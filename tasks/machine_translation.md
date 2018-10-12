# Machine Translation

## IWSLT 2015 Evaluation Campaign

[IWSLT 2015](http://workshop2015.iwslt.org/): The IWSLT 2015 Evaluation Campaign featured three tracks: automatic speech recognition (ASR), spoken language translation (SLT), and machine translation (MT). For ASR we offered two tasks, on English and German, while for SLT and MT a number of tasks were proposed, involving English, German, French, Chinese, Czech, Thai, and Vietnamese.

`TED Data En-Vi`: 131k sentences (train), 1080 sentences (tst2015) 

### Leaderboard

**TED: MT English-Vietnamese**

| Method    | BLEU   | NIST    | TER   | Year |
|-----------|--------|---------|-------|------|
| PJAIT     | **28.39**  | 6.6650  | 56.01 | 2015 |
| JAIST     | 28.17  | **6.7092**  | 55.84 | 2015 |
| KIT       | 26.60  | 6.4014  | 58.26 | 2015 |
| SU        | 26.41  | 6.5986  | **55.60** | 2015 |
| UNETI     | 22.93  | 6.0218  | 60.33 | 2015 |
| BASELINE  | 27.01  | 6.4716  | 58.42 | 2015 |

**TED: MT Vietnamese-English**

| Method    | BLEU   | NIST    | TER   | Year |
|-----------|--------|---------|-------|------|
| PJAIT     | **23.46**  | 5.7314  | 62.20 | 2015 |
| UMD       | 21.57  | **5.7831**  | **59.19** | 2015 |
| JAIST     | 21.53  | 5.6413  | 62.35 | 2015 |
| UNETI     | 20.18  | 5.1443  | 66.33 | 2015 |
| TUT       | 19.78  | 5.4559  | 62.69 | 2015 |
| BASELINE  | 24.61  | 5.9259  | 59.32 | 2015 |

**References**

* `Task Description` **The IWSLT 2015 Evaluation Campaign** (2015), M. Cettolo et al. [[pdf](http://workshop2015.iwslt.org/downloads/IWSLT_2015_EP_0.pdf)]
* `UNETI '15` **The English-Vietnamese Machine Translation System for IWSLT 2015** (2015), H. Tran et al. [[link](http://workshop2015.iwslt.org/downloads/IWSLT_2015_EP_3.pdf)]
* `PJAIT '15` **PJAIT Systems for the IWSLT 2015 Evaluation Campaign Enhanced by Comparable Corpora** (2015), K. Wolk et al. [[pdf](https://arxiv.org/pdf/1512.01639.pdf)]
* `TUD '15` **Improvement of Word Alignment Models for Vietnamese-to-English Translation** (2015), A. Axelrod et al. [[pdf](http://workshop2015.iwslt.org/downloads/IWSLT_2015_EP_9.pdf)]
* `UMD '15` **The UMD Machine Translation Systems at IWSLT 2015** (2015), T. Nomura et al. [[pdf](https://pdfs.semanticscholar.org/ce1c/bbd597e91e707aa4357a4f44a81d43ddfbbb.pdf)]
* `KIT '15` **The KIT Translation Systems for IWSLT 2015** (2015), T. Ha et al. [[pdf](http://workshop2015.iwslt.org/downloads/IWSLT_2015_EP_17.pdf)]
* `JAIST '15` `UET '15` **The JAIST-UET-MITI Machine Translation Systems for IWSLT 2015** (2015), H. Trieu et al. [[pdf](http://workshop2015.iwslt.org/downloads/IWSLT_2015_EP_6.pdf)]
* `SU '15` **Stanford Neural Machine Translation Systems for Spoken Language Domains** (2015), M. Luong et al. [[pdf](https://nlp.stanford.edu/pubs/luuongong-manning-iwslt15.pdf)]

## Miscellaneous

:file_folder: **Open sources**

* [duyvuleo/Transformer-DyNet (2018-)](https://github.com/duyvuleo/Transformer-DyNet) `dynet,python`
* [polyglot (2014-2017)](http://polyglot.readthedocs.io/en/latest/Transliteration.html) `c++,java,python`
* [EVBCorpus (2016)](https://sourceforge.net/projects/evbc/) `data`
