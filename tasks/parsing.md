# Parsing

## VLSP 2020 Shared Task Dependency Parsing

Data descriptions

* Training data: 8152 sentences
  * Training Data Package1: All sentences (5069) from DP-2019
  * Training Data Package2: 3083 sentences remain from
* Viettreebank Testing data: 1123 sentences
  * 906 sentences from Viettreebank
  * 217 sentences from vnexpress.vn

Data Annatation

* Word segmentation: Review and correct all word segmentation errors in all data sets
* Part of speech tagging: Review and correct all POS errors in all data sets
* Dependency labels set: 38 main labels 47 sub-labels

### Leaderboard

#### CONLLU

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
    <td>PhoBert+ELMO / Biaffine</td>
    <td>76.27</td>
    <td>84.65</td>
    <td></td>
    <td><a href="https://drive.google.com/file/d/19fWjeVfKUB-oVQv57OydrFOFpckwhJ6N/view?usp=sharing">Doan VLSP'20</a></td>
    <td></td>
  </tr>
  <tr>
    <td>fastText Embed / Biaffine</td>
    <td>75.64</td>
    <td>84.08</td>
    <td></td>
    <td><a href="https://drive.google.com/file/d/1BtQYQfS-LivnkFgIlG3i95o7qxOOG0eZ/view?usp=sharing">Nguyen VLSP'20</a></td>
    <td></td>
  </tr>
   <tr>
    <td></td>
    <td>73.19</td>
    <td>81.71</td>
    <td></td>
    <td><a href="https://drive.google.com/file/d/1Aegu_F6qpIm5SE8b_FANtMFzGDoeXgM_/view?usp=sharing">Nguyen et al. VLSP'20</a></td>
    <td></td>
  </tr>
</table>

#### Raw text

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
    <td>PhoBert+ELMO / Biaffine / VNCoreNLP</td>
    <td>67.32</td>
    <td>76.12</td>
    <td></td>
    <td><a href="https://drive.google.com/file/d/19fWjeVfKUB-oVQv57OydrFOFpckwhJ6N/view?usp=sharing">Doan VLSP'20</a></td>
    <td></td>
  </tr>
  <tr>
    <td>fastText Embed / Biaffine / VNCoreNLP</td>
    <td>65.3</td>
    <td>74.47</td>
    <td></td>
    <td><a href="https://drive.google.com/file/d/1BtQYQfS-LivnkFgIlG3i95o7qxOOG0eZ/view?usp=sharing">Nguyen VLSP'20</a></td>
    <td></td>
  </tr>
   <tr>
    <td></td>
    <td>64.35</td>
    <td>72.85</td>
    <td></td>
    <td><a href="https://drive.google.com/file/d/1Aegu_F6qpIm5SE8b_FANtMFzGDoeXgM_/view?usp=sharing">Nguyen et al. VLSP'20</a></td>
    <td></td>
  </tr>
</table>

## BkTreebank: A Vietnamese Dependency Treebank

BKTreebank 1.0 contains 6,900 sentences annotated with POS tagging and dependency parsing for Vietnamese. The treebank was divided into a training set of 5639 sentences and a test set of 1270 sentences for learning and testing POS tagging and dependency parsing

* :scroll: [BkTreebank paper (Nguyen LREC'18)](https://arxiv.org/pdf/1710.05519.pdf)
* :link: [BkTreebank website](http://is.hust.edu.vn/~hieunk/bktreebank/)

## Vietnamese Dependency Treebank VnDT

Vietnamese dependency Treebank namely VnDT contains 10200 sentences. The VnDT Treebank is formatted following 10-column data format as proposed by the CoNLL shared tasks on multilingual dependency parsing.

* :scroll: [VnDT paper (Nguyen et al. NLDB'14)](https://people.eng.unimelb.edu.au/dqnguyen/resources/NLDB2014.pdf)
* :link: [VnDT website](http://vndp.sourceforge.net/)

### Leaderboard
#### VnDT v1.1

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
    <td>PhoBERT-base</td>
    <td>78.77</td>
    <td>85.22</td>
    <td><a href="https://arxiv.org/abs/1907.11692">Liu et al. '18</a></td>
    <td><a href="https://arxiv.org/abs/2003.00744">Nguyen et al. '20</td>
    <td><a href="https://github.com/VinAIResearch/PhoBERT">Official</a></td>
  </tr>
    <tr>
    <td>PhoBERT-large</td>
    <td>77.85</td>
    <td>84.32</td>
    <td><a href="https://arxiv.org/abs/1907.11692">Liu et al. '18</a></td>
    <td><a href="https://arxiv.org/abs/2003.00744">Nguyen et al. '20</td>
    <td><a href="https://github.com/VinAIResearch/PhoBERT">Official</a></td>
  </tr>
    <tr>
    <td>Biaffine</td>
    <td>74.99</td>
    <td>81.19</td>
    <td><a href="https://arxiv.org/abs/1611.01734">Dozat and Manning ICLR'17</a></td>
    <td><a href="https://arxiv.org/pdf/1812.11459.pdf">Nguyen '18</td>
    <td></td>
  </tr>
  </tr>
    <tr>
    <td>JointWPD</td>
    <td>73.90</td>
    <td>80.12</td>
    <td><a href="https://arxiv.org/pdf/1812.11459.pdf">Nguyen '18</a></td>
    <td></td>
    <td></td>
  </tr>
  </tr>
    <tr>
    <td>jPTDP-v2</td>
    <td>73.12</td>
    <td>79.63</td>
    <td><a href="https://www.aclweb.org/anthology/K18-2008/">Nguyen et al. CoNLL'18</a></td>
    <td><a href="https://arxiv.org/pdf/1812.11459.pdf">Nguyen '18</td>
    <td><a href="https://github.com/datquocnguyen/jPTDP">Official</a></td>
  </tr>
  </tr>
    <tr>
    <td>VnCoreNLP (unsegmented)</td>
    <td>71.38</td>
    <td>77.35</td>
    <td><a href="https://www.aclweb.org/anthology/N18-5012/">Nguyen et al. NAACL'18</a></td>
    <td><a href="https://arxiv.org/pdf/1812.11459.pdf">Nguyen '18</td>
    <td><a href="https://github.com/vncorenlp/VnCoreNLP">Official</a></td>
  </tr>
</table>
<table>
  
#### VnDT v1.0

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
