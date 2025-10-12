# internet-provider-client-sentiment-analysis-app-streamlit-postgresql
Ce projet propose le développement d’un système de chat intelligent et sécurisé, intégrant un moteur d’analyse sémantique pour l’étude automatisée des avis clients.

L’objectif principal est d’offrir une **plateforme interactive** capable de gérer des utilisateurs, de sauvegarder leurs échanges, et d’analyser en temps réel la **satisfaction client** selon plusieurs critères tels que la **technologie utilisée** (ADSL, VDSL, Fibre) ou la **région**.

Ce projet a été développé dans le cadre d’un stage et repose sur une architecture moderne combinant **Python, Streamlit et PostgreSQL**.

Grâce à une interface moderne développée avec **Streamlit**, le système offre une expérience fluide et intuitive, tout en garantissant la **sécurité des données** via une **authentification chiffrée** et le **hachage des mots de passe avec bcrypt**.  

En parallèle, un module d’**analyse de sentiment** basé sur un **modèle NLP fine-tuné** permet de classifier automatiquement les retours clients (*positif, négatif, neutre*) et de générer des **indicateurs statistiques exploitables** pour un suivi précis de la qualité du service.

Ce projet allie ainsi **interaction en temps réel** et **analyse automatique du langage naturel** offrant une **vision claire et opérationnelle de la satisfaction des abonnés**.

Le code source de l’application n’est pas partagé publiquement pour des raisons de confidentialité.
Ce dépôt contient uniquement des **captures d’écran illustrant l’interface et le fonctionnement de l’application**.

## Captures d’écran

Voici quelques images de l’application :

![Interface de connexion utilisateur de l’application](interface%20connexion.png)
**Interface de connexion utilisateur de l’application**  <br><br>



![Interface d’inscription de l’application](interface%20insription.png)
**Interface d’inscription de l’application**  <br><br>




    
![Interface principale du chatbot après connexion](interface%20chatbot.png)
**Interface principale du chatbot après connexion**  <br><br>




    
![Détection d’une forte positivité dans un commentaire sur l’installation du VDSL](analyse%20de%20sentiments%20installation%20du%20VDSL.png)
**Détection d’une forte positivité dans un commentaire sur l’installation du VDSL**  <br><br>




    
![Détection d’une forte négativité dans un commentaire sur l’installation de l’ADSL](analyse%20de%20sentiments%20installation%20de%20ADSL.png)
**Détection d’une forte négativité dans un commentaire sur l’installation de l’ADSL**  <br><br>




    
![Répartition des sentiments des avis pour une produit donné](Avis%20sur%20la%20fibre%20optique.png)
**Répartition des sentiments des avis pour une produit donné**  <br><br>




    
![Exemples de questions qu'on peut poser sur le chatbot](Exemples%20questions%20chatbot.png)
**Exemples de questions qu'on peut poser sur le chatbot**  <br><br>


  
## Perspectives d’amélioration

- Ajouter un module d’analyse des conversations pour identifier les tendances.
- Intégrer un modèle de langage plus avancé pour enrichir les réponses du chatbot.
- Déployer l’application sur un serveur cloud sécurisé.



