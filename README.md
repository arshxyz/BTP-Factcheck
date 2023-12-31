# CombattingDisinformation

BTP-Factcheck is a browser extension that bundles a suite of tools to fight disinformation on the web. These inform the user of a news report's reliability, media bias and objectivity using sophisticated Machine Learning Models.The extension summarises the report for the user's convenience, and suggests similar verified articles.


## Usage
### Within a Site
![Browser Extension Demo 1](https://media.discordapp.net/attachments/933085476041134103/936306003329298452/asatyamain.gif?width=540&height=629)
<br/>
<br/>

### Right Clicking a Link

![Browser Extension Demo 2](https://media.discordapp.net/attachments/933085476041134103/936306058828333066/rightclick.gif?width=540&height=475)

## Features
1. Machine Learning Predictor for News Reliability
2. Displaying Media Bias
3. Displaying Objectivity
4. Suggested Articles using keyword extraction
5. Article Summariser using Extractive Summarisation Algorithm

## Install and Test
Follow below instructions to run the Asatya Browser Extension.

```bash
git clone https://github.com/MananSuri27/CombattingDisinformation.git
cd CombattingDisinformation
cd extension 
npm i
npm run build
cd ..
pip install -r requirements.txt
python3 -m flask run
```

Now open chrome, go to chrome://extensions/ or “more tools -> extensions”
Then, turn on the developer mode at the top-right corner
Then, in top-left corner click on load unpacked, then follow this path 
CombattingDisinformation -> extension -> build

Now at the top right pin our “Asatya” extension and enjoy the seamless experience :)

##  [Demo Video](https://youtu.be/UaPHJ3a_eC4)

## Team
- Arsh Kohli
- Mohit Godara
- Satvik Gupta
- Rishabh Thakur

## Attributions
[Kaggle: Fake and real news dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)<br/>
[COVID19 Fake News Detection in English](https://github.com/diptamath/covid_fake_news)<br/>
[Media Bias Fact Check](https://mediabiasfactcheck.com/)<br/>











