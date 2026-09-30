# Prototype de projet QGIS (29 mai 2026)

Le premier prototype de projet QGIS repose sur le modèle de données défini dans le [schéma](https://github.com/cnigfr/standard-accessibilite-espace-naturel/tree/master/schema) du projet de standard soumis à l'appel à commentaires du 18 mai au 30 juin 2026.

Il contient un cheminement à titre d'exemple : _Le Sentier didactique du Bois de la Fontaine_, à Tenneville en Belgique.
Pour cette raison, les fonds de plan nationaux IGN sont vides. Le projet QGIS intègre le fond de plan OSM.

En dehors de CHEMINEMENT les couches de données sont vides, et leur symbolisation n'a pas encore été traitée.

> [!WARNING]
> Attention : ce projet QGIS v2026-05 n'intègre pas les évolutions suite à l'appel à commentaires et n'est donc pas rigoureusement conforme au standard ACEN v2026-09
> 
> => utiliser le projet QGIS v2026-09 de David Amiaud

# Projet QGIS + QField ACEN (23 septembre 2026)

Ce projet est destiné à la collecte de données relatives à l'accessibilité des cheminements en espaces naturels à l'aide de l'application QField sur smartphone ou tablette Android.

Réalisé par David Amiaud, ce projet est conforme au standard CNIG ACEN v2026-09.

Avant de commencer, il est nécessaire :

- d'avoir installé QField sur le smartphone ou la tablette ;
- de disposer du **dossier compressé « ACEN_QFIELD_v2026_09 »** ;
- de disposer, si nécessaire, d'un ordinateur pour transférer le projet vers le smartphone ou la tablette.

## Installation du projet depuis un ordinateur

Cette méthode permet de transférer directement le **projet QField** depuis un ordinateur vers un smartphone ou une tablette Android.

Remarque : l'application QField doit être téléchargée en amont des étapes suivantes.

### Étape 1 – Connecter le terminal

Connectez le smartphone ou la tablette à l'ordinateur à l'aide d'un câble USB.

Si nécessaire, autorisez le transfert de fichiers sur le smartphone ou la tablette.

### Étape 2 – Copier le dossier du projet

Copier le dossier compressé « ACEN_QFIELD_v2026_09 » dans le répertoire QField correspondant aux projets importés.

Le chemin à suivre est généralement :

Android/data/ch.opengis.qfield/files/QField/Imported Projects

**Attention** : le nom du répertoire peut apparaître différemment selon la version d'Android ou de QField. Le dossier recherché est celui correspondant à **QField → Imported Projects**.

### Étape 3 – Décompresser l'archive

Une fois l'archive copiée dans **Imported Projects**, décompressez-la à cet emplacement.

Le dossier du projet doit alors apparaître sous la forme : **ACEN_v2026_09_qfield.**

## Ouvrir le projet dans QField

Après avoir transféré et décompressé le projet :

1. ouvrez **QField** ;
2. sélectionnez **« Projets locaux et jeux de données »** ;
3. accédez au répertoire **QField** ;
4. ouvrez **« Imported Projects »** ;
5. sélectionnez le dossier **« ACEN_v2026_09_qfield »** ;
6. ouvrez le projet.

Le projet est alors prêt à être utilisé pour la collecte de données sur le terrain.

## Installation directement depuis un smartphone ou une tablette Android

Il est également possible d'installer le projet directement depuis le smartphone ou la tablette, sans passer par un ordinateur.

Remarque : l'application QField doit être téléchargée en amont des étapes suivantes.

### Étape 1 – Télécharger l'archive

Téléchargez le fichier : **« ACEN_QFIELD_v2026_09 ».**

Sur le smartphone ou la tablette.

Le fichier est généralement enregistré dans le dossier **Téléchargements / Downloads**.

### Étape 2 – Décompresser l'archive

Ouvrez le fichier téléchargé.

Sur Android, le système propose généralement une option permettant **d'extraire les fichiers**.

Décompressez l'archive afin d'obtenir le dossier : **« ACEN_v2026_09_qfield ».**

### Étape 3 – Importer le projet dans QField

1. ouvrez **QField** ;
2. depuis la page d'accueil, sélectionnez **« Projets locaux et jeux de données »** ;
3. cliquez sur les **trois points verts** situés en bas à droite ;
4. sélectionnez **« Importer un projet à partir d'un dossier »** ;
5. recherchez le dossier **« ACEN_v2026_09_qfield »** dans le répertoire **Téléchargements / Downloads** ;
6. sélectionnez le dossier ;
7. cliquez sur **« Utiliser ce dossier »**.

Le projet est alors importé dans QField et peut être ouvert depuis **« Projets locaux et jeux de données »**.

## Installation sur iPhone / iPad

Sur iPhone ou iPad, le projet peut notamment être transféré à l'aide d'**AirDrop**.

### Étape 1 – Transférer le fichier

Transférez le dossier ou l'archive **« ACEN_QFIELD_v2026_09 »** vers l'iPhone ou l'iPad à l'aide d'AirDrop.

Lorsque cela est proposé, enregistrez le fichier dans le répertoire : **QField → Imported Projects.**

### Étape 2 – Décompresser l'archive

Si le fichier est transmis sous forme d'archive compressée, décompressez-le dans **Imported Projects**.

Vous devez obtenir le dossier : **« ACEN_v2026_09_qfield ».**

### Étape 3 – Ouvrir le projet

Ouvrez ensuite QField et accédez à :

**Projets locaux et jeux de données → QField → Imported Projects → ACEN_v2026_09_qfield**

Sélectionnez le projet pour commencer la collecte.

## Vérification avant utilisation sur le terrain

Avant de partir sur le terrain, il est recommandé de vérifier que :

- le projet **ACEN_v2026_09_qfield** s'ouvre correctement ;
- les fonds cartographiques et les couches nécessaires sont bien visibles ;
- la localisation GPS fonctionne ;
- il est possible de créer ou modifier une donnée ;
- les formulaires de saisie s'affichent correctement ;
- les données saisies sont bien enregistrées.

Il est également conseillé d'effectuer un **test de saisie avant la première campagne de terrain**, afin de vérifier le bon fonctionnement du projet sur le matériel utilisé.

## Organisation des fichiers

Le dossier transmis doit conserver sa structure interne.

**Ne pas supprimer, renommer ou déplacer les fichiers contenus dans le dossier du projet**, sauf consigne spécifique.

L'organisation attendue est la suivante : ACEN_QFIELD_v2026_09.

└── ACEN_v2026_09_qfield

├── projet QField

├── couches de données

├── formulaires

└── autres fichiers nécessaires au projet

La présence et le nom exact des fichiers peuvent varier selon la version du projet.

## En cas de difficulté

En cas de problème lors de l'installation ou de l'ouverture du projet, vérifier en priorité :

1. que **QField est correctement installé** ;
2. que l'archive a bien été **décompressée** ;
3. que le dossier **ACEN_v2026_09_qfield** contient bien l'ensemble des fichiers du projet ;
4. que le dossier a été placé/importé dans QField en utilisant la procédure décrite ci-dessus ;
5. que QField dispose des **autorisations nécessaires pour accéder aux fichiers et à la localisation** du terminal.

En cas de problème persistant, conserver le message d'erreur éventuel et ouvrir une issue sur le Github en précisant le **modèle du smartphone ou de la tablette**, ainsi que la **version d'Android/iOS et de QField**, afin de faciliter le diagnostic.
