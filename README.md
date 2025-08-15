<p align="center">
    <img src="https://github.com/user-attachments/assets/2ea1a349-ca78-45fa-b429-94fbbeada0bc" alt="Phoenix’s 360-degree panorama of its landing site." height="300">
    <br> Crédit d'image | Image credit: NASA JPL
</p>

<p align="center">
    <a href="#stars">
        <img alt="Étoiles sur GitHub | GitHub Repo stars" src="https://img.shields.io/github/stars/asc-csa/MET-Tutorial">
    </a>
    <a href="#watchers">
        <img alt="Spectateurs sur Github | GitHub watchers" src="https://img.shields.io/github/watchers/asc-csa/MET-Tutorial">
    </a>
    <a href="https://github.com/asc-csa/MET-Tutorial/commits/main">
        <img alt="Dernier commit sur GitHub | GitHub last commit" src="https://img.shields.io/github/last-commit/asc-csa/MET-Tutorial">
    </a>
    <a href="https://github.com/asc-csa/MET-Tutorial/graphs/contributors">
        <img alt="Contributeurs sur GitHub | GitHub contributors" src="https://img.shields.io/github/contributors/asc-csa/MET-Tutorial">
    </a>
    <a href="https://twitter.com/intent/follow?screen_name=csa_asc">
        <img alt="Suivre sur Twitter | Twitter Follow" src="https://img.shields.io/twitter/follow/csa_asc?style=social">
    </a>
</p>

# Données Phoenix MET - Tutoriel

---

<h3 align="center">
  <a href="#titre-du-projet">Français</a> |
  <a href="#project-title">English (follows)</a>
</h3>

---

<a id="titre-du-projet"></a>

## À propos

**Données Phoenix MET - Tutoriel** est un tutoriel qui guide les utilisateurs dans l'exploration et l'analyse des données météorologiques collectées par l'instrument MET de l'atterrisseur Phoenix sur Mars. Il couvre :

- Accès et manipulation des données météorologiques martiennes
- Analyse des conditions atmosphériques de l'Arctique martien
- Visualisation des données temporelles et saisonnières
- Traitement de données de la première station météo canadienne sur Mars

L'atterrisseur Phoenix a atterri sur Mars en 2008 où il est resté pendant 5 mois dans le but de mieux comprendre la géomorphologie, le climat et l'habitabilité de l'Arctique martien. Il s'agissait de la première mission à explorer le niveau du sol de la région arctique de Mars, et la première fois que le Canada se trouvait à la surface de Mars. La composante canadienne de l'atterrisseur Phoenix était l'instrument MET, utilisé pour suivre les conditions météorologiques quotidiennes et saisonnières et a été le premier à détecter de la neige sur Mars.

Vous pouvez en apprendre davantage sur la mission générale à https://www.asc-csa.gc.ca/eng/astronomy/mars/phoenix/

*Ce tutoriel est fourni à des fins pédagogiques et expérimentales.*

## Prérequis

- Python 3.11.3 ou plus récent
- Jupyter Notebook ou Jupyter Lab
- Bibliothèques Python : pandas, numpy, matplotlib, seaborn
- Connexion Internet (pour le téléchargement des données Phoenix)
- Espace de stockage pour les fichiers de données météorologiques

## Démarrage rapide

1. 📦 **Cloner le dépôt**
   ```bash
   git clone https://github.com/asc-csa/MET-Tutorial.git
   cd MET-Tutorial
   ```
2. 🐍 **Créer un environnement**
   ```bash
   # Avec virtualenv
   python -m venv env
   source env/bin/activate

   # Ou avec conda
   conda create -n phoenix_env python=3.11.3
   conda activate phoenix_env
   ```
3. 📥 **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Lancer le tutoriel**
   ```bash
   jupyter notebook
   ```

> **Remarque :** Ce tutoriel utilise des données météorologiques réelles de la mission Phoenix Mars.

## Astuces & Conseils

- **Données Phoenix :** Les données couvrent 5 mois d'observations météorologiques martiennes
- **Analyse temporelle :** Explorez les variations quotidiennes et saisonnières des conditions
- **Première détection :** Phoenix a été le premier à détecter de la neige sur Mars
- **Visualisation :** Les graphiques temporels révèlent des patterns météorologiques uniques

## Licence

Ce projet est sous une licence MIT modifiée – voir le fichier [LICENSE](https://github.com/asc-csa/MET-Tutorial/blob/main/LICENSE.txt) pour plus de détails.

---

<h3 align="center">
  <a href="#project-title">English </a> |
  <a href="#titre-du-projet">Français (précède)</a>
</h3>

---

<a id="project-title"></a>
# Phoenix MET Data Tutorial

## About

**Phoenix MET Data Tutorial** is a tutorial that guides users through exploring and analyzing meteorological data collected by the MET instrument of the Phoenix Lander on Mars. It covers:

- Accessing and manipulating Martian meteorological data
- Analyzing atmospheric conditions of the Martian Arctic
- Visualizing temporal and seasonal data
- Processing data from Canada's first weather station on Mars

The Phoenix Lander arrived on Mars in 2008 where it stayed for 5 months with the goal of better understanding the geomorphology, climate, and habitability of the Martian arctic. It was the first mission to explore the ground level of the Arctic region of Mars, and Canada's first time on the Martian surface. The Canadian component of the Phoenix Lander was the MET Instrument, used to track daily & seasonal weather patterns and was the first to detect snow on Mars.

You can learn more about the general mission at https://www.asc-csa.gc.ca/eng/astronomy/mars/phoenix/

*This tutorial is provided for educational and experimental purposes.*

## Prerequisites

- Python 3.11.3 or newer
- Jupyter Notebook or Jupyter Lab
- Python libraries: pandas, numpy, matplotlib, seaborn
- Internet connection (for Phoenix data download)
- Storage space for meteorological data files

## Quick Start

1. 📦 **Clone the repo**
   ```bash
   git clone https://github.com/asc-csa/MET-Tutorial.git
   cd MET-Tutorial
   ```
2. 🐍 **Create environment**
   ```bash
   # Using virtualenv
   python -m venv env
   source env/bin/activate

   # Or using conda
   conda create -n phoenix_env python=3.11.3
   conda activate phoenix_env
   ```
3. 📥 **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Run the tutorial**
   ```bash
   jupyter notebook
   ```

> **Note:** This tutorial uses real meteorological data from the Phoenix Mars mission.

## Tips & Tricks

- **Phoenix Data:** Data covers 5 months of Martian meteorological observations
- **Temporal Analysis:** Explore daily and seasonal variations in conditions
- **First Detection:** Phoenix was the first to detect snow on Mars
- **Visualization:** Time-series plots reveal unique weather patterns

## License

This project is licensed under a modified MIT license - see the [LICENSE](https://github.com/asc-csa/MET-Tutorial/blob/main/LICENSE.txt) file for details.
