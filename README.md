# Modèle de dépôt Github pour les standards CNIG

> [!IMPORTANT]
> **Attention** : Le modèle de fichier README débute après ce paragraphe. Dans la suite,
>
> * toutes les consignes en citation, comme cette ligne, doivent être supprimées,
> * tout ce qui est <mark>_surligné_</mark> doit être remplacé.
>
> Vous trouverez l'ensemble des consignes et conseils pour utiliser ce modèle de dépôt sur [cette page de la documentation](https://app.gitbook.com/o/w6D6SnLwCXQaMMSzcTvp/s/weZQRU1RV5So9WzNyxlW/~/changes/19/la-fabrique-des-standards/realisation-du-standard/utiliser-le-modele-de-depot-github). 

---
<!-- Supprimer les trois tirets précédents (qui insèrent une ligne) -->

# Standard <mark>_Nom_</mark>

<!-- Indiquer le nom du standard à la place de <mark>_Nom_</mark>. Le texte entre les balises "<mark>_" et "_</mark>" apparaît en italique surligné et doit être remplacé dans ce modèle -->

> _Insérer une description du standard et des données concernées en quelques lignes. Ici comme dans la suite, il est recommandé de réutiliser le contenu du mandat du GT ou d'autres documents déjà rédigés. Voici plusieurs exemples pour vous inspirer dans la rédaction :_
>
> * _[standard des opération d'aménagement](https://github.com/cnigfr/schema-operations-amenagement/)_
> * _[standard risques](https://github.com/cnigfr/Geostandards-Risques)._
>
> _Afin de clarifier la lecture de cette description sur le site schema.data.gouv, préciser ici lorsque le standard n'est pas accompagné d'un schéma sur schema.data.gouv:_
>
> [!TIP]
> Ce standard CNIG ne possède pas de schéma de données directement accessible sur schema.data.gouv.fr. 

Davantage de documentation peut être trouvée sur le site du CNIG au lien suivant : <mark>_insérer le lien vers la page du GT_</mark>.

> Insérer une (ou plusieurs) image(s) pour illustrer la thématique en remplaçant le logo du CNIG ci-dessous.  
<!-- Pour remplacer le logo du CNIG, suivre le modèle "![texte alternatif](lien vers l'image) Les images peuvent être chargées sur le dépôt Github dans un dossier image -->
![logo du CNIG à remplacer par l'image du standard](https://cnig.gouv.fr/IMG/png/cnig2022_geolocalise-petit.png)

## Contexte

> _Décrire le contexte dans lequel le schéma a été élaboré. Il peut être utile de renvoyer ici vers la page du GT CNIG où la documentation du standard correspondant peut être trouvée._

## Cadre juridique

> _Citer les textes liés aux données sur lesquelles porte le schéma. Même lorsque l'utilisation du schéma n'est pas mentionnée dans les textes, il peut être utile de faire référence ici aux lois, décrets, arrêtés portant spécifiquement sur les données, leurs conditions de collecte, de partage, etc. Il n'est pas utile de citer les textes plus généraux (portant sur l'open data par exemple)._

## Finalité

> _Les enjeux et objectifs liés à la création du standard doivent être précisés ici._

## Cas d’usage

> _Présenter ici quelques cas d'usage de données conformes au schéma. Ces cas peuvent exister ou être fictifs._

## Organisation du dépôt

* Le dossier [ressources](ressources) contient les documents utiles pour les utilisateurs du standard ;
* Le dossier [groupe_de_travail_CNIG](groupe_de_travail_CNIG) contient les comptes-rendus de réunions et les documents de suivi du groupe de travail ;
* Le dossier [standard](standard) contient le standard ainsi que les documents qui lui sont liés ;

> _A supprimer en l'absence de schéma JSON :_

* Le dossier [schéma](schéma) contient le schéma ainsi que les documents qui lui sont liés.

## Modalités de production des données

> _Dans le cas où la création du standard interviendrait alors que les données sont déjà produites, documenter ici comment leur production a lieu. Dans le cas contraire, cette partie peut être supprimée._

### Données ouvertes

> _Dans le cas où les données sont publiées en open data, sinon, cette partie peut être supprimée._

Les données relatives à <mark>_la thématique_</mark> sont ouvertes et sont à la disposition de tous. Elles seront publiées sur <https://www.data.gouv.fr>

## Informations et participation au groupe de travail

### Méthodologie

> _Cette partie peut être laissée telle quelle. Elle vise à expliquer les modalités d'adoption d'un standard par le CNIG._

La méthodologie des groupes de travail du CNIG repose sur une diversité d'approches complémentaires :

* Construire **une gouvernance ouverte** à l'ensemble des parties prenantes, afin de susciter l’adhésion et de créer le cadre favorable à la pérennité du dispositif ;
* Promouvoir et exploiter **les retours d'expériences** afin d'étudier les diversités d'usages et embarquer les acteurs en les positionnant au centre du processus d’alimentation des référentiels géographiques ;
* Privilégier **l’interopérabilité** entre système d'informations à l’échelle nationale pour favoriser le partage et l’échange de données : éviter les doubles stockages, doubles saisies, etc. ;
* S'appuyer sur les **processus éprouvés** de [standardisation du CNIG](http://cnig.gouv.fr/les-standards-cnig-a18959.html#Etapes-de-creation-d-un-Standard-CNIG) et de modélisation suivant [schema.data.gouv.fr](https://guides.etalab.gouv.fr/producteurs-schemas/).
L’objectif est d'aboutir à terme à un consensus qui se traduise en un standard et un modèle de donnée commun pour la thématique considérée.

### Actualisation

> _Préciser ici la phase d'avancement dans laquelle se trouve le standard selon la terminologie de [la Fabrique des standards](https://guides.data.gouv.fr/guides-de-data.gouv.fr/fabrique-des-standards/la-fabrique-des-standards) (rédaction, validation, déploiement, etc.). Il peut être utile de donner des éléments de calendrier comme la date de passage en commission des standards ou devant le conseil plénier._
> _Indiquer également les évolutions prévues ou prévisibles du standard (en fonction des évolutions réglementaires, des retours des utilisateurs, etc.), ainsi que les évolutions prévues pour les bases de données, logiciels, API, etc. concernées par le standard._

Le projet de standard <mark>_thématique_</mark>, puis le standard une fois validé par le CNIG, évoluera en fonction des évolutions réglementaires et de l'expression des besoins de la communauté des utilisateurs.

Les ressources associées et les bases de données correspondantes seront actualisées conformément au standard CNIG <mark>_thématique_</mark>. Les mises à jour de base de données sont effectuées en modifiant le cas échéant les données qui y figurent déjà.

### Comment contribuer

> _Indiquer ici comment contribuer au standard. Par exemple :_
Vous pouvez contribuer au standard en créant une issue sur cette page (il s'agit d'une fonctionnalité permettant de poser une question, de faire une remarque, une suggestion etc. directement sur github, ce qui en informe automatiquement les responsables du dépôt).

### Nous contacter

Pour contacter le GT CNIG <mark>_thématique_</mark>, écrire à l’adresse cnig[at]cnig.fr.

### Licence

Les travaux du GT CNIG <mark>_thématique_</mark> sont réalisés sous [Licence Ouverte Etalab 2.0](https://www.etalab.gouv.fr/licence-ouverte-open-licence/).
