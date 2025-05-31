# CrossBar Plugin pour BakkesMod

## Description
CrossBar est un plugin pour BakkesMod qui affiche un overlay dans Rocket League pour compter le nombre de fois que vous touchez les poteaux ou la barre transversale. Il inclut :
- Un compteur de session et un compteur total.
- Un overlay personnalisable avec une position ajustable via un menu ImGui.
- Une icône (optionnelle) dans l'overlay.

## Prérequis
- BakkesMod installé (dernière version recommandée).
- Rocket League.

## Installation
1. Téléchargez le fichier `CrossBar.dll` et le dossier `CrossBar` (contenant `images/goal.png`).
2. Placez `CrossBar.dll` dans `%appdata%\bakkesmod\bakkesmod\plugins`.
3. Placez le dossier `CrossBar` dans `%appdata%\bakkesmod\bakkesmod\data\` (le chemin final doit être `%appdata%\bakkesmod\bakkesmod\data\CrossBar\images\goal.png`).
4. Lancez Rocket League. lancez bakkesmod , open plugin manager, cocher Crossbar plugin ou dasn la console bakkesmod taper "plugin load CrossBar "

## Utilisation
1. Ouvre le menu ImGui de BakkesMod (par défaut : F2).
2. Cherche l'onglet "CrossBar".
3. Ajuste la position de l'overlay avec les sliders "Position X" et "Position Y".
4. Active ou désactive l'overlay avec la case "Afficher overlay".
5. Réinitialise les compteurs avec les boutons "Réinitialiser le compteur session" et "Réinitialiser le compteur total".

## Notes
- Si l'image `goal.png` n'est pas trouvée, l'overlay s'affichera sans icône.
- Compatible avec Rocket League sur PC (Windows).

## Auteur
[Matt hoeub]