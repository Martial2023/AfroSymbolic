# AfroSymbolic

## Présentation

AfroSymbolic est un projet d'exploration et de traitement de données
audio-visuelles consacré à des enregistrements musicaux et culturels
africains. Le projet prépare les métadonnées des vidéos, extrait et analyse
les pistes audio, puis organise les résultats pour faciliter l'étude des
caractéristiques sonores et symboliques.

## Organisation

- `data/metadata/` contient les métadonnées des enregistrements.
- `data/processed/` contient les données produites par les traitements.
- `notebooks/` contient les étapes d'exploration, de traitement audio et le
  pipeline général.
- `img/` contient les illustrations du projet.
- `requirements.txt` liste les dépendances Python.

Les dossiers `data/raw/audio/` et `data/raw/video/` ne sont pas versionnés
car les fichiers multimédias sont trop volumineux. Le dossier `.venv/`
ainsi que la configuration locale de VS Code (`.vscode/`) sont également
exclus du dépôt.

## Utilisation

1. Créer un environnement virtuel Python.
2. Installer les dépendances avec `pip install -r requirements.txt`.
3. Ouvrir les notebooks dans l'ordre souhaité, en commençant par
   `01_data_exploration.ipynb`.
