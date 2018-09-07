# Speech Classification

## Zalo AI Challenge: Voice Gender Classification

* :link: [Zalo AI Challenge: Voice Gender Classification Website](https://challenge.zalo.ai/portal/voice)
* :file_folder: [Zalo AI Challenge: Voice Gender Classification Data](https://challenge.zalo.ai/portal/voice/data)

Identifying gender and regional accent from speech is essential for intelligent systems such as conversational chatbot, recommendation systems, smart home, and speech recognition. In this speech challenge, you will build a system to predict genders and regional accents of Vietnamese speakers using a diverse speech dataset.  The dataset consists of ~30K short speech signals recorded in an un-controlled environment.

### Leaderboard

<table>
  <tr>
    <th rowspan="2">Model</th>
    <th colspan="2">Score</th>
    <th rowspan="2">Paper/Source</th>
    <th rowspan="2">Code</th>
  </tr>
  <tr>
    <td>Private Test</td>
    <td>Public Test</td>
  </tr>
  <tr>
    <td>VietAI</td>
    <td>0.847</td>
    <td>0.817</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>AIS-HelloKitty</td>
    <td>0.832</td>
    <td>0.786</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>ZE</td>
    <td>0.821</td>
    <td></td>
    <td></td>
    <td><a href="https://github.com/tiepvupsu/zalo_voice">Official</a></td>
  </tr>
    <tr>
    <td>pbcquoc</td>
    <td></td>
    <td>0.678</td>
    <td></td>
    <td><a href="https://github.com/pbcquoc/voice_zaloai">Official</a></td>
  </tr>
</table>

## Zalo AI Challenge: Music Genre Classification

* :link: [Zalo AI Challenge: Voice Gender Classification Website](https://challenge.zalo.ai/portal/music)
* :file_folder: [Zalo AI Challenge: Voice Gender Classification Data](https://challenge.zalo.ai/portal/music/data)

Music Genre classification is a difficult and interesting challenge. A good classification is very helpful for smart music storage, music recommendation, music search. Despite of their usefulness, there are not many good music classifiers yet, especially for Vietnamese songs.

In this challenge, you are to build a classifier to detect the correct genre of a Vietnamese song. The 10 selected genres are: Cải Lương, Nhạc Cách Mạng, Nhạc Dân Ca - Quê Hương, Nhạc Dance, Nhạc Không Lời, Nhạc Thiếu Nhi, Nhạc Trịnh, Nhạc Trữ Tình, Rap Việt, Rock Việt.

A training set with labels is provided for your training. A test set with no category labels is also provided to test your trained classifiers against unseen data.

For each song, the classifier will need to output the most matching genre. Teams are scored and ranked by the classification accuracy on the test set.

### Leaderboard

<table>
  <tr>
    <th rowspan="2">Model</th>
    <th colspan="2">Score</th>
    <th rowspan="2">Paper/Source</th>
    <th rowspan="2">Code</th>
  </tr>
  <tr>
    <td>Private Test</td>
    <td>Public Test</td>
  </tr>
  <tr>
    <td>DungNB</td>
    <td>0.701</td>
    <td>0.815</td>
    <td></td>
    <td><a href="https://github.com/dungnb1333/music_genre_classification">Official</a></td>
  </tr>
  <tr>
    <td>Batip</td>
    <td>0.681</td>
    <td>0.810</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>toppan</td>
    <td>0.652</td>
    <td>0.802</td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>ZE</td>
    <td></td>
    <td>0.782</td>
    <td></td>
    <td><a href="https://github.com/tiepvupsu/zalo_voice">Official</a></td>
  </tr>
</table>