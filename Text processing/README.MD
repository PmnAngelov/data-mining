Using the Import Document statement, the folder USA Party Platforms 2016 is loaded, containing 2 subfolders - Democratic and Republican. The data are text files about speeches by the Democratic and Republican political parties during the USA 2016 election.

A Preprocess Text statement is added to process the text data. Text is converted to lowercase, tokenized, and stopwords and punctuation are filtered out. Finally, bigrams are generated.

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/data-mining/blob/main/Text%20processing/imgs/c1.PNG" />
</p>

Two Corpus Viewers are added, one for visualizing the text data of the Democratic Party (Corpus Viewer) and one for those of the Republican Party (Corpus Viewer(1)). They are connected to the Word Cloud tools, to visualize the most common bigrams, and to the Bag of Words to calculate the Term Frequency (COUNT), which is connected to the Data Table.

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/data-mining/blob/main/Text%20processing/imgs/c2.PNG" />
</p>

The Word Cloud depicting the most common bigrams in Democratic Party text shows their most frequently used bigrams include:

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/data-mining/blob/main/Text%20processing/imgs/c3.PNG" />
</p>

This can lead to the conclusion that in the speeches made by the Democratic Party, the most frequent mentions are about democratic values, the health care system, Donald Trump and issues related to global warming and clean energy.


On the other hand, the Word Cloud (1) depicting the most common bigrams in the Republican Party texts, shows their most frequently used bigrams.

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/data-mining/blob/main/Text%20processing/imgs/c4.PNG" />
</p>

This may lead to the conclusion that in the speeches given by the Republican Party, the administration of the day, the federal government, national security and the American people are most often talked about.

When we search for the bigram "Donald Trump" in both documents, it turns out that it is only present in the text data of the Democratic Party and is mentioned 31 times, in connection with attacks against Donald Trump.

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/data-mining/blob/main/Text%20processing/imgs/c6.PNG" />
</p>










