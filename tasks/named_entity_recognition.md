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

### Leaderboard

<table>
  <tr>
    <th>Model</th>
    <th>F1</th>
    <th>Paper/Source</th>
    <th>Code</th>
  </tr>
  <tr>
    <td>CRF</td>
    <td>74.70</td>
    <td><a href="https://arxiv.org/pdf/1803.08463.pdf">Pham et al. VLSP'18</a></td>
    <td></td>
  </tr>
  <tr>
    <td>Bi-LSTM</td>
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

* :scroll: [VLSP 2016 Shared Task: Named Entity Recognition paper](https://drive.google.com/file/d/18FuXxRM0slTeReQUCOj8IiToB5eqVQCT/view?usp=sharing)

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
    <td>VnCoreNLP</td>
    <td>88.55</td>
    <td><a href="http://aclweb.org/anthology/N18-5012">Nguyen et al. NAACL'18</a></td>
    <td><a href="https://github.com/vncorenlp/VnCoreNLP">Official</a></td>
  </tr>
  <tr>
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
    <td>Token reguilar expression + Bidirectional Inference</td>
    <td>88.78</td>
    <td><a href="https://drive.google.com/file/d/1yepeBjeOCWmwMSrGwP-ewhxQBmPpyP0p/view?usp=sharing">Le et al. VLSP'16</a></td>
    <td></td>
  </tr>
  <tr>
    <td>CRF</td>
    <td>84.08</td>
    <td><a href="https://drive.google.com/file/d/1n4JMtHLsIgaeiAtjPncg64BVumykbHsL/view?usp=sharing">Nguyen et al. VLSP'16</a></td>
    <td></td>
  </tr>
  <tr>
    <td>Stack LSTM</td>
    <td>83.80</td>
    <td><a href="https://drive.google.com/file/d/16M0Ry_dHFOY5njVhqy4NV0G2-bfTq6Qt/view?usp=sharing">Nguyen et al. VLSP'16</a></td>
    <td></td>
  </tr>
  <tr>
    <td>Bi-LSTM CRF</td>
    <td>83.25</td>
    <td><a href="https://drive.google.com/file/d/16M0Ry_dHFOY5njVhqy4NV0G2-bfTq6Qt/view?usp=sharing">Nguyen et al. VLSP'16</a></td>
    <td></td>
  </tr>
  <tr>
    <td>CRF</td>
    <td>78.38</td>
    <td><a href="https://drive.google.com/file/d/1vg9Bvu6HgiO7KDiKKAPZz9dL3VmlON1I/view?usp=sharing">Le et al. VLSP'16</a></td>
    <td></td>
  </tr>
</table>

