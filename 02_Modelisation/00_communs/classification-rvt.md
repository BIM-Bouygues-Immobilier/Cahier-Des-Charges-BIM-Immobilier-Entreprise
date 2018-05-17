# Ajout des codes de classification

## Ajouter le fichier de classification dans Revit

Afin de faciliter la saisie des codes de classification dans Revit, il est nécéssaire d'ajouter l'ensemble des codes directement dans Revit.

Pour cela, ouvrir le menu "Paramètre de code d'assemblage" (1) dans Gérer -> Paramètres supplémentaires.

![Selection du fichier de codes de classification](/02_Modelisation/00_communs/images/classification/addClassificationFileInRevit.png)

Cliquer sur "Parcourir..." (2) et sélectionner le fichier texte contenant les codes de la classification. Ce fichier texte est disponible ici :

* En français: [Uniclass2015_fra](https://raw.githubusercontent.com/BIM-Bouygues-Immobilier/Cahier-Des-Charges-BIM-Immobilier-Entreprise/classification/02_Modelisation/00_communs/images/classification/Uniclass_fr_revit.txt)

Cliquer sur "Ok" (3) pour valider. Un message apparait indiquant que les codes de classifications sonnt correctmenet chargés. Cliquer sur "OK" (4) pour valider.

## Selectionner la classification du type

Chaque type de chaque famille Revit du modèle doit être associé à un code de classification. Pour selectionnner ce code, cliquer sur "Modifier le type" (1), puis sur "..." (2) dans le champs "Code d'assemblage".

![Ajout d'un code de classification](/02_Modelisation/00_communs/images/classification/AjoutClassificationType.png)

Selectionner dans la liste la code correspondant au type (3), puis cliquer sur "OK" (4).

Cliquer sur "OK" (5) pour terminer l'édition du type.

## Exporter la classification en IFC

Afin d'exporter de s'assurer que la classification selectionnée est correctement exportée en IFC, il est nécéssaire d'ajouter une configuration supplémentaire lors de l'export en IFC.

Ouvrir les paramètres de configuration de l'export IFC (1) puis (2) et sélectionner l'onglet "Property Sets" (3).

![Configuration de l'export en IFC](/02_Modelisation/00_communs/images/classification/ConfigurationExportIFC.png)

La propriété "Export user defined property sets" (4) doit être selectionnée et pointer vers un fichier texte indiquant à Revit comment exporter le code de classification décrit ci-dessus.

Ce fichier texte est disponible ici : [Fichier de configuration d'export](https://raw.githubusercontent.com/BIM-Bouygues-Immobilier/Cahier-Des-Charges-BIM-Immobilier-Entreprise/classification/02_Modelisation/00_communs/images/classification/export_classification_fra.txt)

Cliquer sur "OK" (5) pour valider cette configuration.