# Applied Data Science @ Columbia
## Fall 2019
## Project 1: A "data story" on the songs of our times

<img src="figs/title.png" width="500">

### [Project Description](doc/)
This is the first and only *individual* (as opposed to *team*) this semester. 

Term: Fall 2019

+ Projec title: Project 1, Applied Data Science
+ This project is conducted by Tushar Ponkshe

+ The objective of this project was to analyze trends in music lyrics over 4 decades of collected lyrics data. The entire dataset - "lyrics.csv" is a filtered corpus of 380,000+ song lyrics from from MetroLyrics. You can read more about it on [Kaggle](https://www.kaggle.com/gyani95/380000-lyrics-from-metrolyrics). For the purpose of this report I have used a cleaned version of lyrics data provided to us in starter code.

The starter code in Text_Processing.Rmd cleans the original dataset by removing stop words and performing various preprocessing tasks such as converting all the lyrics to the lower case, removing punctuation, numbers, empty words, extra white spaces, and stemming. The cleaned version of data is then saved as a RData file. 

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
