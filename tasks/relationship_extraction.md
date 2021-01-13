# Relationship Extraction

## VLSP 2020 Relation Extraction Task

Data descriptions

* Training set: 506 documents
* Development set: 250 documents
* Test set: 300 documents

Three named entities types: Location (LOC), Organiation (ORG), Person (PER)

Four relation types: LOCATED, PART-WHOLE, PERSONAL-SOCIAL, ORGANIZATION-AFFILIATION

### Leaderboard

<table>
  <tr>
    <th>Model</th>
    <th>F1 (micro-averaged)</th>
    <th>F1 (macro-averaged)</th>
    <th>Method</th>
    <th>Reference</th>
    <th>Code</th>
  </tr>
  <tr>
    <td>RELEX2020_HT</td>
    <td>0.7206</td>
    <td>0.6616</td>
    <td>
      PhoBert,XML-RoBERTa<br/>
      underthesea
    </td>
    <td><a href="https://drive.google.com/file/d/1ckKBS8T55oCWS3JnwWsNdzKPBsclDDHb/view">Nguyen et al. VLSP'20</a></td>
    <td></td>
  </tr>
  <tr>
    <td>RELEX2020_MinhPQN</td>
    <td>0.6756</td>
    <td>0.6342</td>
    <td>
      NLPHust/vibert4news,FPT/vibert<br/>
      VnCoreNLP
    </td>
    <td><a href="https://drive.google.com/file/d/1uzTIuxjsCw3TmNAdE7T6v6XB2zurkpTF/view">Pham VLSP'20</a></td>
    <td></td>
  </tr>
  <tr>
    <td>RELEX2020_SunBear</td>
    <td>0.6648</td>
    <td>0.6209</td>
    <td>
      join training NER and RE<br/>
      PhoBERT, VnCoreNLP
    </td>
    <td><a href="https://drive.google.com/file/d/1WlMnKJkThFkq1lOFqz_3dJzKF8Vf_wP2/view?usp=sharing">Pham et al. VLSP'20</a></td>
    <td></td>
  </tr>
</table>

## Miscellaneous

:scroll: **Papers**

* [Nguyen et al. NICS'18. Relation Extraction in Vietnamese Text via Piecewise Convolution Neural Network with Word-Level Attention](https://drive.google.com/file/d/1To2pL-UAEiKWNFYDJzHgO7ls20lh4_J0/view?usp=sharing)
* [Truong et al. SoICT'17](https://arxiv.org/pdf/1801.07804.pdf)
* [Sam et al. 2014](http://vjs.ac.vn/index.php/jcc/article/view/2566)
* [Sam et al. SoICT'11](https://www.researchgate.net/publication/221633643_Semi-supervised_learning_for_relation_extraction_in_Vietnamese_text)

:file_folder: **Open sources**

* [vnoie (2017)](https://bitbucket.org/vnoie/source/overview)`java`
