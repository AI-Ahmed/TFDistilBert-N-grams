<p align='center'><h1 style='background:DeepSkyBlue;color:white'>Disaster Tweets – Deep NLP Analysis & [<img src='https://i.imgur.com/DFetacC.png' width='20px' height='30px'/>] Distributed Training DistilBert-N-grams-sst-en</h1></p>

<p align='center'>
    <img src='https://i.imgur.com/UYkdJD7.png'>
</p>

Copyright [2022] [AI Engineer: [Ahmed](https://www.kaggle.com/dsxavier/)]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

# 📖<font size='5' color='DarkViolet'>Overview</font>

Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

# 📝<font size='5' color='DarkViolet'>Acknowledgments</font>

This dataset was created by the company figure-eight and originally shared on their ‘[Data For Everyone’ website here](https://www.figure-eight.com/data-for-everyone/).

Tweet source: https://twitter.com/AnyOtherAnnaK/status/629195955506708480


# 📝<font size='5' color='DarkViolet'>Proof of Work</font>

I decided to use the **Transfer Learning** in this project and **Fine-tune** it since I believe in not to re-invent the wheels. We're going to use one of my favourite libraries; it's **Hugging Face**. It is the library – you need to use to inject your model with a pre-trained model that has trained on billions of examples.

# 📚<font size='5' color='DarkViolet'>Dictionary</font>

<table>
<thead>
  <tr>
    <th>Variables</th>
    <th>Definition</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>id</td>
    <td>a unique identifier for each tweet</td>
  </tr>
  <tr>
    <td>text</td>
    <td>the text of the tweet</td>
  </tr>
  <tr>
    <td>location</td>
    <td>the location the tweet was sent from (may be blank)</td>
  </tr>
  <tr>
    <td>keyword</td>
    <td>a particular keyword from the tweet (may be blank)</td>
  </tr>
  <tr>
    <td>target</td>
    <td>in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)</td>
  </tr>
</tbody>
</table>
