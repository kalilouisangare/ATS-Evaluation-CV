# ATS Resume Screener

ATS Resume Screener est une application conçue pour automatiser et optimiser le processus de recrutement. En utilisant des techniques avancées de traitement du langage naturel (NLP), cette application analyse et évalue les CVs des candidats par rapport aux exigences spécifiques d'un poste, permettant ainsi aux recruteurs de se concentrer sur les candidats les plus qualifiés.

## Fonctionnalités

- **Analyse de CV** : Extrait et analyse les informations clés des CVs, telles que l'expérience professionnelle, les compétences et la formation.
- **Évaluation Intelligente** : Compare les profils des candidats avec la description du poste pour attribuer un score de pertinence.
- **Interface Intuitive** : Une interface utilisateur simple et conviviale pour télécharger des CVs et visualiser les résultats de l'évaluation.

## Comment utiliser l'application

1.  **Configuration de la clé API** :
    *   Au premier lancement, rendez-vous dans l'onglet "Configuration".
    *   Entrez votre clé API Gemini dans le champ prévu à cet effet.
    *   Cliquez sur "Sauvegarder".
    *   Cette clé est nécessaire pour utiliser les fonctionnalités d'analyse de l'application.

2.  **Téléchargement du CV** :
    *   Allez dans l'onglet "Analyseur de CV".
    *   Utilisez le bouton de téléchargement pour soumettre un ou plusieurs CVs au format PDF ou DOCX.

3.  **Analyse et Résultats** :
    *   L'application traitera les CVs et affichera un rapport détaillé pour chaque candidat, mettant en évidence la pertinence de leur profil par rapport au poste.

## Installation

1.  Clonez le dépôt :
    ```bash
    git clone https://github.com/votre-utilisateur/votre-repo.git
    ```
2.  Installez les dépendances :
    ```bash
    pip install -r requirements.txt
    ```
3.  Lancez l'application :
    ```bash
    streamlit run app_production.py
    ```

## Contribuer

Les contributions sont les bienvenues ! Veuillez lire les [directives de contribution](CONTRIBUTING.md) pour plus d'informations.
