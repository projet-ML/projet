# PROJET ML

![picture](https://miro.medium.com/max/1400/1*hsyCZOYoGrX6BJsj4Lgrhg.png)

Nous faisons l'analyse et la comparaison entre plusieurs algorithmes travaillant sur le problème de detection de spam dans les messages. 
Pour commencer, une analyse de la data s'avère nécessaire. 

Notre jeu d’apprentissage sera une collection de mails. Pour chacun d’eux, on indiquera s’il s’agit d’un SPAM ou non.

Le fichcier de data contient 5572 lignes et un message par ligne. Chaque ligne est composée de 2 colonnes : Label (spam ou ham) et Message (le message en clair).

# Notre Training Set est composé de :

747 mails Spam

4825 mails Non spam (Ham)

# Les méthodes réalisées : 

- Naive Bayes spam filtering
- K-Nearest Neighbors algorithm
- Decision Tree learning
- Support Vector Machine (SVM)
- Random Forest
- Logistic Regression
- Neural Network
![picture](https://imagizer.imageshack.com/img924/7788/WNsWRB.png)

Nous avons aussi réalisé la fonction d’efficacité du récepteur, plus fréquemment désignée sous le terme « courbe ROC » (de l’anglais receiver operating characteristic). Elle permet la détermination et la comparaison des performances diagnostiques de plusieurs tests à l'aide de l'évaluation des aires sous la courbe. 

# N.B : 
Le test de la méthode Neural Natwork se fait vers la fin. c'est une implementation simple de l'algorithme Neural Network faite par Python et Numpy. Le but de cette partie était de comprendre l'architecture complète d'un réseau de neurones et de décomposer visuellement ce qui se passe pendant le training pour reconnaître les spams / non spams.
