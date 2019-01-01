# Word Segmentation

## VLSP 2013

The training set consists of 75k manually word-segmented sentences (about 23 words per sentence in average). The test set consists of 2120 sentences (about 31 words per sentence) in 10 files from 800001.seg to 800010.seg.

### Leaderboard

<table>
  <tr>
    <th>Model</th>
    <th>F1</th>
    <th>Method</th>
    <th>Reference</th>
    <th>Code</th>
  </tr>
  <tr>
    <td>RDRsegmenter</td>
    <td>97.90</td>
    <td><a href="http://www.lrec-conf.org/proceedings/lrec2018/pdf/55.pdf">Nguyen et al. LREC'18</a></td>
    <td></td>
    <td><a href="https://github.com/vncorenlp/VnCoreNLP">Official</a></td>
  </tr>
  <tr>
    <td>jPTDP-v2</td>
    <td>97.90</td>
    <td><a href="http://www.aclweb.org/anthology/K18-2008">Nguyen et al. CoNLL'18</a></td>
    <td><a href="https://arxiv.org/pdf/1812.11459.pdf">Nguyen et al. arxiv'18</a></td>
    <td><a href="https://github.com/vncorenlp/VnCoreNLP">Official</a></td>
  </tr>
   <tr>
    <td>Biaffine</td>
    <td>97.90</td>
    <td><a href="https://arxiv.org/pdf/1611.01734.pdf">Dozat and Manning ICLR'17</a></td>
    <td><a href="https://arxiv.org/pdf/1812.11459.pdf">Nguyen et al. arxiv'18</a></td>
    <td><a href="https://github.com/vncorenlp/VnCoreNLP">Official</a></td>
  </tr>
  <tr>
    <td>UETsegmenter</td>
    <td>97.87</td>
    <td><a href="https://drive.google.com/file/d/1EEbEJCCieHD9yPBDHr2VP_k_6-qCjdjL/view?usp=sharing">Nguyen et al. RIVF'16</a></td>
    <td></td>
    <td><a href="https://github.com/phongnt570/UETsegmenter">Official</a></td>
  </tr>
  <tr>
    <td>JointWPD</td>
    <td>97.78</td>
    <td><a href="https://arxiv.org/pdf/1812.11459.pdf">Nguyen et al. arxiv'18</a></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>vnTokenizer</td>
    <td>97.33</td>
    <td><a href="https://link.springer.com/chapter/10.1007/978-3-540-88282-4_23">Le et al. LATA'08</a></td>
    <td></td>
    <td><a href="https://github.com/phuonglh/vn.vitk">Official</a></td>
  </tr>
  <tr>
  <tr>
    <td>JVnSegmenter</td>
    <td>97.06</td>
    <td><a href="https://www.semanticscholar.org/paper/Vietnamese-Word-Segmentation-with-CRFs-and-SVMs%3A-An-Nguyen-Nguyen/3927b5e7eaf4350382306d072c4799fbbcfb2dbc">Nguyen et al. PACLIC'06</a></td>
    <td></td>
    <td><a href="http://jvnsegmenter.sourceforge.net/">Official</a></td>
  </tr>
  <tr>
  <tr>
    <td>DongDu</td>
    <td>96.90</td>
    <td></td>
    <td></td>
    <td><a href="http://viet.jnlp.org/dongdu">Official</a></td>
  </tr>
</table>

## VietTreeBank

**References**

* :scroll: [Vietnamese Treebank paper (Nguyen et al. 2009)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.164.6770&rep=rep1&type=pdf)

## Miscellaneous

:scroll: **Papers**

* [Nguyen et al. LREC'18](https://arxiv.org/pdf/1709.06307.pdf),
[Liu et al. 2017](https://www.researchgate.net/publication/315949021_Supervised_Ensemble_Learning_for_Vietnamese_Tokenization),
[Liu et al. LREC'16](http://www.lrec-conf.org/proceedings/lrec2016/pdf/266_Paper.pdf),
[Nguyen et al. ICSITech'16](https://drive.google.com/file/d/1BQQuulOIUx_9TNqUcG3HFO39V0AvsK2c/view?usp=sharing),
[Nguyen et al. RIVF'16](https://drive.google.com/file/d/1EEbEJCCieHD9yPBDHr2VP_k_6-qCjdjL/view?usp=sharing),
[Tran et al. 2015](http://ieeexplore.ieee.org/document/7049878/)
* [Tran et al. 2012](https://goo.gl/gkwj6d), [Let et al. 2010](http://link.springer.com/10.1007/978-3-642-12101-2_21),
[Tran et al. 2010](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=katDGDYAAAAJ&citation_for_view=katDGDYAAAAJ:u-x6o8ySG0sC),
[Pham et al. 2009](http://vnu.edu.vn/upload/scopus/232.pdf),
[Le et al. 2008](http://ieeexplore.ieee.org/document/5361713/),
[Nguyen et al. 2006](https://dspace.wul.waseda.ac.jp/dspace/handle/2065/29084)

:dizzy: Services:

* [OpenFPT: Vitk (2017)](http://doc.openfpt.vn/#vitk)

:file_folder: **Open sources**

* [vncorenlp/VnCoreNLP (2018)](https://github.com/vncorenlp/VnCoreNLP) `java`
* [datquocnguyen/RDRsegmenter (2017)](https://github.com/datquocnguyen/RDRsegmenter) `java`
* [UETsegmenter (2016)](https://github.com/phongnt570/UETsegmenter)  `java`
* [Vitk (2016)](https://github.com/phuonglh/vn.vitk)`java`
* [pyvi (2016)](https://pypi.python.org/pypi/pyvi) `python`
* [truongdo/vita (2015)](https://github.com/truongdo/vita) `c++`
* [vTools (2015)](https://github.com/lupanh/vTools) `python`
* [manhtai/vietseg (2015)](https://github.com/manhtai/vietseg) `python`
* [DongDu (2014)](https://github.com/rockkhuya/DongDu)`c++`
* [Roy_VnTokenizer (2014)](https://github.com/roy-a/Roy_VnTokenizer) `python`
* [vnTokenizer (2008)](http://vlsp.hpda.vn:8080/demo/?page=resources) `java`
