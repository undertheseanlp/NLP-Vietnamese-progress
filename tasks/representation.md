# Representation

## Pre-trained Transformer Models

<table>
  <tr>
    <th>Model</th>
    <th>References</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>fpt-corp/viBERT</td>
    <td><a href="https://arxiv.org/pdf/2006.15994.pdf">Bui et al. PACLIC'20</a></td>
    <td>
      🤗<a href="https://huggingface.co/FPTAI/vibert-base-cased"><code>FPTAI/vibert-base-cased</code></a><br/>
      💻<a href="https://github.com/fpt-corp/viBERT"><code>fpt-corp/viBERT</code></a>
    </td>
  </tr>
  <tr>
    <td>fpt-corp/vELECTRA</td>
    <td><a href="https://arxiv.org/pdf/2006.15994.pdf">Bui et al. PACLIC'20</a></td>
    <td>
      🤗<a href="https://huggingface.co/FPTAI/velectra-base-discriminator-cased"><code>FPTAI/velectra-base-discriminator-cased</code></a><br/>
      💻<a href="https://github.com/fpt-corp/viBERT"><code>fpt-corp/viBERT</code></a>
    </td>
  </tr>
  <tr>
    <td>VinAIResearch/PhoBERT</td>
    <td><a href="https://arxiv.org/pdf/2003.00744.pdf">Nguyen et al. EMNLP Findings'20</a></td>
    <td>
      🤗<a href="https://huggingface.co/vinai/phobert-base"><code>vinai/phobert-base</code></a><br/>
      🤗<a href="https://huggingface.co/vinai/phobert-large"><code>vinai/phobert-large</code></a><br/>
      💻<a href="https://github.com/VinAIResearch/PhoBERT"><code>VinAIResearch/PhoBERT</code></a>
    </td>
  </tr>
   <tr>
    <td>NlpHUST/vibert4news</td>
    <td>
    </td>
    <td>
      🤗<a href="https://huggingface.co/NlpHUST/vibert4news-base-cased"><code>NlpHUST/vibert4news-base-cased</code></a><br/>
      💻<a href="https://github.com/bino282/bert4news"><code>bino282/bert4news</code></a>
    </td>
  </tr>
  <tr>
    <td>nguyenvulebinh/vietnamese-electra</td>
    <td></td>
    <td>
      💻<a href="https://github.com/nguyenvulebinh/vietnamese-electra"><code>nguyenvulebinh/vietnamese-electra</code></a>
    </td>
  </tr>
</table>

<b>Model Descriptions</b>

<table>
  <tr>
    <th>Model</th>
    <th>#params</th>
    <th>Data</th>
    <th>Domain</th>
    <th>Tokenization</th>
    <th>Vocab Size</th>
  </tr>
  <tr>
    <td>fpt-corp/viBERT</td>
    <td></td>
    <td>10GB</td>
    <td>News</td>
    <td>Subword</td>
    <td>38168</td>
  </tr>
  <tr>
    <td>VinAIResearch/PhoBERT</td>
    <td>
      135M (phobert-base)<br/>
      370M (phobert-large)
    </td>
    <td>20GB</td>
    <td>News</td>
    <td>Word</td>
    <td></td>
  </tr>
  <tr>
    <td>NlpHUST/vibert4news</td>
    <td></td>
    <td>20GB</td>
    <td>News</td>
    <td>Syllable</td>
    <td>62000</td>
  </tr>
</table>

## Word Vectors

* [datquocnguyen/PhoW2V](https://github.com/datquocnguyen/PhoW2V) - Pre-trained Word2Vec syllable and word embeddings for Vietnamese
* [vietnlp/etnlp](https://github.com/vietnlp/etnlp) - A toolkit to evaluate, extract, and visualize multiple embeddings
* [Kyubyong/wordvectors](https://github.com/Kyubyong/wordvectors) `resource`
* [facebookresearch/fastText](https://github.com/facebookresearch/fastText) `resource`
* [sonvx/word2vecVN](https://github.com/sonvx/word2vecVN) `resource`

## ViCon & ViSim-400

ViCon comprises pairs of synonyms and antonyms across word classes, thus offering data to distinguish between similarity and dissimilarity. ViSim-400 provides degrees of similarity across five semantic relations, as rated by human judges.

The two datasets are verified through standard co-occurrence and neural network models, showing results comparable to the respective English datasets

* :scroll: [ViCon & ViSim-400 paper (Nguyen et al. NAACL'18)](https://arxiv.org/pdf/1804.05388.pdf)
* :file_folder: [ViCon & ViSim-400 data](http://www.ims.uni-stuttgart.de/forschung/ressourcen/experiment-daten/vnese_sem_datasets.html)

## VSimLex-999

* :scroll: [VSimLex-999 paper (Bui et al. KSE'17)](https://drive.google.com/file/d/1wU09HMcrgGZhniS7pU3WGuVb1NOUTbAW/view?usp=sharing)
* :file_folder: [VSimLex-999 data](https://github.com/BuiVanTan2017/VSimLex-999)

## Miscellaneous

:scroll: **Papers**

* [Tran et al. 2016](https://www.slideshare.net/microlife/a-vietnamese-language-model-based-on-recurrent-neural-network-66865054)
