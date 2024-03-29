Unity Version : 2022.3.20
Sujet : Evaluation
Cours concerné : Développement
Date : 29 mars 2024

Configuration du projet :

Etape 1 : Récupérer le projet sur votre ordinateur dans un dossier que vous supprimerez à l'étape 5 : git clone https://github.com/YohanIsalyx/OXO_Evaluation_AutoFire.git
Etape 2 : Créer un repository public sur votre Github. Vous l'appelerez PrenomNom_AutoFire.
Etape 3 : Cloner votre repository sur votre ordinateur dans un autre dossier appelé PrenomNom_AutoFire que vous aurez créé préalablement.
Etape 4 : Déplacer les dossiers "Assets", "Packages", "Projects Settings". Et les fichiers ".gitignore" et "readme.md" dans le dossier de votre repository.
Etape 5 : Supprimer le premier dossier, il ne vous sera plus utile.
Etape 6 : Ouvrez le projet avec Unity Hub. /!\ Unity pourrait vous demander de switch la version unity utilisée si vous n'avez pas la 2022.3.20. Acceptez le.
Etape 7 : Quand votre projet sera ouvert. Allez dans le dossier scene, et ouvrez la scene : Evaluation
Etape 8 : ENJOY !



Objectifs principaux :

1. Déplacement du personnage en ZQSD pour lui permettre de se déplacer librement. Le déplacement par le transform est autorisé.
2. Lorsque vous passer sur le "Declenchor", vous devez l'activer. Celui passe au vert, s'enfonce légèrement dans le sol (-0.1 sur l'axe y).
3. La porte s'ouvre.
4. Lorsque vous quittez le "Declenchor", celui revient à son positionnement initial et redevient rouge. (n'oubliez pas de le remonter).
5. Après un temps de x secondes, la porte se referme.
6. Permettez à votre joueur de sauter.
7. Faites en sorte que la caméra suive le joueur (via code, et non via la hiérarchie en mettant votre caméra enfant du player).

Objectifs secondaires :
1. Réalisez un petit effet sonore ou un VFX lorsque vous activez le "Declenchor" et lorsqu'il se désactive / Porte qui s'ouvre et se ferme.
2. Réalisez la rotation de la caméra via la souris. N'oubliez pas de clamp les valeurs de haut-bas (axe X).
3. Utilisez les interfaces pour améliorer votre code et sa modularité.
4. Ouvrez et fermez votre porte de manière "Smooth".



Rendu :

1. Lorsque votre projet est terminé, vous devez push le projet sur le github.
2. Créez un fichier NomPrenom.txt dans lequel vous inscrirez le lien vers votre repository public.
3. Mettez ce fichier NomPrenom.txt dans le dossier "Evaluation Mars" dans le drive, partie Développement.
4. Ne modifiez plus votre rendu, ou créez une branche parallèle si vous souhaitez le continuer par la suite. Ceci évitera tout problème de date pour la correction.