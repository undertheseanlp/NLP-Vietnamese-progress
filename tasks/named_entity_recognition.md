# Named Entity Recognition

Named entity recognition (NER) is the task of tagging entities in text with their corresponding type. Approaches typically use BIO notation, which differentiates the beginning (B) and the inside (I) of entities. O is used for non-entity tokens.

Example:

| Mark | Watney | visited | Mars |
| --- | ---| --- | --- |
| B-PER | I-PER | O | B-LOC |

### Contents

* [VLSP 2018 Shared Task: Named Entity Recognition](#vlsp-2018-shared-task-named-entity-recognition)
* [VLSP 2016 Shared Task: Named Entity Recognition](#vlsp-2016-shared-task-named-entity-recognition)

## VLSP 2018 Shared Task: Named Entity Recognition

* :link: [VLSP 2018 Shared Task: Named Entity Recognition Website](http://vlsp.org.vn/vlsp2018/eval/ner)
* :file_folder: [VLSP 2018 Shared Task: Annotation Guildlines](https://drive.google.com/file/d/1wVdfkWgsRgTiXA4b_G8OGeugP03YBSrg/view?usp=sharing)

The size of VLSP 2018 dataset

<table>
  <tr>
    <th>Type</th>
    <th>Train</th>
    <th>Test</th>
    <th>Dev</th>
  </tr>
  <tr>
    <td>LOC</td>
    <td>8,831</td>
    <td>2,525</td>
    <td>3,043</td>
  </tr>
  <tr>
    <td>ORG</td>
    <td>3,471</td>
    <td>1,616</td>
    <td>1,203</td>
  </tr>
  <tr>
    <td>PER</td>
    <td>6,427</td>
    <td>3,518</td>
    <td>2,168</td>
  </tr>
  <tr>
    <td>MISC</td>
    <td>805</td>
    <td>296</td>
    <td>179</td>
  </tr>
</table>

### Leaderboard

<table>
  <tr>
    <th>Model</th>
    <th>F1</th>
    <th>Paper/Source</th>
    <th>Code</th>
  </tr>
   <tr>
    <td>VNER<br>Attentive Neural Network</td>
    <td>77.52</td>
    <td><a href="https://arxiv.org/pdf/1810.13097.pdf">Dong et al. 2018</a></td>
    <td></td>
  </tr>
  <tr>
    <td>vietner<br>CRF (ngrams + word shapes + cluster + w2v)</td>
    <td>76.63</td>
    <td><a href="https://arxiv.org/pdf/1803.08463.pdf">Pham et al. VLSP'18</a></td>
    <td><a href="https://github.com/minhpqn/vietner">Official</a></td>
  </tr>
  <tr>
    <td>ZA-NER<br>BiLSTM</td>
    <td>74.70</td>
    <td><a href="https://drive.google.com/file/d/1tLPn6DZgJ1QbyINJPZ69lF1aSPLV0HWE/view?usp=sharing">Luong et al. VLSP'18</a></td>
    <td></td>
  </tr>
  <tr>
    <td>Dong et al. 2018</td>
    <td>66.07</td>
    <td><a href="https://drive.google.com/file/d/10FPPK2dtGmG0iLlaSuCeclwfRa5G1mOE/view?usp=sharing">Dong et al. VLSP'18</a></td>
    <td></td>
  </tr>
</table>


## VLSP 2016 Shared Task: Named Entity Recognition

* :link: [VLSP 2016 Shared Task: Named Entity Recognition Website](http://vlsp.org.vn/vlsp2016/eval/ner)
* :scroll: [VLSP 2016 Shared Task: Named Entity Recognition Paper](https://drive.google.com/file/d/18FuXxRM0slTeReQUCOj8IiToB5eqVQCT/view?usp=sharing)

16,861 sentences for training and development from the VLSP 2016 NER shared task:

* 14,861 sentences are used for training.
* 2k sentences are used for development.

Test data: 2,831 test sentences from the VLSP 2016 NER shared task.

### Leaderboard

Without gold POS and chunking tags

<table>
  <tr>
    <th>Model</th>
    <th>F1</th>
    <th>Paper/Source</th>
    <th>Code</th>
  </tr>
  <tr>
    <td>VNER<br>Attentive Neural Network</td>
    <td>90.37</td>
    <td><a href="https://arxiv.org/pdf/1810.13097.pdf">Dong et al. 2018</a></td>
    <td></td>
  </tr>
  <tr>
    <td>vietner<br>CRF (ngrams + word shapes + cluster + w2v)</td>
    <td>90.03</td>
    <td><a href="https://arxiv.org/pdf/1803.04375.pdf">Pham CICLing'18</a></td>
    <td><a href="https://github.com/minhpqn/vietner">Official</a></td>
  </tr>
  <tr>
    <td>VnCoreNLP<br>dynamic feature induction model</td>
    <td>88.55</td>
    <td><a href="http://aclweb.org/anthology/N18-5012">Nguyen et al. NAACL'18</a></td>
    <td><a href="https://github.com/vncorenlp/VnCoreNLP">Official</a></td>
  </tr>
</table>

With gold POS and chunking tags

<table>
  <tr>
    <th>Model</th>
    <th>F1</th>
    <th>Paper/Source</th>
    <th>Code</th>
  </tr>
  <tr>
    <td>BiLSTM-CRF + POS + Chunk</td>
    <td>94.88</td>
    <td><a href="https://arxiv.org/pdf/1811.03754.pdf">Nguyen et al. 2018</a></td>
    <td><a href="https://github.com/duongna21/VNsequencelabeling">Official</a></td>
  </tr>
  <tr>
    <td>CRFs (PoS, Chunk, word + word shapes + cluster + w2v)</td>
    <td>93.93</td>
    <td><a href="https://arxiv.org/pdf/1803.04375.pdf">Pham CICLing'18</a></td>
    <td></td>
  </tr>
  <tr>
    <td>NNVLP (BiLSTM-CNN-CRF)</td>
    <td>92.91</td>
    <td><a href="https://arxiv.org/pdf/1708.07241.pdf">Pham et al. IJCNLP'17</a></td>
    <td><a href="https://github.com/pth1993/NNVLP">Official</a></td>
  </tr>
  <tr>
    <td>vie-ner-lstm</td>
    <td>92.05</td>
    <td><a href="https://arxiv.org/pdf/1705.10610.pdf">Pham et al. PACLIC'17</a></td>
    <td><a href="https://github.com/pth1993/vie-ner-lstm">Official</a></td>
  </tr>
  <tr>
    <td>Token reguilar expression + ME (Bidirectional Inference)</td>
    <td>88.78</td>
    <td>
      <a href="https://drive.google.com/file/d/1yepeBjeOCWmwMSrGwP-ewhxQBmPpyP0p/view?usp=sharing">Le et al. VLSP'16</a>
    </td>
    <td></td>
  </tr>
  <tr>
    <td>BiLSTM-CNN-CRF</td>
    <td>88.59</td>
    <td><a href="https://arxiv.org/pdf/1705.04044.pdf">Pham et al. PACLIC'17</a></td>
    <td></td>
  </tr>
  <tr>
    <td>ME + Beam Search</td>
    <td>84.08</td>
    <td><a href="https://drive.google.com/file/d/1n4JMtHLsIgaeiAtjPncg64BVumykbHsL/view?usp=sharing">
      Nguyen et al. VLSP'16</a></td>
    <td></td>
  </tr>
  <tr>
    <td>Stack LSTM</td>
    <td>83.80</td>
    <td><a href="https://drive.google.com/file/d/16M0Ry_dHFOY5njVhqy4NV0G2-bfTq6Qt/view?usp=sharing">Nguyen et al. VLSP'16</a></td>
    <td></td>
  </tr>
  <tr>
    <td>BiLSTM-CRF</td>
    <td>83.25</td>
    <td><a href="https://drive.google.com/file/d/16M0Ry_dHFOY5njVhqy4NV0G2-bfTq6Qt/view?usp=sharing">Nguyen et al. VLSP'16</a></td>
    <td></td>
  </tr>
  <tr>
    <td>CRF</td>
    <td>78.38</td>
    <td>
      <a href="https://drive.google.com/file/d/1vg9Bvu6HgiO7KDiKKAPZz9dL3VmlON1I/view?usp=sharing">Le et al. VLSP'16</a>
    </td>
    <td></td>
  </tr>
</table>

## Miscellaneous

:scroll: **Papers**

* [Pham et al. PACLIC'17](https://arxiv.org/pdf/1705.10610.pdf), [Pham et al. IJCNLP'17](https://arxiv.org/pdf/1708.07241.pdf), [Le et al. KSE'17](https://arxiv.org/pdf/1708.09163.pdf)
* [Nguyen et al. 2010](https://pdfs.semanticscholar.org/931a/f0c14c6f32c7e6782cde1007fdddcd3e18c2.pdf?_ga=2.249289476.26579401.1520334621-721084246.1519381355)
* [Tran et al. 2007](https://pdfs.semanticscholar.org/32ec/df1774d24d2461615e5eb448668dfe2a8647.pdf?_ga=2.53162539.26579401.1520334621-721084246.1519381355), [Pham et al. 2007](https://www.semanticscholar.org/paper/Named-entity-recognition-in-Vietnamese-using-class-Thao-Tri/a6aeb599a261a5e077ad430a30b448d41a927132)

:file_folder: **Open sources**

* [vncorenlp/VnCoreNLP (2018)](https://github.com/vncorenlp/VnCoreNLP)`java`
* [pth1993/NNVLP (2017)](https://github.com/pth1993/NNVLP) `python,bash`
* [pth1993/vie-ner-lstm (2017)](https://github.com/pth1993/vie-ner-lstm) `python,keras` 
* [ntson2002/lstm-crf-tagging (2017)](https://github.com/ntson2002/lstm-crf-tagging) `python,theano`
* [polyglot (2014-2017)](http://polyglot.readthedocs.io/en/latest/NamedEntityRecognition.html) `c++,java,python`
* [ai.vitk.ner (2017)](https://github.com/phuonglh/ai.vitk.ner) `scala,java`
