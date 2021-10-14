# Sentiment Analysis

## UIT-ViSFD: A Vietnamese Smartphone Feedback Dataset for Aspect-Based Sentiment Analysis

UIT-ViSFD consists of 11,122 human-annotated comments for mobile e-commerce, which is freely available for research purposes: 

* :scroll: [SA2SL: From Aspect-Based Sentiment Analysis to Social Listening System for Business Intelligence](https://link.springer.com/chapter/10.1007/978-3-030-82147-0_53)
* :link: [Vietnamese Smartphone Feedback Dataset](https://github.com/LuongPhan/UIT-ViSFD)


## UIT ABSA Datasets

* :scroll: [Two New Large Corpora for Vietnamese Aspect-based Sentiment Analysis at Sentence Level](https://dl.acm.org/doi/abs/10.1145/3446678)

**Hotel Dataset**: 7180 reviews (train), 795 reviews (development), 2030 reviews (test)

## AIVIVN 2019: Sentiment Analysis Challenge

* :link: [AIVIVN 2019: Sentiment Analysis Challenge 2019  website](https://www.aivivn.com/contests/1)

The data contains user's reviews following two categories: "positive" and "negative"

27068 sentences

* Train: 16087 sentences, Test: 10981 sentences (public: 5454 sentences, private: 5527 sentences)
* Labels: 0 (positive), 1 (negative)

### Leaderboard

Score: F1 score of negative labels

<table>
  <tr>
    <th rowspan="2">Author</th>
    <th rowspan="2">Model</th>
    <th colspan="2">Score</th>
    <th rowspan="2">Paper/Source</th>
    <th rowspan="2">Code</th>
  </tr>
  <tr>
    <td>Public Test</td>
    <td>Private Test</td>
  </tr>
  <tr>
    <td>HoangNhat2</td>
    <td>Weighted Ensemble<br>(TextCNN, VDCNN, HARNN, SARNN)</td>
    <td>0.90087</td>
    <td>0.90012</td>
    <td>
      <a href="https://forum.machinelearningcoban.com/t/1st-place-solution-phan-loai-sac-thai-binh-luan/4504">Write up</a>
    </td>
    <td><a href="https://github.com/petrpan26/Aivivn_1">Official</a></td>
  </tr>
  <tr>
    <td>iota</td>
    <td>SVM</td>
    <td>0.8914</td>
    <td>0.89688</td>
    <td>
      <a href="https://forum.machinelearningcoban.com/t/svm-model-cho-phan-loai-sac-thai-binh-luan-3rd-place-solution/4510">Write up</a>
    </td>
    <td><a href="https://github.com/iotadesu/aivivn-sentiment-svm">Official</a></td>
  </tr>
  <tr>
    <td>Nal_AI</td>
    <td>SVM (TF-IDF)</td>
    <td>0.89545</td>
    <td>0.89574</td>
    <td>
      <a href="https://forum.machinelearningcoban.com/t/chia-se-model-sentiment-analysis-aivivn-com-top-5/4537">Write up</a>
    </td>
    <td><a href="https://github.com/swordmanager/sentiment_analysis_nal">Official</a></td>
  </tr>
  <tr>
    <td>nlpers</td>
    <td>Ensemble<br>(LinearSVC, SGD, RandomForest)</td>
    <td>0.88921</td>
    <td>0.89559</td>
    <td>
      <a href="https://forum.machinelearningcoban.com/t/mo-hinh-ensemble-don-gian-cho-phan-loai-sac-thai-binh-luan-7th-place-solution/4507">Write up</a>
    </td>
    <td><a href="https://github.com/minhpqn/aivivn_1_ensemble_7th_place">Official</a></td>
  </tr>
  <tr>
    <td>ngxbac</td>
    <td>LightGBM (TFIDF)</td>
    <td>0.867</td>
    <td></td>
    <td>
      <a href="https://forum.machinelearningcoban.com/t/feature-engineering-stacking-va-ensemble-cho-cuoc-thi-phan-loai-sac-thai-binh-luan/4298">Write up</a>
    </td>
    <td><a href="https://github.com/ngxbac/aivivn_phanloaisacthaibinhluan">Official</a></td>
  </tr>
</table>


## Vietnamese Students’ Feedback Corpus (UIT-VSFC)

* :scroll: [UIT-VSFC: Vietnamese Students’ Feedback Corpus for Sentiment Analysis](https://drive.google.com/file/d/1flr5ew6thRFw4emMx5hWlAS3gUYBp8bI/view?usp=sharing)
* :file_folder: [VSFC data](https://sites.google.com/uit.edu.vn/uit-nlp/corpora-projects)

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
    <td>Bi-LSTM - Word2Vec</td>
    <td>0.896</td>
    <td>0.92</td>
    <td><a href="https://drive.google.com/file/d/1yWKHLBC-hJ5RMUuvC2qOmEiLpViqmjAC/view?usp=sharing">Nguyen et al. NICS'18</a></td>
    <td></td>
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
    <td>CNNs</td>
    <td>0.80</td>
    <td></td>
    <td>
      <a href="https://drive.google.com/file/d/1mioRMEkPzkk9V_aDZgBaEG1vxWVd4iT1/view?usp=sharing">Dang et al. NICS'18</a>
    </td>
    <td></td>
  </tr>
  <tr>
    <td>SVM</td>
    <td>0.77</td>
    <td>0.61</td>
    <td>
      <a href="https://drive.google.com/file/d/1I2U2AinR5kfz1gjZRgfgsRQwqZEo7-od/view?usp=sharing">Dang et al. VLSP'18</a>
    </td>
    <td></td>
  </tr>
  <tr>
    <td>SVM</td>
    <td>0.54</td>
    <td>0.48</td>
    <td>
      <a href="https://drive.google.com/file/d/1-3HYFHjDv1R-H5HOIC9es1Xd-gBEtcZ9/view?usp=sharing">Nguyen et al. VLSP'18</a>
    </td>
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
    <td><a href="https://drive.google.com/file/d/1I2U2AinR5kfz1gjZRgfgsRQwqZEo7-od/view?usp=sharing">Dang et al. VLSP'18</a>
    </td>
    <td></td>
  </tr>
  <tr>
    <td>CNNs</td>
    <td>0.69</td>
    <td></td>
    <td>
      <a href="https://drive.google.com/file/d/1mioRMEkPzkk9V_aDZgBaEG1vxWVd4iT1/view?usp=sharing">Dang et al. NICS'18</a>
    </td>
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

5100 sentences for training, 1050 sentences for testing

* Train: 1700 positive, 1700 neutral, 1700 negative
* Test: 350 positive, 350 neutral, 350 negative

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
    <td>Ensemble: SVM, LR, LSTM, CNN</td>
    <td>69.71</td>
    <td><a href="https://drive.google.com/file/d/102zjgYYLphgiqR7GuoXbiJN69pXSQ0hl/view?usp=sharing">Nguyen et al. NICS'18</a></td>
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

* [Huynh et al. NICS'18. Integrating Grammatical Features into CNN Model for Emotion Classification](https://drive.google.com/file/d/167e2Oo68l0mxokw-ZLzCEPyHW0S-n300/view?usp=sharing)
* [Pham et al. 2016](http://www.indjst.org/index.php/indjst/article/viewFile/93164/69662), [Ngo et al. SoICT'16](https://www.semanticscholar.org/paper/Cross-domain-sentiment-classification-with-word-and-Bach-Hai/41f67072e52ae0b4902a4ea7f98db521a3c3dd3b), [Pham et al. KSE'16](https://ieeexplore.ieee.org/document/7758052/), [Tran et al. 2016](http://www.indjst.org/index.php/indjst/article/viewFile/97360/71787)
* [Kieu et al. KSE'10](https://drive.google.com/file/d/1rYQYyAxEOabxKa7Y6C3TDuxLHDz7OD9P/view?usp=sharing)

:file_folder: **Open sources**

* [VnEmoLex (2017)](https://zenodo.org/record/801610#.WffTwp-WakD)`data`
* [polyglot (2014-2017](http://polyglot.readthedocs.io/en/latest/Sentiment.html) `c++,java,python`
* [pyurgent (2016)](https://github.com/tiendung/pyurgent) `python,data`
* [VietSentiWordNet (2014)](https://github.com/magizbox/underthesea/wiki/VietSentiWordNet) `data`
