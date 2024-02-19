# SF_RL_SOIA

## Prérequis
Pour lancer l'émulateur, il faut créer un fichier rom contenant le jeu Street Fighter II (https://www.planetemu.net/rom/sega-mega-drive/street-fighter-ii-special-champion-edition-usa-1?fbclid=IwAR3B4bNx3LZJEaAUyM0awdjYYe-fR-Hd_1I1WofG1njIrW0z6MZEK3ID1xI)

Pour lier le fichier rom à l'émulateur, il faut seulement ajouter une ligne de code :
```bash
python -m retro.import . # Run this from the roms folder
```

Ensuite, il faut importer différentes bibliothèques python :
```bash
! pip install gym==0.21.0  
```