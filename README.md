# Data Party les 30 ans de la MTD

![logo_30ans](readme.files/30ans_mtd.png)

Dans le cadre des 30 ans de la MTD, les différents organismes de la [Maison de la TéléDétection]() organisent une journée dédiée à la Science Ouverte. Cette année, le sujet principal sera la visualisation de données à travers deux activités :

- Séminaire de 10h à 12h30
- Un challenge de 09h à 18h

**Date**: Le jeudi 03 Octobre 2024

**Lieu du séminaire :**
En Salle Asie et Afrique, Batiment Adret, Maison de la TéléDétection.

En distanciel via [Zoom INRAE](https://inrae-fr.zoom.us/j/3650238425?pwd=dEorRHlQNTF2b1Bzb1NsVHdqUmZGdz09&omn=96030529291).


## Programme Séminaire 

| Time           | Speaker               | Topic                                        | Presentation link |
| -------------- | --------------------- | -------------------------------------------- | ----- |
| 09h00 - 09h15  | [Organisateurs](https://30ans-mtd.github.io/dataparty/about.html)          | Lancement du **Challenge**                                 |                              | [[PDF](https://github.com/30ans-MTD/dataparty/raw/main/presentations/2024-10-03_Dataparty_30ans-challenge.pdf)] |
| 09h50 - 10h00  | [Organisateurs](https://30ans-mtd.github.io/dataparty/about.html)          | Lancement du Séminaire **visualisation de données**                                | [[PDF](https://github.com/30ans-MTD/dataparty/raw/main/presentations/2024-10-03_Dataparty_30ans-webinaire.pdf)] |
| 10h00 - 11h00  | [Nicolas Lambert](https://neocarto.hypotheses.org/nicolas-lambert)        | Construire des cartes réactives pour le Web avec Observable JavaScript                      | [[Notebook Observable](https://observablehq.com/@neocartocnrs/mtd) |]
| 11h00 - 11h30  | [Marie Gradeler](https://fr.linkedin.com/in/marie-gradeler)         | Comment choisir la visualisation de données la plus adaptée ?| [[PDF](https://github.com/30ans-MTD/dataparty/raw/main/presentations/Comment%20choisir%20la%20visualisation%20de%20donn%C3%A9es%20la%20plus%20adapt%C3%A9e.pdf)]
| 11h30 - 12h00  | [Christophe Revillion](https://www.researchgate.net/profile/Christophe-Revillion)   | Présentation de deux applications Rshiny, les projets SCO Leptoyangoon et Cimopolée                              | [[PDF](https://nextcloud.inrae.fr/s/jKXxi7yxyTAQX2J)] |



## Challenge : La plus belle data viz !
Les équipes seront constituées le jour même par les organisateurs afin de :

- Mélanger les participants entre organismes (i.e. les équipes devrons avoir plusieurs tutelles)
- Avec un socle commun de compétences (Programmation, cartographie, web, géographie)

L'**objectif** est de proposer des visualisations, particulièrement jolies, qui arrivent à faire passer un message [cf [Répartition spatiale des co-auteurs des UMRs de la MTD](https://30ans-mtd.github.io/dataparty/idees_dataviz.html)].
Pour ce faire, nous mettons à disposition plusieurs notebooks pour construire des jeux de données autour des articles et données publiées par les différentes structures de la MTD. Ces notebooks interrogent de manière automatique les API des entrepôts les plus utilisés par la MTD.

À la fin de la journée, nous récolterons les différentes visualisations des équipes. Le Lendemain, nous ferons passer un sondage pour choisir l'équipe gagnante.

**Prix** : L'équipe gagnante sera invitée dans un restaurant à Montpellier !

**Description des Jeux de données proposés** : 

| Jeux de données                        | Description                                                                                   | Notebook Lié                                         | Information Géographique                            |
| ------------------------------------ | --------------------------------------------------------------------------------------------- | ---------------------------------------------------- | --------------------------------------------------- |
| Collection Hal d'Espace-Dev et Tetis | Génère un fichier CSV contenant les métadonnées des articles scientifiques (API Hal).          | [construction_dataset_hal.ipynb](notebooks/hal_dataset.ipynb) | Les pays des adresses d'affiliation des co-auteurs       |
| Jeux de données TETIS                | Combine les jeux de données déposées dans Recherche.Data.Gouv et Dataverse.Cirad (API Dataverse). | [data_tetis.ipynb](notebooks/data_tetis.ipynb)        | Terrain d'étude quand cela est renseigné |
| Jeux de données Espace-Dev           | Récupère les métadonnées de la collection Espace-Dev de DataSuds (API Dataverse).              | [data_espace-dev.ipynb](notebooks/data_espace-dev.ipynb) | Terrain d'étude quand cela est renseigné    |
| Jeux de données OpenIG               | Récupère les métadonnées des jeux de données via l'IDG d'OpenIG (API CKAN).                   | [data_openig.md](notebooks/data_openig.md)      | -  |
| Jeux de données Nitidae | fichier csv export Zenodo | [donnees_nitidae.csv](https://github.com/30ans-MTD/dataparty/blob/main/readme.files/donnees_nitidae.csv) | -  |





---

## Organisateurs

 | Prénom   | Nom     | Institut      |
|-----------|----------|---------------|
| Rémy      | Decoupes | TETIS         |
| Vincent   | Delbar   | Telescop      |
| Laurent   | Demagistri| EspaceDev    |
| Etienne   | Duperron | Nitidae       |
| Nadia     | Guiffant | TETIS         |
| Michaël   | Viadere  | OpenIG        |