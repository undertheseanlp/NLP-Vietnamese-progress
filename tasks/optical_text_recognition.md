# Optical Text Recognition

## VNOnDB

* :link: [ICFHR2018 Competition on Vietnamese Online Handwritten Text Recognition using VNOnDB](https://sites.google.com/view/icfhr2018-vohtr-vnondb)
* :file_folder: [ICFHR2018 Competition on Vietnamese Online Handwritten Text Recognition Database (HANDS-VNOnDB2018)](http://tc11.cvc.uab.es/datasets/HANDS-VNOnDB2018_1/)

ICFHR2018 Competition on Vietnamese Online Handwritten Text Recognition using HANDS-VNOnDB (VNOnDB in short) database is the first attempt to bring together researchers working on handwritten text recognition and provide them a proper benchmark to compare their approaches on the tasks of transcribing Vietnamese online handwritten text. The goal of this competition is to encourage the studies on Vietnamese online handwritten text recognition and analyze the different approaches of the participants. 

This competition (VNOnDB2018) is organized in the framework of the ICFHR 2018 competitions by Nakagawa Laboratory of Tokyo University of Agriculture and Technology, Department of Computer and Information Sciences.

In order to share the ideas and systems for other researchers, we encourage all participants to present their approaches in a conference paper at ICFHR 2018 and also publish their source codes after the competition results have been announced. 

**Task 1: Word level (VNOnDB-Word)**

In task 1, the segmented handwritten words and their ground truth are provided. We verified and eliminated the words which contain the long-distance delayed strokes such as the delayed strokes written after finished other words, or even a sentence. Thus, task 1 is used to evaluate the performance of recognizers with short-distance delayed strokes since in this task, there are only short-distance delayed strokes.

**Task 2: Text line level (VNOnDB-Line)**

In task 2, the text lines and their ground truth are provided. In this task, there is both long-distance, and short-distance delayed strokes which is appropriate for evaluating the robustness of systems with different kinds of delayed strokes.

**Task 3: Paragraph level (VNOnDB-Paragraph)**

In task 3, there are the handwritten text, which usually contains multiple text lines, and the paragraph level ground truth, which is a long sequence of characters. Task 3 is suitable for measuring the limitation of recognition system on the long sequences with many delayed strokes.

### Leaderboard

**Task 1: Word level (VNOnDB-Word)**

<table>
  <tr>
    <th rowspan="2"></th>
    <th colspan="2">Public test set</th>
    <th colspan="2">Secret test set</th>
    <th rowspan="2">Paper/Source</th>
    <th rowspan="2">Code</th>
  </tr>
  <tr>
    <td>CER</td>
    <td>WER</td>
    <td>CER</td>
    <td>WER</td>
  </tr>
  <tr>
    <td>MyScriptTask1<br>Segmentation+Feedforward Neural Network (FNN) &amp; BLSTM+CTC<br>Syllable-based unigram VTB + others<br></td>
    <td>2.91</td>
    <td>6.46</td>
    <td>6.01</td>
    <td>12.66</td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>IVTOVTask1<br>2 BLSTM layers + CTC/Dictionary/VTB<br></td>
    <td>2.92</td>
    <td>6.47</td>
    <td>7.31</td>
    <td>15.38</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>GoogleTask1<br>Multi LSTM layers + CTC/Character &amp; word n-gram<br></td>
    <td>6.09</td>
    <td>13.18</td>
    <td>9.81</td>
    <td>20.45</td>
    <td></td>
    <td></td>
  </tr>
</table>

**Task 2: Text line level (VNOnDB-Line)**

<table>
  <tr>
    <th rowspan="2"></th>
    <th colspan="2">Public test set</th>
    <th colspan="2">Secret test set</th>
    <th rowspan="2">Paper/Source</th>
    <th rowspan="2">Code</th>
  </tr>
  <tr>
    <td>CER</td>
    <td>WER</td>
    <td>CER</td>
    <td>WER</td>
  </tr>
   <tr>
    <td>MyScriptTask2_1<br>Segmentation+ FNN &amp; BLSTM+CTC<br>Syllable-based trigram/VTB<br></td>
    <td>1.02</td>
    <td>2.02</td>
    <td>1.02</td>
    <td>3.39</td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>MyScriptTask2_2<br>Segmentation+FNN &amp; BLSTM+CTC<br><br>Syllable-based trigram/VTB + others<br></td>
    <td>1.57</td>
    <td>4.02</td>
    <td>1.71</td>
    <td>5.16</td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>IVTOVTask2<br>2 BLSTM layers + CTC/Dictionary/VTB<br></td>
    <td>3.24</td>
    <td>14.11</td>
    <td>5.65</td>
    <td>21.07</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>GoogleTask2<br>Multi LSTM layers + CTC<br><br>Character &amp; word n-gram/Other<br></td>
    <td>6.86</td>
    <td>19</td>
    <td>10.26</td>
    <td>27.05</td>
    <td></td>
    <td></td>
  </tr>
</table>

**Task 3: Paragraph level (VNOnDB-Paragraph)**

<table>
  <tr>
    <th rowspan="2"></th>
    <th colspan="2">Public test set</th>
    <th colspan="2">Secret test set</th>
    <th rowspan="2">Paper/Source</th>
    <th rowspan="2">Code</th>
  </tr>
  <tr>
    <td>CER</td>
    <td>WER</td>
    <td>CER</td>
    <td>WER</td>
  </tr>
   <tr>
    <td>MyScriptTask3_1<br>Segmentation+FNN &amp; BLSTM+CTC<br><br>word-based trigram/VTB<br></td>
    <td>0.78</td>
    <td>1.38</td>
    <td>1.92</td>
    <td>5.81</td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>MyScriptTask3_2<br>Segmentation+FNN &amp; BLSTM+CTC<br>syllable-based trigram/VTB + others<br></td>
    <td>1.32</td>
    <td>3.4</td>
    <td>2.62</td>
    <td>7.74</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>MyScritpTask3_3<br>Segmentation+FNN &amp; BLSTM+CTC with Post-processing for Paragraph<br>word-based trigram/VTB<br></td>
    <td>0.4</td>
    <td>1.05</td>
    <td>3.69</td>
    <td>7.84</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>IVTOVTask3<br>2 BLSTM layers + CTC/VTB/Dictionary<br></td>
    <td>3.75</td>
    <td>16.09</td>
    <td>7.31</td>
    <td>24.07</td>
    <td></td>
    <td></td>
  </tr>
</table>

## Cinnamon AI Marathon: Handwriting OCR for Vietnamese Address

* :link: [Cinnamon AI Marathon: Handwriting OCR for Vietnamese Address](https://drive.google.com/drive/folders/1Qa2YA6w6V5MaNV-qxqhsHHoYFRK5JB39)

Given an image of a handwritten line, participants are required to create an OCR model to transcribe the image into text.

### Leaderboard

TBD

## Miscellaneous

:file_folder: **Open sources**

* [miendinh/VietnameseOCR (2018)](https://github.com/miendinh/VietnameseOCR) `python,tensorflow`