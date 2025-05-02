# Collecte-de-donnee-via-API

Ce programme sert a **collecté des données de manière automatisée.**

Imagine un chercheur qui doit parcourir des milliers d'annonces manuellement. C'est long et fastidieux. Notre FranceTravailAPI fait cette collecte automatiquement :

  - Il va chercher les données brutes : Les fonctions comme search_offres récupèrent les informations directement depuis la source (l'API de France Travail). C'est comme aspirer les données dont on a besoin.
    
  - Il structure un peu les données : Même si la fonction search_offres renvoie du JSON brut, la fonction recherche_offres commence déjà à organiser les informations importantes (titre, entreprise, lieu, description) dans un format plus facile à manipuler.

  - Il gère la "qualité" des données de base : Des fonctions comme find_commune_code aident à s'assurer qu'on utilise des informations de localisation correctes, ce qui est important pour une analyse géographique. nettoyer_description prépare le texte pour une éventuelle analyse de contenu.

*Ce programme en Python fonctionne comme une boîte à outils qui sait comment parler au site de France Travail pour trouver des offres d'emploi. Cette boîte à outils s'occupe de se connecter correctement, de chercher les villes même si on fait des fautes, et de nous donner les offres d'une manière facile à comprendre.*

**ballogouessicarole@gmail.com**
