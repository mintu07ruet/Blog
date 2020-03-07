---
title: "Real or Not? NLP with Disaster Tweets-CSE 5338 Data Mining Project Phase-02 "
date: 2020-03-03 11:33:00 +0800
categories: [Blogging, Demo]
tags: [typography]
---

The purpose of this project was classification of Disater tweets to identify weather it is Disaster or Not Disaster related. This study has used BERT model which is the Neuaral Network techniques to decode the texts. This study has scored 0.81901 in the kaggle Leaderboard with 969 current position. 

# Import necesssray library for the analysis and model
***


<h2 data-toc-skip>H2</h2>

<h3 data-toc-skip>H3</h3>

#### H4

***

## Paragraph

The purpose of this project was classification of Disater tweets to identify weather it is Disaster or Not Disaster related. This study has used BERT model which is the Neuaral Network techniques to decode the texts. This study has scored 0.81901 in the kaggle Leaderboard with 969 current position

## Block Quote

> This line to shows the Block Quote.

## Tables

|Company|Contact|Country|
|:---|:--|---:|
|Alfreds Futterkiste | Maria Anders | Germany
|Island Trading | Helen Bennett | UK
|Magazzini Alimentari Riuniti | Giovanni Rovelli | Italy

## Link

[https://www.kaggle.com/mintumiah/nlp-disaster-or-not-disaster](https://www.kaggle.com/mintumiah/nlp-disaster-or-not-disaster)


## Footnote

Click the hook will locate the footnote[^footnote].


## Image

![Desktop View]({{ "/assets/img/sample/mockup.png" | relative_url }})


## Inline code

This is an example of `Inline Code`.


## Code Snippet

### Common

```
This is a common code snippet, without syntax highlight and line number.
```

### Specific Languages

# Import necesssray library for the analysis and model

```console
import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)
import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))
import matplotlib.pyplot as plt
import seaborn as sns
from nltk.corpus import stopwords
import re
import string
import pandas_profiling
import random
import string
import tensorflow as tf
from tensorflow.keras.layers import Dense, Input
from tensorflow.keras.optimizers import Adam
from tensorflow.keras.models import Model
from tensorflow.keras.callbacks import ModelCheckpoint
import tensorflow_hub as hub
```

#Load 3 different files-train, test and submission files
```console
train = pd.read_csv("/kaggle/input/nlp-getting-started/train.csv")
test = pd.read_csv("/kaggle/input/nlp-getting-started/test.csv")
sample_submission = pd.read_csv("/kaggle/input/nlp-getting-started/sample_submission.csv")
print (train.shape, test.shape, sample_submission.shape)
```
# See the data attributes 

```terminal
train.head()
```

#### Ruby

```ruby
def sum_eq_n?(arr, n)
  return true if arr.empty? && n == 0
  arr.product(arr).reject { |a,b| a == b }.any? { |a,b| a + b == n }
end
```

#### Shell

```shell
if [ $? -ne 0 ]; then
    echo "The command was not successful.";
    #do the needful / exit
fi;
```

#### Liquid

{% raw %}
```liquid
{% if product.title contains 'Pack' %}
  This product's title contains the word Pack.
{% endif %}
```
{% endraw %}

#### HTML

```html
<div class="sidenav">
  <a href="#contact">Contact</a>
  <button class="dropdown-btn">Dropdown
    <i class="fa fa-caret-down"></i>
  </button>
  <div class="dropdown-container">
    <a href="#">Link 1</a>
    <a href="#">Link 2</a>
    <a href="#">Link 3</a>
  </div>
  <a href="#contact">Search</a>
</div>
```

**Horizontal Scrolling**

```html
<div class="panel-group">
  <div class="panel panel-default">
    <div class="panel-heading" id="{{ category_name }}">
      <i class="far fa-folder"></i>
      <p>This is a very long long long long long long long long long long long long long long long long long long long long long line.</p>
      </a>
    </div>
  </div>
</div>
```

Refernces
***https://www.kaggle.com/holfyuen/basic-nlp-on-disaster-tweets

**https://www.kaggle.com/nkoprowicz/a-very-simple-fine-tuned-bert-model

**https://www.kaggle.com/ratan123/in-depth-guide-to-google-s-bert

**https://www.kaggle.com/ratan123/in-depth-guide-to-google-s-bert?fbclid=IwAR3m3AL4vajTMr-IY2kIPPS eFJJw7Lc9UqJ_nb5cmW5buliW5_qJlfpxgg
## Reverse Footnote

[^footnote]: The footnote source.
