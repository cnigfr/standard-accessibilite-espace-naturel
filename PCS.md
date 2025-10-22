# Groupe de travail CNIG Plans communaux et intercommunaux de sauvegarde (PCS-PICS)

Ce référentiel publie les documents et travaux du [GT CNIG Plans communaux et intercommunaux de sauvegarde](https://cnig.gouv.fr/gt-plans-communaux-et-intercommunaux-de-sauvegarde-a30138.html) (GT CNIG PCS-PICS), qui fonctionne suivant [ce mandat](https://cnig.gouv.fr/gt-plans-communaux-et-intercommunaux-de-sauvegarde-a30138.html#H_Mandat-du-GT), sous pilotage de la [Direction générale de la sécurité civile et de la gestion des crises ](https://www.securite-civile.interieur.gouv.fr/) (Ministère de l’intérieur / DGSCGC).

## Standard CNIG Plans communaux et intercommunaux de sauvegarde

Le standard CNIG PCS-PICS est actuellement en phase de : **<mark>_élaboration_</mark>**.

_Après élaboration, consultation publique, puis validation par la Commission des standards, il sera destiné à être publié sur la page web des [ressources](url) du GT CNIG PCS-PICS._

> intégrer une image

## Contexte

Sur le fondement de ses pouvoirs de police générale, le maire assure la réponse de premier niveau à toute situation mettant en péril sa population. La commune constitue ainsi le premier maillon de l'organisation générale de la sécurité civile.

A cette fin la commune élabore un **plan communal de sauvegarde (PCS)**. Document à visée résolument opérationnelle, cet outil de gestion des crises lui permet de préparer la réponse à tout type d'évènements pouvant impacter la population, quelle qu'en soit la nature (accident, phénomène météo, inondation, etc.).

Le PCS a pour objet de définir, par avance, les procédures et organisations qui seront mises en place en cas d'événement. Cette démarche permet, en situation de crise, de ne pas se poser de questions sur l'organisation à mettre en place afin de traiter l'événement de manière rapide et pertinente.

Les communes sont appuyées dans ces missions par les intercommunalités qui disposent des **plans intercommunaux de sauvegarde (PICS)**. Ce plan permet à la commune sinistrée de solliciter les moyens propres de l'EPCI et les moyens mutualisés des communes-membres de l'intercommunalité.

Le PICS organise également la continuité des compétences exercées par l'EPCI en période de crise (voirie, eau potable, assainissement, etc.).

> [!TIP]
> source : Ministère de l’intérieur, [fiche PCS-PICS](https://www.securite-civile.interieur.gouv.fr/reagir/comment-se-preparer-face-aux-risques/plans-communaux-et)

## Cadre juridique

- [Loi n° 2004-811 du 13 août 2004](https://www.legifrance.gouv.fr/loda/id/JORFTEXT000000804612)  de modernisation de la sécurité civile
- [Loi n° 2021-1520 du 25 novembre 2021](https://www.legifrance.gouv.fr/jorf/id/JORFTEXT000044367862) visant à consolider notre modèle de sécurité civile et valoriser le volontariat des sapeurs-pompiers et les sapeurs-pompiers professionnels
- Articles [L731-3](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000044375292) et L731-4](https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000044370020) et autres du Code de la Sécurité Intérieure
- Codes : code de l’Environnement, code Forestier, etc.

### Echéances réglementaires :

- La réalisation et l’actualisation des PCS est fixée au mois d’octobre 2024 ;
- La réalisation des PICS est fixée au mois de novembre 2026.


## Enjeux

- respecter le délai réglementaire (très court pour les PICS, déjà dépassé pour les PCS)
- œuvrer à l’harmonisation des pratiques communales et intercommunales
- assurer l’interopérabilité des données : pouvoir les partager avec d’autres structures (Préfectures, SDIS) et les assembler aux niveaux supra-communaux (départements, régions, etc..)
- rationaliser les solutions logicielles et les propositions d’accompagnement disponibles

## Objectifs

Le GT CNIG PCS-PICS vise à :

- rassembler les modèles de documents existants sur la thématique
- obtenir un consensus avec les collectivités territoriales et l’ensemble des parties prenantes pour réaliser un standard de données conmprenant :
  - un modèle conceptuel de données
  - des modèles de fichiers
  - une symbologie spécifique pour représenter les objets constitutifs des PCS et PICS
- accompagner les communes et intercommunalités en fournissant des modèles pour la structuration de fichiers
- mutualiser les données interopérables, afin de pouvoir agréger les PCS et les PICS aux niveaux supérieurs sur les éléments principaux
- faciliter la mise à jour des PCS-PICS, notamment via l’intégration dans les logiciels de gestion de crise et les plateformes mutualisées et en favorisant l’interopérabilité des données.

Le GT CNIG PCS-PICS travaillera en coordination avec :
- le [GT CNIG Risques](https://cnig.gouv.fr/gt-risques-a25378.html) et le [géostandard Risques profil PPR](https://github.com/cnigfr/Geostandards-risques-ppr) (DICRIM, enjeux, données emprises de risques pris en compte dans le cadre de la réalisation des PCS/PICS).
- le [GT CNIG ERP](https://cnig.gouv.fr/gt-erp-a24557.html), qui serait à relancer.

## Acteurs

- Institut des risques majeurs (IRMa)
- Cerema
- Entente Valabre
- GIP ATGéri
- AMF
- AITF GT SIG TOPO et AITF GT Risques
- Métropole Aix-Marseille Provence
- ECAA
- Cs soprasteria Group (CRIMSON)
- Riscrises
- [Club des intercommunalités dans l'élaboration des PICS](https://outil2amenagement.cerema.fr/actualites/club-pour-faciliter-les-plans-intercommunaux-sauvegarde-pics)
- etc.

> [!IMPORTANT]
> Le groupe de travail est ouvert à toutes les parties prenantes.

## Cas d’usage

- Agir rapidement de façon coordonnée en situation de crise, 
- Eviter de se poser des questions sur l'organisation à mettre en place afin de traiter l'événement de manière rapide et pertinente.


## Organisation du dépôt

* Le dossier [documentation](documentation) contient les ressources documentaires du groupe de travail ;
* Le dossier [reunions](reunions) contient les supports, comptes-rendus de réunions et documents de suivi du groupe de travail ;
* Le dossier [standard](standard) contient le projet de standard ainsi que les ressources qui lui sont liées ;
* Le dossier [schema](schema) contiendra (le cas échéant) le schéma json conforme au standard au standard TableSchema pour la publication des données ouvertes sur [data.gouv.fr]([url](https://www.data.gouv.fr/)).

### Données ouvertes

> [!TIP]
> Ce standard CNIG ne possède pas encore de schéma de données directement accessible sur schema.data.gouv.fr.

## Informations et participation au groupe de travail

### Méthodologie

La méthodologie des groupes de travail du CNIG repose sur une diversité d'approches complémentaires :

* Construire **une gouvernance ouverte** à l'ensemble des parties prenantes, afin de susciter l’adhésion et de créer le cadre favorable à la pérennité du dispositif ;
* Promouvoir et exploiter **les retours d'expériences** afin d'étudier les diversités d'usages et embarquer les acteurs en les positionnant au centre du processus d’alimentation des référentiels géographiques ;
* Privilégier **l’interopérabilité** entre systèmes d'informations à l’échelle nationale pour favoriser le partage et l’échange de données : éviter les doubles stockages, doubles saisies, etc. ;
* S'appuyer sur les **processus éprouvés** de [standardisation du CNIG](http://cnig.gouv.fr/les-standards-cnig-a18959.html#Etapes-de-creation-d-un-Standard-CNIG) et de modélisation suivant [schema.data.gouv.fr](https://guides.etalab.gouv.fr/producteurs-schemas/).
* L’objectif est d'aboutir à terme à un **consensus** qui se traduise par un **standard et un modèle de donnée communs** pour la structuration des PCS-PICS.

### Actualisation

Le standard PCS-PICS évoluera en fonction des évolutions réglementaires et de l'expression des besoins de sa communauté des utilisateurs.

Les ressources associées et les bases de données correspondantes seront actualisées conformément au standard CNIG PCS-PICS. Les mises à jour de base de données sont effectuées en modifiant le cas échéant les données qui y figurent déjà.

### Comment contribuer

Vous pouvez contribuer aux travaux en créant une issue dans la [section issues](url) de ce référentiel github.

Il s'agit d'une fonctionnalité permettant de poser une question, de proposer une suggestion d'amélioration ou de correction... directement sur ce référentiel github, ce qui en informe automatiquement les animateurs du GT CNIG PCS-PICS et ses participants (qui se seront préalablement abonnés à la réception des issues par mail).

> [!TIP]
> Un **Manuel du débutant pour Github** est disponible dans le répertoire [documentation](documentation)

### Nous contacter

[Page de contact du CNIG](https://cnig.gouv.fr/spip.php?page=contact)

### Licence

Les travaux du GT CNIG PCS-PICS sont réalisés sous [Licence Ouverte Etalab 2.0](https://www.etalab.gouv.fr/licence-ouverte-open-licence/).
