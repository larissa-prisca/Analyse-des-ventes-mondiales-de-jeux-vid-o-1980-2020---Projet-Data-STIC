#  Analyse des ventes mondiales de jeux vidéo (1980–2020)

##  Introduction
Ce projet analyse un dataset de **16 598 jeux vidéo** vendus entre **1980 et 2020**, provenant de la plateforme **Kaggle**.  
L’objectif est d’explorer les tendances du marché du jeu vidéo à travers le temps, les régions, les genres et les plateformes, à l’aide de l’analyse de données et de la visualisation.

---

##  Objectifs du projet
- Identifier les jeux les plus vendus de l’histoire
- Comparer les performances des différentes régions du monde
- Analyser l’évolution du marché au fil du temps
- Comprendre les préférences des consommateurs par genre et par plateforme

---

##  Données analysées
- **16 598 jeux vidéo**
- **11 variables** (nom, plateforme, année, genre, éditeur, ventes)
- Ventes réparties en **4 régions** :
  - Amérique du Nord
  - Europe
  - Japon
  - Autres régions

---

##  Méthodologie

###  Outils utilisés
- Python 3.x
- Bibliothèques :
  - `pandas` (manipulation des données)
  - `matplotlib` et `seaborn` (visualisation)
- Environnement : **Google Colab**

###  Nettoyage des données
- Suppression des jeux sans année de sortie (**271 lignes**)
- Suppression des jeux avec **0 vente**
- Conversion de la colonne `Year` en format numérique
- **Dataset final : 16 327 jeux exploitables**

###  Analyses effectuées
- Statistiques descriptives (moyennes, totaux, distributions)
- Classements (Top 10 jeux, genres, plateformes)
- Analyses temporelles (évolution des ventes par année)
- Analyses géographiques (comparaison entre régions)
- Corrélations entre les ventes régionales

---

##  Résultats clés

###  Top 3 des jeux les plus vendus
1. **Wii Sports** – 82.74 millions
2. **Super Mario Bros.** – 40.24 millions
3. **Mario Kart Wii** – 35.82 millions

###  Répartition géographique des ventes
- Amérique du Nord : **49.2%**
- Europe : **27.3%**
- Japon : **14.5%**
- Autres régions : **9.0%**

### Tendances observées
- Pic historique des ventes en **2008** (génération Wii / PS3 / Xbox 360)
- Genre dominant : **Action** (20% du marché)
- Plateforme la plus vendue : **PlayStation 2**

##  Synthèse des principales découvertes

###  Jeux & genres
- *Wii Sports* est le jeu le plus vendu de l’histoire
- Les jeux d’Action dominent le marché mondial
- Nintendo place **6 jeux dans le Top 10**

### Régions
- L’Amérique du Nord domine le marché mondial (49.2%)
- Forte corrélation entre les ventes USA–Europe (**0.76**)
- Le Japon présente des préférences distinctes (RPG japonais)

### Plateformes
- **PS2** : plateforme avec le plus grand volume de ventes (**1 255M**)
- Nintendo domine en nombre de hits (Wii, DS, Game Boy)
- Sony domine en volume total de ventes

###  Évolution temporelle
- Apogée du marché en **2008–2009**
- Déclin progressif après 2010 (montée du mobile gaming)
- Période **2000–2010** considérée comme l’âge d’or du jeu vidéo physique

## Conclusion
Ce projet a permis d’analyser plus de **16 000 jeux vidéo sur 40 ans d’histoire**, mettant en évidence des tendances majeures du marché mondial du jeu vidéo.

### Points clés
- Le marché nord-américain domine historiquement
- Nintendo excelle sur les jeux grand public
- Le pic du marché a été atteint en 2008–2009
- Les préférences varient fortement selon les régions

###  Limites de l’étude
- Données arrêtées avant l’ère **Switch / PS5**
- Absence des ventes numériques et mobiles
- Pas d’informations sur les budgets de développement

###  Perspectives
- Analyse de l’impact des jeux free-to-play (Fortnite, Apex Legends)
- Comparaison ventes digitales vs physiques
- Corrélation entre budgets marketing et ventes

---

##  Annexes

###  Ventes par région
| Région | Ventes (M) | % |

| Amérique du Nord | 4 392.95 | 49.2% |
| Europe | 2 434.12 | 27.3% |
| Japon | 1 291.02 | 14.5% |
| Autres | 797.19 | 9.0% |
| **Total** | **8 915.28** | **100%** |

---

##  Source des données
- Dataset : **Kaggle – Video Game Sales**
- Code source : disponible dans ce repository


