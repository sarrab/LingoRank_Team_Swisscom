# LingoRank_Team_Swisscom
### A ML model for English speakers that predicts the difficulty of a French written text. 
This model could be used in a recommendation system , to recommend texts (for example, recent news articles)
that are appropriate for someone’s language level. If someone is at A1 French level, it is
inappropriate to present a text at B2 level, as she won’t be able to understand it.

## Authors
* Etra Almadani
* Sarra Berich 
* Jessy Landry Inaka

## Context 
We develop this model as a project for Big-Sclae Analytics course.
It's purpose is to develop a NLP model from scratch, learn and understand the related concepts.


## Methodology
1. Define adequately our problem and think how to model it:
   - Do some search on the topic 
   - Find and read related articles 
   - Find out how to solve the problem : Classification,Regression ...
  
2. Gather Data
3. Build the model
4. Evaluate How good the model is 

## Milestone 1
### 1 Problem 
We will model the problem as a multi-label classification problem. We may consider several features (as proposed in the papers below):
- Part-of-speech (POS) tags
- Number of words
- Number of different words
- Words frequencies
- Number of different verbs forms
- Number of auxiliary verbs
- Number of main verbs
- Cognativity  
- ....
#### Existing Papers:
1. [Curto, Pedro, Nuno Mamede, and Jorge Baptista. “Automatic Text Difﬁculty Classiﬁer,” n.d., 9.]( https://www.inesc-id.pt/publications3/11043/pdf)
2. [Vlachos, Michail, and Theodoros Lappas. “Ranking German Texts by Comprehensibility for Foreign Document Retrieval,” n.d., 3. ](http://alumni.cs.ucr.edu/~mvlachos/pubs/ENIR2011.pdf)
3. [Balyan, Renu, Kathryn McCarthy, and Danielle McNamara. Comparing Machine Learning Classification Approaches for Predicting Expository Text Difficulty, 2018.](https://www.researchgate.net/publication/325302169_Comparing_Machine_Learning_Classification_Approaches_for_Predicting_Expository_Text_Difficulty)
### 2 Data
#### Data Collection
Collecting data is the basic step in the machine learning pipeline. Several techniques can be applied to do it . Among these techniques *Web crawling and scraping*.
We used a script to extract the sentences from educational websites with indicated learning levels.
For the advanced levels, we made use of novels and philosophy articles.

##### Datatsets 
“Free French Reading Practice | French Reading Exercises.” Accessed March 17, 2021. 
https://french.kwiziq.com/learn/reading#A1
“Texte En Français: Lecture et Compréhension.” Accessed March 17, 2021
https://lingua.com/fr/francais/lecture/.
TV5MONDE. Bibliothèque Numérique TV5MONDE - Adolphe. Accessed March 17, 2021. https://bibliothequenumerique.tv5monde.com/livre/26/Adolphe.
Bibliothèque Numérique TV5MONDE - La Chartreuse de Parme. Accessed March 17, 2021. https://bibliothequenumerique.tv5monde.com/livre/175/La-Chartreuse-de-Parme.




#### Annotation
3 annotations were assigned to each sentence. The first annotation was assigned automatically by the script since datasets were annotated. However it was checked manually by one of the team member. The other two were provided by the other two team members separately.
The difficulty of the sentence is calculated as the average of the 3 given annotations.
To annotate a sentence, certain criteria such as familiarity of words, conjugation time, cognativity, etc. have been taken into consideration.









