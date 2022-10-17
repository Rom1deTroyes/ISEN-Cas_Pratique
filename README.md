# ISEN-Cas_Pratique
Cas Pratique ISEN 2022

---
created: 2022-10-17T09:26:31 (UTC +02:00)
tags: []
source: https://simplonline.co/briefs/43bc00fb-fec8-4296-9cba-acfe41b6c49e
author: 
---

# Simplonline - Détails d'un brief

> ## Excerpt
> Les caméras sont devenues un moyen important pour développer plusieurs applications en termes de surveillance et de sécurité.
# Vérificateur de l’uniforme
Mohammed El Amine BECHAR

16.10.2022

Développement d’une application pour vérifier l’uniforme des travailleurs (casque et gilet)

![](https://simplonline.co/_next/image?url=https%3A%2F%2Fsimplonline-v3-prod.s3.eu-west-3.amazonaws.com%2Fmedia%2Fimage%2Fjpg%2F87a3a96c-628c-4ef4-be2a-77f33c0acab9.jpg&w=1280&q=75)


## Contexte du projet

Les caméras sont devenues un moyen important pour développer plusieurs applications en termes de surveillance et de sécurité.

Une entreprise qui propose des solutions technologiques en caméra de surveillance et de sécurité a développé une application IA capable à détecter et localiser la présence du port d’un casque de chantier ou non à partir d’une vidéo. Cette entreprise cherche à améliorer et étendre cette application pour détecter et/ou localiser le gilet de sécurité, si la personne porte un gilet ou non.

L’application développée par l’entreprise est une application Web sous Streamlit-webrtc, elle est capable d’activer la cam du PC et affichée sur la vidéo le résultat de la détection.

Pour faire démarrer cette application, il faut :

1.  Accéder au dossier : Streamlit\_App/
2.  Installer les bibliothèques nécessaires : pip install -r requirements.txt
3.  Pour lancer l’application : streamlit run app.py
4.  Attention : le compilateur C++ devrait être installé pour pouvoir installer la bibliothèque Streamlit-webrtc

Le besoin de cette entreprise est de rajouter sur la même application les fonctionnalités suivantes :
-   Détection et/ou localisation de la présence/absence du gilet de sécurité.
-   Un message d’alerte à afficher sur la page web (en dehors de la vidéo) si une seule personne ne porte pas son casque ou son gilet.
    
    Exemple :
    
    Si toutes les détections sont vérifiées :
    
    Message = « Uniforme vérifié »
    
    Sinon :
    
    Message = « Uniforme non vérifié »
    
NB. Le dossier de l’application se trouve dans ce lien : https://drive.google.com/drive/folders/192CXzJ\_fsYx2bRxYchxQVS5yrQ-Nn5wi?usp=sharing

## Modalités pédagogiques

Le projet est réalisé individuellement.

## Critères de performance

– Un code python bien structuré, avec les commentaires nécessaires.
– Le choix du modèle IA.
– Evaluation des performances du modèle.

## Modalités d'évaluation

L’évaluation de ce projet sera sur :
– Un rapport qui explique les différentes étapes du projet.
- Une présentation de l'architecture CNN utilisée (à préciser dans le rapport).
– Conclusion (avantages, inconvénients et recommandations).
– Le bon fonctionnement de l’application (Interface ou Web).

## Livrables

– Un dossier qui contient les éléments nécessaires (code python, modèle et autre) pour faire fonctionner votre application.
– Un Readme.md pour mettre en avant votre application.
