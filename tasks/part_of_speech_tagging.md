# Part of Speech Tagging

## VLSP 2013

27,870 sentences for training and development from the VLSP 2013 POS tagging shared task:

* 27k sentences are used for training.
* 870 sentences are used for development.

Test data: 2120 test sentences from the VLSP 2013 POS tagging shared task.

<table>
  <tr>
    <th>Model</th>
    <th>Accuracy</th>
    <th>Method</th>
    <th>Reference</td>
    <th>Code</th>
  </tr>
  <tr>
    <td>PhoBERT-large</td>
    <td>96.8</td>
    <td><a href="https://arxiv.org/abs/2003.00744">Nguyen et al. ArXiv'20</a></td>
    <td></td>
    <td><a href="https://github.com/VinAIResearch/PhoBERT">Official</a></td>
  </tr>
  <tr>
    <td>vELECTRA</td>
    <td>96.77</td>
    <td><a href="https://arxiv.org/abs/2006.15994">Bui et al. ArXiv'20</a></td>
    <td></td>
    <td><a href="https://github.com/fpt-corp/viBERT">Official</a></td>
  </tr>
  <tr>
    <td>PhoBERT-base</td>
    <td>96.7</td>
    <td><a href="https://arxiv.org/abs/2003.00744">Nguyen et al. ArXiv'20</a></td>
    <td></td>
    <td><a href="https://github.com/VinAIResearch/PhoBERT">Official</a></td>
  </tr>
  <tr>
    <td>VnMarMoT</td>
    <td>95.88</td>
    <td><a href="http://aclweb.org/anthology/N18-5012">Nguyen et al. NAACL'18</a></td>
    <td></td>
    <td><a href="https://github.com/vncorenlp/VnCoreNLP">Official</a></td>
  </tr>
  <tr>
    <td>BiLSTM-CRFs + CNN-char</td>
    <td>95.40</td>
    <td><a href="http://aclweb.org/anthology/N18-5012">Ma et al. ACL'16</a></td>
  <td><a href="http://aclweb.org/anthology/N18-5012">Nguyen et al. NAACL'18</a></td>
    <td><a href="https://github.com/UKPLab/emnlp2017-bilstm-cnn-crf/">Link</a></td>
  </tr>
  <tr>
    <td>BiLSTM-CRF + LSTM-char</td>
    <td>95.31</td>
    <td><a href="http://www.aclweb.org/anthology/N16-1030">Lample et al. NAACL'16</a></td>
  <td><a href="http://aclweb.org/anthology/N18-5012">Nguyen et al. NAACL'18</a></td>
    <td><a href="https://github.com/UKPLab/emnlp2017-bilstm-cnn-crf/">Link</a></td>
  </tr>
  <tr>
    <td>BiLSTM-CRF</td>
    <td>95.31</td>
    <td><a href="https://arxiv.org/abs/1508.01991">Huang et al. ArXiv'15</a></td>
  <td><a href="http://aclweb.org/anthology/N18-5012">Nguyen et al. NAACL'18</a></td>
    <td><a href="https://github.com/UKPLab/emnlp2017-bilstm-cnn-crf/">Link</a></td>
  </tr>
  <tr>
    <td>RDRPOSTagger</td>
    <td>95.11</td>
    <td><a href="https://www.researchgate.net/publication/279916333_RDRPOSTagger_A_Ripple_Down_Rules-based_Part-Of-Speech_Tagger">Nguyen et al. EACL'14</a></td>
    <td></td>
    <td><a href="https://github.com/datquocnguyen/rdrpostagger">Official</a></td>
  </tr>
 <tr>
    <td>JointWPD</td>
    <td>94.03</td>
    <td><a href="https://arxiv.org/pdf/1812.11459.pdf">Nguyen et al. '18</a></td>
    <td></td>
    <td></td>
  </tr>
</table>

## VietTreeBank

* :scroll: [VietTreeBank Paper](https://hal.inria.fr/inria-00421103v2/document)

Dataset

* train: 7268 sentences, dev: 1038 sentences, test: 2077 sentences
* labels: N, V, CH, R, E, A, P, Np, M, N, Nc, L, T, Ny, Nu, X, B, S, I, Y, Vy

<table>
  <tr>
    <th>Model</th>
    <th>Accuracy</th>
    <th>Method</th>
    <th>Reference</th>
    <th>Code</th>
    <th>Note</th>
  </tr>
  <tr>
    <td>BiLSTM-CRFs</td>
    <td>93.52</td>
    <td><a href="https://arxiv.org/pdf/1811.03754.pdf">Nguyen et al. '18</a></td>
    <td></td>
    <td><a href="https://github.com/duongna21/VNsequencelabeling">Official</a></td>
    <td>10-fold CV</td>
  </tr>
  <tr>
    <td>VNTagger</td>
    <td>93.40</td>
    <td><a href="https://hal.inria.fr/inria-00526139/document">Le et al. TALN'10</a></td>
    <td></td>
    <td><a href="http://mim.hus.vnu.edu.vn/dsl/tools/tagger">Official</a></td>
    <td>10-fold CV</td>
  </tr>
  <tr>
    <td>RDRPOSTagger</td>
    <td>91.96</td>
    <td></td>
    <td><a href="http://aclweb.org/anthology/I17-3010">Pham et al. IJCNLP'17</a></td>
    <td><a href="https://github.com/datquocnguyen/RDRPOSTagger">Official</a></td>
    <td>5-fold CV</td>
  </tr>
  <tr>
    <td>NNVLP</td>
    <td>91.92</td>
    <td><a href="http://aclweb.org/anthology/I17-3010">Pham et al. IJCNLP'17</a></td>
    <td></td>
    <td><a href="https://github.com/pth1993/NNVLP">Official</a></td>
    <td>5-fold CV</td>
  </tr>
  <tr>
    <td>vTools</td>
    <td>90.73</td>
    <td>
      <a href="https://drive.google.com/file/d/1V06YfENrguQk2SRJFbpwWzapxpgPPaPS/view?usp=sharing">Tran et al. VLSP'13</a>
    </td>
    <td><a href="http://aclweb.org/anthology/I17-3010">Pham et al. IJCNLP'17</a></td>
    <td><a href="https://github.com/lupanh/vTools">Official</a></td>
    <td></td>
  </tr>
  <tr>
    <td>Vitk</td>
    <td>88.41</td>
    <td></td>
    <td><a href="http://aclweb.org/anthology/I17-3010">Pham et al. IJCNLP'17</a></td>
    <td><a href="https://github.com/phuonglh/vn.vitk">Official</a></td>
    <td></td>
  </tr>
</table>

## Social Media Text

:scroll: **Papers**

* [Vietnamese POS Tagging for Social Media Text - Ngo et al. 2016](https://www.researchgate.net/publication/309176280_Vietnamese_POS_Tagging_for_Social_Media_Text)
* [A POS Tagging Model for Vietnamese Social Media Text Using BiLSTM-CRF with Rich Features - Ngo et al. 2019](https://www.researchgate.net/publication/335361630_A_POS_Tagging_Model_for_Vietnamese_Social_Media_Text_Using_BiLSTM-CRF_with_Rich_Features)
* [An Empirical Study on POS Tagging for Vietnamese Social Media Text - Ngo et al. 2017](https://www.researchgate.net/publication/321940724_An_Empirical_Study_on_POS_Tagging_for_Vietnamese_Social_Media_Text)

## Miscellaneous

:scroll: **Papers**

* [Nguyen et al. NICS'18. Building Vietnamese Linguistic Resources for Social Network Text Analysis](https://drive.google.com/file/d/1V6zFx7p-tLV6ZRiyLhVvbjI12PKyQnmF/view?usp=sharing)
* [Nguyen et al. ALTA'17](https://arxiv.org/pdf/1711.04951.pdf),
[Nguyen et al. 2015](https://arxiv.org/pdf/1412.4021.pdf)
* [Nguyen et al. 2014](http://www.aclweb.org/anthology/E14-2005),
[Nguyen et al. 2011](https://link.springer.com/chapter/10.1007/978-3-642-19400-9_15),
[Nguyen et al. 2011](http://ieeexplore.ieee.org/document/6063458/?reload=true), [Nguyen et al. 2010](http://www.aclweb.org/anthology/I11-1035)
* [Ngo et al. 2016](https://www.researchgate.net/publication/309176280_Vietnamese_POS_Tagging_for_Social_Media_Text),
[Phan et al. 2008](http://www.jaist.ac.jp/~bao/VLSP-text/ICTrda08/ICT08-VLSP-SP83.pdf),
[Nguyen et al. 2006](http://www.vnulib.edu.vn:8000/dspace/bitstream/123456789/1801/1/sedev0206-02.pdf)
* [Nguyen et al. 2003](http://www.vietlex.com/xu-li-ngon-ngu/50-A_Case_Study_in_POS_Tagging_of_Vietnamese_Texts)

:dizzy: **Services**

* [OpenFPT: Vietnamese Accentizer (2017)](http://doc.openfpt.vn/#vietnamese-accentizer)

:file_folder: **Open sources**

* [vncorenlp/VnCoreNLP (2018)](https://github.com/vncorenlp/VnCoreNLP) `java`
* [pth1993/NNVLP (2017)](https://github.com/pth1993/NNVLP) `python,bash`
* [pyvi (2016)](https://pypi.python.org/pypi/pyvi) `python`
* [Vitk (2016)](https://github.com/phuonglh/vn.vitk) `java`
* [kanjirz50/viet-morphological-analysis-crf (2016)](https://github.com/kanjirz50/viet-morphological-analysis-crf), [demonstration](http://160.16.58.116/vietnamese/morph_crf) `python`
* [lupanh/vTools (2015)](https://github.com/lupanh/vTools) `python`
* [truongdo/vita (2015)](https://github.com/truongdo/vita) `c++`
* [RDRPOSTagger (2013-2017)](http://rdrpostagger.sourceforge.net/) `python`
* [vnTagger (2010)](http://vlsp.hpda.vn:8080/demo/?page=resources) `java`
