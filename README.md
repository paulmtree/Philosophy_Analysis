## Sentiment Analysis and Text Generation of Kierkegaard's Philosophy  


# Table of Contents


1. [Overview](#Overview)
2. [Motivations](#Motivations)
3. [Written Report](#Written-Report)
4. [Data Sources](#Data-Sources)
5. [Summary of Results](#Summary-of-Results)
6. [Credit](#Credit)
7. [Future Work](#Future-Work)


# Important Files
This README contains a brief overview and background of the project. If you would like to jump straight to the analysis, there are 2 files to read through with more on the way. The first is 
- Preliminary Sentiment Analysis: Importing, cleaning, and displaying sentiment data using VADER sentiment analysis.
- Text Generation (LSTM) (In Progress): Random text generation using Keras and Long Short-Term Memory (LSTM) framework. Currently using Google Colab to train model.

Future work will include text generation using transformers.


# Content Overview
Kierkegaard's 'Either/Or' explores one of human's most pondered questions, how should we live? It is an interesting book to analyze because it is composed of a narrator and the correspondences between two opposite-thinking psuedonyms of Kierkegaard, named A and B. The first part of the book is written by author A over 7 chapters, titled 'Either' and the last four chapters are written by B in response to A titled 'Or'. 

Authors A and B argue for two very different types of lifestyles. A argues for a lifestyle described by Kierkegaard as the 'aesthetic', generally living life with flexible morality and pursuing new and exciting experiences with no commitments. B on the other hand advocates for the 'ethical' life by living with set morals and pursuing lasting happiness through long-held relationships, like marriage. This project investigates this philosophical divide by examining sentiment of each chapter and comparing their sentiment statistics.


# Written Report
(In Progress)


# Data Sources


![Data Source Image.png](https://github.com/pkm29/Philosophy_Analysis/raw/master/images/Data%20Source%20Image.jpg)

Epub Book by Penguin Publishing

*Edited by*

VICTOR EREMITA

*Abridged, Translated and with an Introduction and Notes by*

ALASTAIR HANNAY


# Summary of Results

#### (In Progress)
![All Chapters Sentiment Graph.png](https://github.com/paulmtree/Philosophy_Analysis/raw/master/images/Sentiment%20Graph%20Big%20(1).jpg)

* Aesthetic chapters 2-7: A quick look at this portion of the book reveals both positive and negative sentiment, chapter 3 being largely positive and chapter 4 being very much negative. While obviously the most negative chapter of the book, it is interesting to see the sharp changes in the moving average as we start chapters 3 and 4. Perhaps the topic of the chapters is naturally characterized as negative or positive, and our VADER sentiment analysis captures this topic instead of the tone. <br><br>
* Ethical chapters 8-11: This section of the book, written by author B, seems to be more positive overall and with an interesting degree of variability, almost cyclical at times. I think the most interesting analysis however comes with reading the text, as you can pinpoint changes in sentiment with the context of the text.

![Comparing Pseudonyms.png](https://github.com/pkm29/Philosophy_Analysis/raw/master/images/box1.jpg)

![Comparing Chapters.png](https://github.com/pkm29/Philosophy_Analysis/raw/master/images/box2.jpg)

# Credit
- Penguin Publishing
- Professor Anna Söderquist 
- Professor K. Brian Söderquist


# License
See the [LICENSE](https://github.com/pkm29/Philosophy_Analysis/blob/master/LICENSE.md) file for license rights and limitations (MIT).
