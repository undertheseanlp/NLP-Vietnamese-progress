# Representation

## Pre-trained Transformer Models

<table>
  <tr>
    <th>Model</td>
    <th>Descriptions</th>
    <th>References</td>
    <th>Link</td>
  </tr>
  <tr>
    <td>fpt-corp/viBERT</td>
    <td>
      Data: 10GB <br/>
      Domain: News <br/>
      Token: Subword <br/>
      Vocab size: 38168
    </td>
    <td><a href="https://arxiv.org/pdf/2006.15994.pdf">Bui et al. PACLIC'20</a></td>
    <td>
      🤗<a href="https://huggingface.co/FPTAI/vibert-base-cased"><code>FPTAI/vibert-base-cased</code></a><br/>
      <a href="https://github.com/fpt-corp/viBERT">[github]</a>
    </td>
  </tr>
  <tr>
    <td>fpt-corp/vELECTRA</td>
    <td>Data: </td>
    <td><a href="https://arxiv.org/pdf/2006.15994.pdf">Bui et al. PACLIC'20</a></td>
    <td>
      🤗<a href="https://huggingface.co/FPTAI/velectra-base-discriminator-cased"><code>FPTAI/velectra-base-discriminator-cased</code></a><br/>
      <a href="https://github.com/fpt-corp/viBERT">[github]</a>
    </td>
  </tr>
  <tr>
    <td>VinAIResearch/PhoBERT</td>
    <td>Data: </td>
    <td><a href="https://arxiv.org/pdf/2003.00744.pdf">Nguyen et al. EMNLP Findings'20</a></td>
    <td>
      🤗<a href="https://huggingface.co/vinai/phobert-base"><code>vinai/phobert-base</code></a><br/>
      🤗<a href="https://huggingface.co/vinai/phobert-large"><code>vinai/phobert-large</code></a><br/>
      <a href="https://github.com/VinAIResearch/PhoBERT">[github]</a>
    </td>
  </tr>
  <tr>
    <td>nguyenvulebinh/vietnamese-electra</td>
    <td>Data: </td>
    <td></td>
    <td>
      <a href="https://github.com/nguyenvulebinh/vietnamese-electra">[github]</a>
    </td>
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
