**Supervised Machine Learning - Classification models** 


Three models are being tested: Decision Tree, kNN, Neural Network, for predicting whether passanger onboard of Titanic survived or not. The dataset used is Titanic and the data inside it is about the passengers of the Titanic ship. It is in 2201 rows and 4 columns. It contains 4 attributes:

• Survived – yes/no
• Class – First/Second/Third/Crew
• Age – Adult/Child
• Sex – Male/Female


<p align="center">
<img align="center" src="https://github.com/PmnAngelov/data-mining/blob/main/Classification%20models%20-%20Titanic/imgs/c4.PNG"/>
</p>

There are a total of 2,201 passengers and 95.5% of them are adults, or more precisely 109 (4.95%) are children, and the remaining 2,092 are adults. The passengers consist of 78.65% (1731) men and 21.35% (470) women. The children on board are divided into 45 (41.28%) girls and 64 (58.72%) boys. Of them, 57 (52.29%) survived, and the remaining 52 (47.71%) died.

The ship's crew represents 40.32% of all people or 885 people. Of these, 862 (97.40%) are male and the remaining 23 (2.60%) are female. 673 people (76.05%) of the crew did not survive and accordingly, the remaining 212 (23.95%) managed to survive.

Of all the people on board, 1490 (67.70%) died and only 711 (32.30%) people managed to save themselves. Of the survivors, 367 (51.62%) were male and 344 (48.38%) were female. This information is visible after adding Data Info and Data Table and Distributions to visualize the data.

First, the following setting are applied, (Sampling)–stratified random sampling (training set size 75%):

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/data-mining/blob/main/Classification%20models%20-%20Titanic/imgs/c5.PNG"/>
</p>

The ROC analysis displays the quality of the 3 classifiers:

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/data-mining/blob/main/Classification%20models%20-%20Titanic/imgs/c6.PNG"/>
</p>

A look at the Confusion Matrix shows that the Tree is the most accurate - getting it wrong 1191 times and guessing correctly 4319 times out of a total of 5510 attempts to predict whether the passanger survives. The neural network, similarly, was wrong 1205 times and guessed 4305 times accordingly. kNN - was wrong 1605 times and guessed 3905.

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/data-mining/blob/main/Classification%20models%20-%20Titanic/imgs/c6.5.PNG"/>
</p>



