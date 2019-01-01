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
    <td>BiLSTM-CRFs</td>
    <td>96.30</td>
    <td><a href="https://arxiv.org/pdf/1811.03754.pdf">Nguyen et al. 2018</a></td>
    <td></td>
    <td><a href="https://github.com/duongna21/VNsequencelabeling">Official</a></td>
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
    <td><a href="https://arxiv.org/pdf/1812.11459.pdf">Nguyen et al. arxiv'18</a></td>
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

## Miscellaneous

:scroll: **Papers**

* [Nguyen et al. ALTA'17](https://arxiv.org/pdf/1711.04951.pdf),
[Nguyen et al. 2015](https://arxiv.org/pdf/1412.4021.pdf)
* [Nguyen et al. 2014](http://www.aclweb.org/anthology/E14-2005),
[Nguyen et al. 2011](https://link.springer.com/chapter/10.1007/978-3-642-19400-9_15),
[Nguyen et al. 2011](http://ieeexplore.ieee.org/document/6063458/?reload=true), [Nguyen et al. 2010](http://www.aclweb.org/anthology/I11-1035)
* [Tran et al. 2009](https://www.researchgate.net/publication/309176280_Vietnamese_POS_Tagging_for_Social_Media_Text),
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
