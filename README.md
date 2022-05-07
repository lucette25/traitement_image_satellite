# traitement_image_satellite

Pour exécuter ce notebook, il faut d'abord installer gdal.

Avant de commencer, vous devez avoir installé anaconda et jupyter notebook sur votre machine.

Puis exécuter les commandes suivantes dans le repertoire du notebook.

1-Créer un environnement conda 
conda create --name nom_env

2-Activer cet environnement
conda activate gdal

3-Intaller gdal
conda install -c conda-forge gdal

4-Installer ipykernel
conda install -c anaconda ipykernel

5- Ajouter ipykernel à l'environnement
python -m ipykernel install --use --name=nom_env