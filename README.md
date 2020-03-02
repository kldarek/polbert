# Polbert - Polish BERT
Description here... intended uses & limitations, etc.

![PolBERT image](/img/polbert.png)

## Pre-training corpora

Below is the list of corpora used along with the output of 'wc' command (counting lines, words and characters). These corpora were divided into sentences with srxsegmenter (see references), concatenated and tokenized with HuggingFace BERT Tokenizer. 

| Tables        | Lines           | Words  | Characters  |
| ------------- |--------------:| -----:| -----:|
| [Polish subset of Open Subtitles](http://opus.nlpl.eu/OpenSubtitles-v2018.php)      | 236635408| 1431199601 | 7628097730 |
| [Polish subset of ParaCrawl](http://opus.nlpl.eu/ParaCrawl.php)     | 8470950      |   176670885 | 1163505275 |
| [Polish Parliamentary Corpus](http://clip.ipipan.waw.pl/PPC) | 9799859      |    121154785 | 938896963 |
| [Polish Wikipedia - Feb 2020](https://dumps.wikimedia.org/plwiki/latest/plwiki-latest-pages-articles.xml.bz2) | 8014206      |    132067986 | 1015849191 |
| Total | 262920423      |    1861093257 | 10746349159 |

## Pre-training details
training params (dataset, preprocessing, hyperparameters), 

## Usage

## Evaluation
evaluation results, 

## Bias

## Acknowledgements
Tino etc., Google TFRC

## Author

## References
* Bert
* Srx 1
* Srx 2
