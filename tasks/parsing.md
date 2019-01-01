# Parsing

## BkTreebank: A Vietnamese Dependency Treebank

BKTreebank 1.0 contains 6,900 sentences annotated with POS tagging and dependency parsing for Vietnamese. The treebank was divided into a training set of 5639 sentences and a test set of 1270 sentences for learning and testing POS tagging and dependency parsing

* :scroll: [BkTreebank paper (Nguyen LREC'18)](https://arxiv.org/pdf/1710.05519.pdf)
* :link: [BkTreebank website](http://is.hust.edu.vn/~hieunk/bktreebank/)

## Vietnamese Dependency Treebank VnDT

Vietnamese dependency Treebank namely VnDT contains 10200 sentences. The VnDT Treebank is formatted following 10-column data format as proposed by the CoNLL shared tasks on multilingual dependency parsing.

* :scroll: [VnDT paper (Nguyen et al. 2014)](https://people.eng.unimelb.edu.au/dqnguyen/resources/NLDB2014.pdf)

### Leaderboard

<table>
  <tr>
    <th>Model</th>
    <th>LAS</th>
    <th>UAS</th>
    <th>Method</th>
    <th>Reference</th>
    <th>Code</th>
  </tr>
  <tr>
    <td>VnCoreNLP</td>
    <td>73.39</td>
    <td>79.02</td>
    <td><a href="http://aclweb.org/anthology/N18-5012">Nguyen et al. NAACL'18</a></td>
    <td></td>
    <td><a href="https://github.com/vncorenlp/VnCoreNLP">Official</a></td>
  </tr>
  <tr>
    <td>Biaffine</td>
    <td>71.73</td>
    <td>78.45</td>
    <td><a href="https://arxiv.org/pdf/1611.01734.pdf">Dozat and Manning ICLR'17</a></td>
    <td><a href="https://arxiv.org/pdf/1812.11459.pdf">Nguyen '18</a></td>
    <td></td>
  </tr>
  <tr>
    <td>JointWPD</td>
    <td>70.50</td>
    <td>77.04</td>
    <td><a href="https://arxiv.org/pdf/1812.11459.pdf">Nguyen '18</a></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>jPTDP-v2</td>
    <td>69.81</td>
    <td>76.60</td>
    <td><a href="http://www.aclweb.org/anthology/K18-2008">Nguyen et al. CoNLL'18</a></td>
    <td><a href="https://arxiv.org/pdf/1812.11459.pdf">Nguyen '18</a></td>
    <td><a href="https://github.com/datquocnguyen/jPTDP">Official</a></td>
  </tr> 
  <tr>
    <td>VnCoreNLP (unsegmented)</td>
    <td>67.79</td>
    <td>74.24</td>
    <td><a href="http://aclweb.org/anthology/N18-5012">Nguyen et al. NAACL'18</a></td>
    <td><a href="https://arxiv.org/pdf/1812.11459.pdf">Nguyen '18</a></td>
    <td><a href="https://github.com/vncorenlp/VnCoreNLP">Link</a></td>
  </tr>
</table>

## VietTreebank

* :scroll: [VietTreebank paper (Nguyen et al. 2009)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.164.6770&rep=rep1&type=pdf)

## Miscellaneous

:scroll: **Papers**

* [Nguyen et al. KSE'18](https://drive.google.com/file/d/1NSJTaGUlbj_IOh7OU3_A_R172v772dvi/view?usp=sharing)
* [Nguyen et al. 2016](https://ieeexplore.ieee.org/document/7758049/)
* [Le et al. 2015](https://link.springer.com/chapter/10.1007/978-3-319-25660-3_22), [Nguyen et al. KSE'15](https://ieeexplore.ieee.org/document/7371762/)

:dizzy: Services: [OpenFPT: Vitk (2017)](http://doc.openfpt.vn/#vitk)

:file_folder: **Open sources**

* [datquocnguyen/jPTDP (2017)](https://github.com/datquocnguyen/jPTDP) `java`
* [phuonglh/vn.vitk (2016)](https://github.com/phuonglh/vn.vitk) `java`
* [VnDP (2014)](http://vndp.sourceforge.net/) `java`
