# Boavizta-Toolkit

Voici quelques outils/livrables concernant l'empreinte carbone des équipements numériques, réalisés lors de mon stage de Master 1 chez Leroy Merlin France (2022) :
 
1. **Fiche_Process.txt** : Fichier texte conçu pour les collaborateurs d'une entreprise devant commander/comparer du nouveau matériel pour un projet, leur expliquant la méthode à employer pour parvenir rapidement à trouver l'empreinte carbone d'un/plusieurs équipement(s) précis.

2. **Recherche_Rapide.ipynb** : *Google Colaboratory Notebook* (Python) conçu pour une recherche rapide dans la base de données open source Boavizta sur l'empreinte carbone des équipements.
https://github.com/Boavizta/environmental-footprint-data/blob/main/boavizta-data-us.csv

3. **GSheet.xslx** : *Google Sheet* avec script conçu pour comparer le poids carbone de multiples équipements à la fois. <br/><br/>
 ![image](https://user-images.githubusercontent.com/71394086/229110507-241022df-4558-4f2d-bd05-e9c64282539f.png) <br/><br/>
 Les étapes pour l'installation de l'outil sont un peu fastidieuses mais cela fonctionne :
   - Uploader la spreadsheet XLSX sur son google drive, puis l'ouvrir avec *Google Sheets*.
   - Dans *Google Sheets* enregistrer la spreadsheet en tant que *Google Sheet*, puis l'ouvrir avec *Google Sheets*.
   - Dans l'onglet "Affichage" de *Google Sheets*, cliquer sur "Feuilles masquées" > "Afficher data".
   - Aller tout en bas de la feuille "data" et ajouter 1000 lignes.
   - Dans l'onglet "Extensions" de *Google Sheets*, cliquer sur "Apps Script".
   - Dans *Apps Script*, supprimer tout le code de la fenêtre de code.
   - Copier le contenu du fichier **Gsheet_Script** de ce repo.
   - Dans *Apps Script*, coller le contenu et sauvegarder.
   - Enfin suivre les instructions dans la feuille "Tutoriel" de la *Google Sheet*.

4. **Extrait du dashboard conçu sur *Google Data Studio* : "IT Carbon Footprint"** <br/><br/>
![Capture d'écran 2023-03-31 131049](https://user-images.githubusercontent.com/71394086/229112855-7ee89b31-bf8a-4d39-9a52-456e599bf28e.png)
![Capture d'écran 2023-03-31 131023](https://user-images.githubusercontent.com/71394086/229105721-10ee1b47-083c-4b4a-ba64-f3ea20800986.png)
![Capture d'écran 2023-03-31 131120](https://user-images.githubusercontent.com/71394086/229105709-7bba8e89-90ef-48ed-844d-7c7edd4bff67.png)
![image](https://user-images.githubusercontent.com/71394086/229106802-ce80b745-16a7-4fee-a5e0-404fc85ef67b.png)

