# Text Classification

Text classification algorithms are at the heart of a variety of software systems that process text data at scale. Email software uses text classification to determine whether incoming mail is sent to the inbox or filtered into the spam folder. Discussion forums use text classification to determine whether comments should be flagged as inappropriate.

These are two examples of topic classification, categorizing a text document into one of a predefined set of topics. In many topic classification problems, this categorization is based primarily on keywords in the text.

## VNTC 

* :scroll: [VNTC paper (Vu et al. RIVF'07)](http://docshare01.docshare.tips/files/4624/46242178.pdf)
* :file_folder: [VNTC data](https://github.com/duyvuleo/VNTC)

A Large-scale Vietnamese News Text Classification Corpus

Level 1: 10 topics, 33,759 documents for training and 50,373 documents for testing

<table>
  <tr>
    <th>Model</th>
    <th>Score</th>
    <th>Paper / Source </th>
    <th>Code</th>
  </tr>
  <tr>
    <td>NGRAM</td>
    <td>97.1</td>
    <td><a href="http://docshare01.docshare.tips/files/4624/46242178.pdf">Vu et al. RIVF'07</a></td>
    <td></td>
  </tr>
  <tr>
    <td>SVM Multi</td>
    <td>93.4</td>
    <td><a href="http://docshare01.docshare.tips/files/4624/46242178.pdf">Vu et al. RIVF'07</a></td>
    <td></td>
  </tr>
</table>

Level 2: 27 topics, 14375 documents for training and 12076 documents for testing

<table>
  <tr>
    <th>Model</th>
    <th>Score</th>
    <th>Paper / Source </th>
    <th>Code</th>
  </tr>
  <tr>
    <td>SVM Multi</td>
    <td>96.21</td>
    <td><a href="http://docshare01.docshare.tips/files/4624/46242178.pdf">Vu et al. RIVF'07</a></td>
    <td></td>
  </tr>
</table>

## Miscellaneous

:scroll: **Papers**

* [Le et al. NICS'18. A Comparative Study of Neural Network Models for Sentence Classification](https://drive.google.com/file/d/1uCBtYHJJ7b_MYZvPQttdUu6y9SPmbMoZ/view?usp=sharing)
* [Zhu et al. CCC'15](https://drive.google.com/file/d/1jpAVOfn-utsLWCEv7EffjL5hTix3lNfu/view?usp=sharing), 
[Nguyet et al. KSE'15](https://drive.google.com/file/d/15o2-wC6p_tN5V-fcJcjx9k1F1VV6IcwO/view?usp=sharing), 
[Vu et al. FDSE'15](https://drive.google.com/file/d/1YC7xAWt_r4KVe3u90WLct8OiPoqXbMVu/view?usp=sharing)

:dizzy: **Services**

* [OpenFPT: Name to Gender (2017)](http://doc.openfpt.vn/#vitk)

:file_folder: **Open sources**

* [suicao/transformer-text-classifier (2018)](https://github.com/suicao/transformer-text-classifier) `python`
* [pth1993/vn_spam_sms_filtering (2017)](https://github.com/pth1993/vn_spam_sms_filtering) `python` 
* [duyvuleo/VNTC (2007)](https://github.com/duyvuleo/VNTC) `data`
