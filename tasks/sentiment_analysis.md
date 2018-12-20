# Sentiment Analysis

## Vietnamese Students’ Feedback Corpus (UIT-VSFC)

* :scroll: [UIT-VSFC: Vietnamese Students’ Feedback Corpus for Sentiment Analysis](https://drive.google.com/file/d/1flr5ew6thRFw4emMx5hWlAS3gUYBp8bI/view?usp=sharing)

Students’ feedback is a vital resource for the interdisciplinary research involving the combining of two different research fields between sentiment analysis and education. Vietnamese Students’ Feedback Corpus (UIT-VSFC) is the resource consists of over 16,000 sentences which are human-annotated with two different tasks: sentiment-based and topic-based classifications. To assess the quality of our corpus, we measure the annotator agreements and classification evaluation on the UIT-VSFC corpus.

### Leaderboard

<table>
  <tr>
    <th>Model</th>
    <th>Topic (F1)</th>
    <th>Sentiment (F1)</th>
    <th>Paper/Source</th>
    <th>Code</th>
  </tr>
  <tr>
    <td>Maximum Entropy classifier</td>
    <td>0.88</td>
    <td>0.84</td>
    <td><a href="https://drive.google.com/file/d/1flr5ew6thRFw4emMx5hWlAS3gUYBp8bI/view?usp=sharing">Nguyen et al. KSE'18</a></td>
    <td></td>
  </tr>
</table>

## VLSP 2018 Shared Task: Aspect Based Sentiment Analysis

* :scroll: [VLSP 2018 Shared Task: Aspect Based Sentiment Analysis Paper](https://drive.google.com/file/d/1C3l2n2Jicwzc0aoBLoyA5zIdczHpcy5R/view?usp=sharing)

### Leaderboard

**Restaurant Dataset**: 2961 reviews (train), 1290 reviews (development), 500 reviews (test) 

<table>
  <tr>
    <th>Model</th>
    <th>Aspect (F1)</th>
    <th>Aspect-Polarity (F1)</th>
    <th>Paper/Source</th>
    <th>Code</th>
  </tr>
  <tr>
    <td>SVM</td>
    <td>0.77</td>
    <td>0.61</td>
    <td><a href="https://drive.google.com/file/d/1I2U2AinR5kfz1gjZRgfgsRQwqZEo7-od/view?usp=sharing">Dang et al. VLSP'18</a></td>
    <td></td>
  </tr>
  <tr>
    <td>SVM</td>
    <td>0.54</td>
    <td>0.48</td>
    <td><a href="https://drive.google.com/file/d/1-3HYFHjDv1R-H5HOIC9es1Xd-gBEtcZ9/view?usp=sharing">Nguyen et al. VLSP'18</a></td>
    <td></td>
  </tr>
</table>

**Hotel Dataset**: 3000 reviews (training), 2000 reviews (development), 600 reviews (test)

<table>
  <tr>
    <th>Model</th>
    <th>Aspect (F1)</th>
    <th>Aspect-Polarity (F1)</th>
    <th>Paper/Source</th>
    <th>Code</th>
  </tr>
  <tr>
    <td>SVM</td>
    <td>0.70</td>
    <td>0.61</td>
    <td><a href="https://drive.google.com/file/d/1I2U2AinR5kfz1gjZRgfgsRQwqZEo7-od/view?usp=sharing">Dang et al. VLSP'18</a></td>
    <td></td>
  </tr>
  <tr>
    <td>SVM</td>
    <td>0.56</td>
    <td>0.53</td>
    <td><a href="https://drive.google.com/file/d/1-3HYFHjDv1R-H5HOIC9es1Xd-gBEtcZ9/view?usp=sharing">Nguyen et al. VLSP'18</a></td>
    <td></td>
  </tr>
</table>

## VLSP 2016 Shared Task: Sentiment Analysis

* :scroll: [VLSP 2016 Shared Task: Sentiment Analysis Paper](https://drive.google.com/file/d/1oAa8tcM8UACK6ibiIxL8yuz_eHM7_qBF/view?usp=sharing)

The data contains user’s reviews about technological device following three categories: ”negative”, ”positive” and ”neutral”

A review can be very complex with different sentiments on various objects. Therefore, we set some constraints on the dataset as follows:

* The dataset only contains reviews having personal opinions.
* The data are usually short comments, containing opinions on one object. There is no limitation on the number of the object's aspects mentioned in the comment.
* Label (positive/negative/neutral) is the overall sentiment of the whole review.
* The dataset contains only real data collected from social media, not artificially created by human.

### Leaderboard

<table>
  <tr>
    <th>Model</th>
    <th>F1</th>
    <th>Paper/Source</th>
    <th>Code</th>
  </tr>
  <tr>
   <td>Perceptron/SVM/Maxent</td>
    <td>80.05</td>
    <td><a href="https://drive.google.com/file/d/1ffh5tcG0e5dzjprT07GGiOHzmbUV569-/view?usp=sharing">Pham et al. VLSP'16</a></td>
    <td></td>
  </tr>
  <tr>
   <td>SVM/MLNN/LSTM</td>
    <td>71.44</td>
    <td><a href="https://drive.google.com/file/d/1s7CdShhyOhR7STQx-tJ3jOXtPWr4gBMk/view?usp=sharing">Nguyen et al. VLSP'16</a></td>
    <td></td>
  </tr>
  <tr>
    <td>Ensemble: Random forest, SVM, Naive Bayes</td>
    <td>71.22</td>
    <td><a href="https://drive.google.com/file/d/1V87Z0Jjgt47nqcN8BaDLU5TLAqzUn1pN/view?usp=sharing">Pham et al. VLSP'16</a></td>
    <td></td>
  </tr>
  <tr>
    <td>SVM</td>
    <td>67.54</td>
    <td><a href="https://drive.google.com/file/d/1ADMRNIaHUG-XFqJbSs2OmKg9DxrNGcQ3/view?usp=sharing">Ngo et al. VLSP'16</a></td>
    <td></td>
  </tr>
  <tr>
   <td>SVM/MLNN</td>
    <td>67.23</td>
    <td><a href="https://drive.google.com/file/d/15FSX0s1K_CCjlDbxHpWcnbGCQfIcV_u8/view?usp=sharing">Tran et al. VLSP'16</a></td>
    <td></td>
  </tr>
  <tr>
   <td>SVM/MLNN</td>
    <td>67.23</td>
    <td><a href="https://drive.google.com/file/d/15FSX0s1K_CCjlDbxHpWcnbGCQfIcV_u8/view?usp=sharing">Tran et al. VLSP'16</a></td>
    <td></td>
  </tr>
  <tr>
   <td>Multi-channel LSTM-CNN</td>
    <td>59.61</td>
    <td><a href="https://www.researchgate.net/publication/321259272_Multi-channel_LSTM-CNN_model_for_Vietnamese_sentiment_analysis">Vo et al. KSE'17</a></td>
    <td><a href="https://github.com/ntienhuy/MultiChannel">Official</a></td>
  </tr>
</table>

## Miscellaneous

:scroll: **Papers**

* [Pham et al. 2016](http://www.indjst.org/index.php/indjst/article/viewFile/93164/69662), [Ngo et al. SoICT'16](https://www.semanticscholar.org/paper/Cross-domain-sentiment-classification-with-word-and-Bach-Hai/41f67072e52ae0b4902a4ea7f98db521a3c3dd3b), [Pham et al. KSE'16](https://ieeexplore.ieee.org/document/7758052/), [Tran et al. 2016](http://www.indjst.org/index.php/indjst/article/viewFile/97360/71787)
* [Kieu et al. KSE'10](https://drive.google.com/file/d/1rYQYyAxEOabxKa7Y6C3TDuxLHDz7OD9P/view?usp=sharing)

:file_folder: **Open sources**

* [VnEmoLex (2017)](https://zenodo.org/record/801610#.WffTwp-WakD)`data`
* [polyglot (2014-2017](http://polyglot.readthedocs.io/en/latest/Sentiment.html) `c++,java,python`
* [pyurgent (2016)](https://github.com/tiendung/pyurgent) `python,data`
* [VietSentiWordNet (2014)](https://github.com/magizbox/underthesea/wiki/VietSentiWordNet) `data`
