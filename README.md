# The Great War Redux FR
> Dépôt du mod de traduction française du mod [The Great War Redux](https://steamcommunity.com/sharedfiles/filedetails/?id=1946557392)

## Tester le mod
- Clonez ou téléchargez le dépôt
- Double-cliquez sur create_symbolic_link.bat. Cela va ouvrir une console, lisez attentivement les logs.

Si vous avez une erreur du style *ERROR: HoI4 mod directory not found. Searched repertory : C:\XXX\Documents\Paradox Interactive\Hearts of Iron IV\mod*,
ouvrez le fichier create_symbolic_link.bat avec un éditeur de texte et remplacez %HOMEDRIVE%%HOMEPATH% par l'emplacement de votre dossier de Documents (par exemple D:).

## Mise à jour des fichiers source
Utiliser le script python update_english.py

Exemple : 
python update_english.py D:\Programmes\Steam\steamapps\workshop\content\394360\1946557392 The_Great_War_Redux_FR

## Mise à jour des fichiers destination
Après mise à jour des fichiers source, utilisez le script [add_missing_lines.py du projet Paradox_localization_utils](https://github.com/NicolasGrosjean/Paradox_localization_utils#for-euiv-hoi4-or-stellaris). 
