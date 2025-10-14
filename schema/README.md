# Schéma _thématique_

_Indiquer ici les informations pertinentes pour la compréhension et l'utilisation du schéma et supprimer les informations ci-dessous qui sont destinées à aider le GT dans ses travaux._

## Réaliser un schéma

L'intégration d'un schéma à schema.data.gouv.fr est documentée [ici](https://guides.data.gouv.fr/guides-open-data/guide-qualite/maitriser-les-schemas-de-donnees/integrer-un-schema-de-donnees-a-schema.data.gouv.fr).

Les types de schéma suivant sont supportés, en fonction du format d'échange et du modèle de donnée défini par le GT:

* Table Schema : adapté pour la description de données tabulaires (sous forme de tableurs ou de CSV). Le schéma est décrit via une fichier JSON.

* Datapackage : plusieurs tables décrites chacune avec un TableSchema.

* JSON Schema : adapté pour la description de données avec une notion de hiérarchie. Ce standard utilise le format JSON.

* XML Schema Definition (XSD) : adapté pour la description de données avec une notion de hiérarchie. Ce standard utilise le format XML.

## Le format TableSchema

Le fonctionnement du format TableSchema est décrit [ici](https://guides.data.gouv.fr/guides-open-data/guide-qualite/maitriser-les-schemas-de-donnees/creer-un-schema-de-donnees/focus-construire-un-schema-tableschema).

Il est adapté pour les données structurées de façon tabulaire.

Les datapackages sont des assemblages de TableSchema. Pour plus d'information voir  [cette page](https://datapackage.org/standard/data-package/)

## Le format JSON Schema

* [cette vidéo introductive](https://youtu.be/gLcr84H2x5Q) revient sur le format JSON et utilise l'environnement Visual Studio pour montrer son utilisation en pratique,
* [la documentation du site Json Schema](https://json-schema.org/learn/getting-started-step-by-step) est très complète, autant pour une première approche que comme support pour la rédaction du schema (on y trouve une définition des propriétés obligatoire, des règles syntaxiques, etc.).

Le format JSON est adapté pour les données ayant un nombre de classe limité mais présentant des éléments imbriqués.

## Le format XML schema Definition

La génération du schéma XSD se fait généralement de manière automatisée ou semi-automatisée à partir du diagramme UML. Le logiciel Enterprise Architect de Sparx System permet de faire cet export automatisé. (voir [ici](https://sparxsystems.com/enterprise_architect_user_guide/17.0/modeling_languages/generate_gml_application_schem.html))

Le format GML (XML pour les données Geo) est adapté pour les données présentant un grand nombre de classes et beaucoup de relation entre ces classes.

> [!TIP]
> La rédaction de fichier JSON ou XML (de code informatique, ou de tout type de fichier ayant vocation à être lu par une machine) est plus facile avec dans un environnement adapté. Github propose une interface (fondée sur Visual Studio) proposant tous les avantages des IDE (environnement de développement intégré) qui peut être activée en pressant la touche "." (shift + ";" sur un clavier azerty) sur une page du domaine Github. Cette environnement a de nombreux atouts (indentation automatique, coloration du code, exécution de code, extensions, etc.).

## Validation du schéma

Le schéma doit respecter un certain nombre de prérequis avant de pouvoir être intégré à schema.data.gouv.fr. Les exigences sont détaillées [ici](https://schema.data.gouv.fr/validation.html).

### Quelques exemples

* [le schéma des opérations d'aménagement du territoire](https://github.com/cnigfr/schema-operations-amenagement/blob/main/schema/operation-amenagement/schema_operation-amenagement.json),
* [le schéma friches](https://github.com/cnigfr/schema-friches/blob/main/schema.json),
* [le schéma des infrastructures de recharge pour véhicules électriques](https://github.com/etalab/schema-irve/blob/master/statique/schema-statique.json),
* [les schémas du standard sites économiques - Datapackage](https://schema.data.gouv.fr/cnigfr/schema-sites-economiques/).
* [les schémas des aménagements cyclables - JSON](https://schema.data.gouv.fr/schemas/etalab/schema-amenagements-cyclables/0.3.5/schema_amenagements_cyclables.json)
