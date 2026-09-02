# Schéma

Ce répertoire contiendra (le cas échéant) le schéma JSON correspondant au **Standard CNIG Accessibilite du cheminement en espace naturel**
Cette section est en **travaux** et présente ci-desous quelques concepts, ressources et exemples.

## Réaliser un schéma

L'intégration d'un schéma à schema.data.gouv.fr est documentée [ici](https://guides.data.gouv.fr/guides-open-data/guide-qualite/maitriser-les-schemas-de-donnees/integrer-un-schema-de-donnees-a-schema.data.gouv.fr).

La thématique ACEN est porté par ce type de schéma : 

- [ ] Table Schema : adapté pour la description de données tabulaires (sous forme de tableurs ou de CSV). Le schéma est décrit via une fichier JSON.

- [x] Datapackage : plusieurs tables décrites chacune avec un TableSchema.

- [ ] JSON Schema : adapté pour la description de données avec une notion de hiérarchie. Ce standard utilise le format JSON.

- [ ] XML Schema Definition (XSD) : adapté pour la description de données avec une notion de hiérarchie. Ce standard utilise le format XML.

## Le format TableSchema

Le fonctionnement du format TableSchema est décrit [ici](https://guides.data.gouv.fr/guides-open-data/guide-qualite/maitriser-les-schemas-de-donnees/creer-un-schema-de-donnees/focus-construire-un-schema-tableschema).

Il est adapté pour les données structurées de façon tabulaire.

Les datapackages sont des assemblages de TableSchema. Pour plus d'information voir  [cette page](https://datapackage.org/standard/data-package/)

## Validation du schéma

Le schéma doit respecter un certain nombre de prérequis avant de pouvoir être intégré à schema.data.gouv.fr. Les exigences sont détaillées [ici](https://schema.data.gouv.fr/validation.html).

### Quelques exemples

* [le schéma des opérations d'aménagement du territoire](https://github.com/cnigfr/schema-operations-amenagement/blob/main/schema/operation-amenagement/schema_operation-amenagement.json),
* [le schéma friches](https://github.com/cnigfr/schema-friches/blob/main/schema.json),
* [le schéma des infrastructures de recharge pour véhicules électriques](https://github.com/etalab/schema-irve/blob/master/statique/schema-statique.json),
* [les schémas du standard sites économiques - Datapackage](https://schema.data.gouv.fr/cnigfr/schema-sites-economiques/).
* [les schémas des aménagements cyclables - JSON](https://schema.data.gouv.fr/schemas/etalab/schema-amenagements-cyclables/0.3.5/schema_amenagements_cyclables.json)
