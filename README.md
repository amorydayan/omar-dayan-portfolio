# Portfolio Omar Dayan

Ce dossier contient le site portfolio statique construit à partir des projets et des fichiers réels disponibles dans le dossier source.

## Structure du site

- index.html : page principale du portfolio
- style.css : styles de la charte visuelle
- script.js : gestion de la lightbox et interactions simples
- assets/images : images sélectionnées pour les projets
- assets/videos : vidéos HTML5 locales
- assets/documents : documents à publier (CV, etc.)

## Prévisualisation locale

Ouvrez simplement le fichier suivant dans un navigateur :

- website/index.html

Le site est conçu pour fonctionner sans dépendance Node.js ni framework.

## Remplacer une image

1. Placez la nouvelle image dans le dossier correspondant.
2. Mettez à jour le chemin dans le fichier index.html.
3. Vérifiez le rendu sur desktop et mobile.

## Remplacer une vidéo

1. Ajoutez la vidéo dans assets/videos/
2. Vérifiez le format MP4.
3. Mettez à jour le chemin du fichier source dans la balise video.

## Modifier le texte d’un projet

Les sections de texte sont directement dans index.html. Il suffit d’éditer les paragraphes et les listes correspondantes.

## Ajouter un autre projet

1. Créez une section dans index.html.
2. Ajoutez une image dans assets/images.
3. Mettez à jour la grille de projets si nécessaire.
4. Ajustez les styles CSS si la mise en page change.

## Remplacer le CV

1. Placez le document PDF dans assets/documents
2. Renommez-le selon la convention souhaitée
3. Mettez à jour le lien dans le bouton CV

## Fonctionnement de la lightbox

Les images des galeries sont cliquables. Un clic ouvre une vue agrandie. La lightbox se ferme avec :

- bouton de fermeture
- touche ESC
- clic en dehors de l’image

## Préparation avant publication

Avant de publier le site, il faut vérifier :

- que les images et vidéos sont compatibles
- que le CV est le bon document
- que les images Orange n’exposent pas de contenus internes sensibles
- que les liens LinkedIn et CV sont corrects

## Fichiers sûrs à publier

Les fichiers directement publiés dans le site sont limités aux éléments nécessaires à la présentation professionnelle :

- images de projets sélectionnées
- vidéos utiles et validées
- CV général validé
- contenu texte du portfolio

Les dossiers source complets comme les rapports PDF d’origine et les archives ZIP ne doivent pas être publiés sur le site public.

## Sources utilisées

- Orange Innovation : dossier stage_orange_2026, données LiDAR / ROS2 / SLAM, images et vidéo de démonstration
- IEMN / FabLab : stage de mesure de force intégré aux vêtements, capteurs piézoélectriques, électronique embarquée et acquisition analogique
- CODESYS : dossier PLC_Projet, image de feux et vidéos de simulation
- PLP : dossier Projet_PLP, démonstrateur et images de carte électronique / PCB
- SolidWorks : projet public de modélisation 3D et conception mécanique
