# TP 1 : Prétraitement du texte — De la donnée brute au texte exploitable

## 📌 Description du projet

Ce TP a pour objectif de découvrir les bases du traitement automatique du langage naturel (NLP) avec Python. Il permet d'apprendre à nettoyer un texte, à le découper en mots, à supprimer les mots vides et à appliquer la lemmatisation.

Les exercices utilisent les bibliothèques NLTK, spaCy et Scikit-learn.

## 🎯 Objectifs

- Installer et importer les bibliothèques nécessaires.
- Nettoyer et normaliser un texte.
- Réaliser la tokenisation.
- Identifier et supprimer les stopwords.
- Appliquer la lemmatisation.
- Comprendre les étapes de préparation du texte avant son analyse.

## 🛠️ Technologies utilisées

- Python
- NLTK
- spaCy
- Scikit-learn
- Jupyter Notebook

## 📚 Partie 1 : Préparation de l'environnement

**Question 1 : Quelle est la commande permettant d'installer une bibliothèque avec pip ?**

La commande utilisée est `pip install nom_bibliotheque`.

Exemple :

```bash
pip install nltk
```

**Question 2 : Quelle est la différence entre NLTK et spaCy ?**

NLTK est une bibliothèque adaptée à l'apprentissage et à l'expérimentation des techniques de traitement du langage naturel. spaCy est conçue pour réaliser efficacement des tâches NLP dans des applications pratiques, comme l'analyse grammaticale et la reconnaissance des entités.


## 🧹 Partie 2 : Nettoyage du texte

Cette partie consiste à convertir le texte en minuscules et à supprimer la ponctuation.

**Question 1 : Pourquoi est-il important de mettre le texte en minuscules ?**

Cela permet de traiter un même mot de manière uniforme, même lorsqu'il apparaît avec des majuscules. Par exemple, `Python` et `python` sont considérés comme identiques.

**Question 2 : Donnez un exemple de résultat avant et après nettoyage.**
<img width="1366" height="768" alt="Capture d&#39;écran 2026-10-13 221058" src="https://github.com/user-attachments/assets/5c21dc69-3ca2-4778-b247-db7a94846fa8" />

Avant :

```text
Hello World! I LOVE Python.
```

Après :

```text
hello world i love python



## 🔤 Partie 3 : Tokenisation et stopwords

La tokenisation consiste à découper un texte en mots. Les stopwords sont des mots fréquents qui peuvent apporter peu d'informations pour certaines analyses.

**Question 1 : Que représentent les stopwords ?**

Les stopwords sont des mots fréquents comme `the`, `is` et `and` en anglais. Ils peuvent être supprimés pour faciliter certaines analyses textuelles, selon le contexte.

**Question 2 : Quelle proportion du texte original est supprimée après leur retrait ?**

Dans notre exemple, nous avons 10 tokens au départ et 5 tokens après le filtrage.

Calcul :

```text
Proportion supprimée = ((10 - 5) / 10) × 100 = 50 %
```

La proportion supprimée est donc de 50 % dans cet exemple.
<img width="1366" height="768" alt="Capture d&#39;écran 2026-10-13 221117" src="https://github.com/user-attachments/assets/a271080f-d31d-419e-a97b-3742ad44c490" />




## 📖 Partie 4 : Lemmatisation

La lemmatisation permet de ramener un mot à sa forme de base. Par exemple, `cars` devient `car` et `studies` devient `study`.

**Question 1 : Quelle est la différence entre stemming et lemmatisation ?**

Le stemming réduit un mot en supprimant certaines parties de celui-ci, sans garantir l'obtention d'un mot existant. La lemmatisation recherche sa forme de base en tenant compte des règles linguistiques.

**Question 2 : Pourquoi cette étape est-elle importante avant l'analyse sémantique ?**

Elle permet de regrouper différentes formes d'un même mot et de réduire la diversité du vocabulaire, ce qui peut faciliter l'analyse du texte.
<img width="1366" height="768" alt="Capture d&#39;écran 2026-10-13 221140" src="https://github.com/user-attachments/assets/96e227e3-d087-4813-9111-d06e36ed36bf" />


## ✅ Conclusion

Ce TP m'a permis de découvrir les principales étapes du prétraitement du texte en Python. J'ai appris à nettoyer un texte, à effectuer la tokenisation, à supprimer les stopwords et à appliquer la lemmatisation. Ces techniques constituent une base importante pour les projets de traitement automatique du langage naturel et d'intelligence artificielle.

## 👨‍🎓 Auteur

**Hamza Id El Baz**

Projet réalisé dans le cadre du cours *Introduction à l'Intelligence Artificielle* sur la plateforme MLIAEdu.
