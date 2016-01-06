# GraceTHD-MOD

Le Modèle d'Organisation des Données et documents GraceTHD-MOD présente l'organisation des données et documents (techniques et adminsitratifs) à mettre en oeuvre en complément de GraceTHD-MCD et en lien avec lui :

- Types de documents, contenu, usage et préconisations (collecte ou non à chaque statut, formats, informations complémentaires)
- Références des documents et nommage des fichiers

La référence d'un document étant établie en tenant compte de son statut et de son lien avec les objets de la base de données, le MOD présente également :

- Une liste de statuts types, basée sur la loi MOP pour les infrastructures
- Une méthode de référencement des objets dans la base de données

Le présent MOD contient également un exemple de mise en application en lien avec un jeu de données témoin, accompagné d'une arborescence type pouvant être mise en place.

Dans sa prochaine version, le MOD contiendra également des préconisations de remplissage des champs du MCD, selon le type de projet et le statut d'avancement.

GraceTHD-MCD est le modèle de données validé par la Covadis comme [Geostandard Aménagement Numérique des Territoires v2](http://www.geoinformations.developpement-durable.gouv.fr/standard-covadis-amenagement-numerique-des-a3300.html). 

La page de présentaion du projet GraceTHD : http://www.avicca.org/actualite/modele-de-donnees-gracethd
La plateforme de gestion du projet GraceTHD : [http://redmine.gracethd.org](http://redmine.gracethd.org)

GraceTHD-MOD est un des projets maintenus par [GraceTHD-community](https://github.com/GraceTHD-community)
* [GraceTHD-MCD](http://gracethd-community.github.io/GraceTHD-MCD/) : Un modèle de données relationnel destiné à échanger des modèles numériques de réseaux de télécommunications. 
* [GraceTHD-Demo](http://gracethd-community.github.io/GraceTHD-Demo/) : Un dépôt dédié à des projets de démonstrations est également disponible. 

### Contexte
De nombreux réseaux télécoms de très hauts débit sont déployés actuellement en France, en mobilisant des acteurs publics et privés, avec pour objectif de garantir la couverture intégrale du territoire. Afin d'assurer la meilleure utilisation des réseaux, l'homogénéisation et l'industrialisation des déploiements est un enjeu majeur.

Dans ce cadre, les travaux initiés par le projet GraceTHD visent à l'interopérabilité des Systèmes d'Informations Géographiques (SIG) mis en place pour chaque réseau d'initiative publique.

### Caractéristiques de la v2
GraceTHD-MOD v2 est la première version du MOD, nommée v2 pour conserver une cohérence avec GraceTHD-MCD v2 et le Geostandard ANT v2. Elle a été créée pour accompagner cette importante refonte du Geostandard ANT v1.

### Contenu
* changelog.txt : historique des modifications
* \mod_doc\ : documentation du modèle (fichier ods)
		Nommage des fichiers et références des documents, arborescence de classement
		Liste et définition des statuts, basée sur la loi MOP pour les infrastructures
		Niveaux de référencement permettant de "classer" les objets et les documents du réseau et de lier les documents aux objets du MCD
		Types de documents, contenu types, principaux usages et préconisations de collecte
* \Exemple\ : exemple de mise en application, avec jeu de données témoin et arborescence (voir readme.txt)
* \sources\ : fichier de travail


### Projets relatifs à GraceTHD
* **Gracelite** : 
Projet open source en cours de développement. Il s'agit d'une boite à outils destinée dans un premier temps à garantir les imports / exports du MCD Spatialite et SHP/CSV. Ceci permet de profiter en mode local d'une base de données SQL. Les imports permettront notamment de faire office d'un premier niveau de contrôle de conformité générale de la structure des shapefiles / CSV. Des exemples de scripts d'import/export PostGIS sont également disponibles. 

* **Outil de contrôle** : 
La création d'un outil de contrôle à destination des collectivités est prévue. 

### Support or Contact
Une plateforme de gestion de projet [Redmine](http://redmine.gracethd.org) destinée à remonter les demandes d'évolutions, les anomalies et les demandes d'assistance est disponible. 

### Contributeurs

Toute contribution au modèle est la bienvenue et encouragée. 

Comité de pilotage : Avicca - L'Agence du Numérique - Caisse des dépôts - Région Alsace - Région Aquitaine - Syane - Mégalis Bretagne - Manche Numérique - La Fibre 59/62 - Gironde Numérique - Touraine Cher Numérique - Oise THD. De nouvelles collectivités rejoignent actuellement le comité de pilotage. 

Groupement d'entreprises : DOTIC - CADaGEO - Aleno - Cochr@n.

Comité consultatif : Aleno, Altitude Infrastructure, Ambition télécoms, Ardèche Drôme Numérique, Axione, CADaGEO, Circet, Covadis/Cerema, Covage, Dotic, Eiffage, Esri France, GISmartsware, Groupe Interop Fibre, Isère, Mégalis Bretagne, Oise THD, Orange, Région Alsace, SFR Collectivités, SPIE, Syane, Tutor. 