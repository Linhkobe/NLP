# NLP - Natrual Language processing - Python
1) Le but de ce projet est de prédire la poralité (modèle régession logistique a été utilisé) des commentaires de client
   sur un restaurant en utilisant le traitement du langage naturel (NLP en anglais). Il y a 4 polarités possibles :
   + Neutral
   + Positive
   + Négative
   + Conflit
2) Les données utilisées dans le projet :
   + Restaurants_Test_Gold.xml : le fichier concernant la/les catégorie(s), les termes principals, la polarité des phrases.
   + Restaurants_Train.xml : pareil comme le fichier "Restaurants_Test_Gold.xml". 
   + Restaurants_Test_NoLabels.xml : le fichier brut à traiter et à mettre en oeuvre la prédiction du modèle entraîné pour tester.
   + df_test_resto.csv : le fichier de données (le traitement à partir du fichier "Restaurants_Test_Gold.xml") pour tester le modèle sur ses prédictions. 
   + df_train_resto.csv : le fichier de données d'entraînement (le traitement à partir du fichier "Restaurants_Train.xml"))pour entraîner le modèle.
3) Package supplémentaire utilisé :
   "en_core_web_sm-3.2.0.tar.gz" est un package pour Spacy, une bibliothèque Python pour le traitement du langage naturel. Il contient un petit modèle de langue anglaise formé sur du      texte Web, avec des règles de tokenisation, des modèles d'analyse, de reconnaissance d'entités nommées et des vecteurs de mots. Vous pouvez l'utiliser pour diverses tâches telles       que l'analyse des parties du discours, la reconnaissance d'entités nommées et l'analyse des dépendances.
   lien : https://github.com/explosion/spacy-models  
