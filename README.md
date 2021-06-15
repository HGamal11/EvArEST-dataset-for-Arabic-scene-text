# EvArEST

Everyday Arabic-English Scene Text dataset

### Detection Dataset

The text detection dataset has 510 images all containing one or more instances of text. Each word is annotated with a four-point polygon that starts with the top left corner of the polygon and follows clockwise. Each image comes with a text file containing three attributes: the four points of the polygon that contains the word, the language of the word.  

![alt text](https://github.com/HGamal11/EvArEST-dataset/blob/main/DetEx.png?raw=true)

[Training Data](https://drive.google.com/file/d/1a1Jf12nyIDswunky5kLM4JishRj2_4Jy/view?usp=sharing)

[Test Data](https://drive.google.com/file/d/15jWxmZb9zoKHys40Cuz-57kV2PTO-cvH/view?usp=sharing)

### Recognition Dataset

The text recognition dataset comprises of 7232 cropped word images of both Arabic and English languages. The groundtruth for the recognition dataset is provided by a text file with each line containing the image file name and the text in the image. The dataset could be used for Arabic text recognition only and could be used for bilingual text recognition. 

![alt text](https://github.com/HGamal11/EvArEST-dataset/blob/main/RecogEx.png?raw=true)

Training Data:

[Arabic](https://drive.google.com/file/d/1ADdCb66VvndcBnRo38IIymL9HZsE4FNx/view?usp=sharing)-
[English](https://drive.google.com/file/d/1vyypcLpX6DTuogNxTeueRRl_PLvcbRsz/view?usp=sharing)

Test Data:

[Arabic](https://drive.google.com/file/d/1P1SnF4ZKOA1PBC6HRAYLxZa82eOGFR2F/view?usp=sharing)-
[English](https://drive.google.com/file/d/1HCPSAeJGNP5LtdIjAuu7ZbeFDTubMYDx/view?usp=sharing)

### Synthetic Data

About 200k synthetic images with segmentation maps.

[SynthData](https://drive.google.com/file/d/1PjfqY4ofK2jy85KbD1ITIma4JFz7fbuw/view?usp=sharing)


### Other Resources for Arabic Data

ICDAR 2019 Robust Reading Challenge on Multi-lingual scene text detection and recognition

https://rrc.cvc.uab.es/?ch=15&com=tasks

Synthetic MLT Data

https://github.com/MichalBusta/E2E-MLT


