# Word Segmentation

## Vietnamese treebank

The training set consists of 75k manually word-segmented sentences (about 23 words per sentence in average). The test set consists of 2120 sentences (about 31 words per sentence) in 10 files from 800001.seg to 800010.seg.

* :scroll: [Vietnamese Treebank paper (Nguyen et al. 2009)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.164.6770&rep=rep1&type=pdf)

### Leaderboard

<table>
  <tr>
    <th>Model</th>
    <th>Score</th>
    <th>Paper / Source </th>
    <th>Code</th>
  </tr>
  <tr>
    <td>RDRsegmenter</td>
    <td>97.90</td>
    <td><a href="http://www.lrec-conf.org/proceedings/lrec2018/pdf/55.pdf">Nguyen et al. LREC'18</a></td>
    <td><a href="https://github.com/vncorenlp/VnCoreNLP">Official</a></td>
  </tr>
  <tr>
    <td>UETsegmenter</td>
    <td>97.87</td>
    <td><a href="https://drive.google.com/file/d/1EEbEJCCieHD9yPBDHr2VP_k_6-qCjdjL/view?usp=sharing">Nguyen et al. RIVF'16</a></td>
    <td><a href="https://github.com/phongnt570/UETsegmenter">Official</a></td>
  </tr>
  <tr>
    <td>DongDu</td>
    <td>97.87</td>
    <td></td>
    <td><a href="http://viet.jnlp.org/dongdu">Official</a></td>
  </tr>
</table>

