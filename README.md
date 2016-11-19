# Project: Words 4 Music

### [Project Description](doc/Project4_desc.md)

Term: Fall 2016

+ [Data link](https://courseworks2.columbia.edu/courses/11849/files/folder/Project_Files?preview=763391)-(**courseworks login required**)

+ [Data description](doc/readme.html)

+ Contributor's name: __Yinxiang Gao, Guanzhong You__

+ Projec title: __Music and Lyrics__

+ Project summary: In this project we try to predict the occurance of specified words in lyrics given the music features of a song.

## Instruction

### 1. Exploration of data

#### a. Ideas
* Sound features: rhythm, pitch,  timbre, …
* Lyrics:  I, the, you, to, and, …
* There is no apparent relationship between sound features and lyrics.
* We need something in between that connects them. It Could be __lyrics topics__.

#### b. Topic modeling
* Ran latent Dirichlet allocation (LDA) with number of topics equals 20.
* The topics are sensitive to languages.
![image](figs/topicmodel.png)
* We can ignore non-English songs when modeling, in order to reduce complexity.

#### c. Association
* A quick association rule mining on artist tags.
    * Achieved a predictive rank sum of 0.38
    * Worse than baseline model
    * Details under lib/try1_ARM_on_Tags/


### 2. Feature engineering


### 3. Neural network



### 4. Evaluation





Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
