# Analyse du Marché Steam : Déterminants du Succès et Typologie des Jeux

## Objectif du Projet
Ce projet vise à explorer et modéliser le marché des jeux vidéo sur la plateforme Steam. L'objectif est d'identifier les caractéristiques intrinsèques (genres, modèles économiques, fonctionnalités multijoueurs) qui favorisent le succès commercial, et de segmenter le catalogue en profils types pour mieux comprendre les dynamiques de l'industrie.

*Projet réalisé dans le cadre de la 4ème année au département GMM de l'INSA Toulouse.*

## Données
Le jeu de données comprend un large échantillon du catalogue Steam (nettoyé à ~120 000 jeux). Les variables incluent :
* **Quantitatives :** Prix, temps de jeu moyen/médian, nombre d'avis, scores Metacritic.
* **Qualitatives :** Genres, tags, fonctionnalités (Multijoueur, Co-op, Support manette, etc.), modèle économique.

## Méthodologie
L'analyse s'articule autour de plusieurs méthodes d'apprentissage non supervisé et supervisé :
1. **Analyse en Composantes Principales (ACP) :** Réduction de dimension sur les variables d'engagement et de notoriété.
2. **Clustering (K-Means) :** Segmentation du marché en 3 groupes distincts basés sur le plan factoriel de l'ACP.
3. **Analyse des Correspondances Multiples (ACM) :** Étude des associations entre les caractéristiques qualitatives (Genres vs Succès, Évolution temporelle).
4. **Régressions (OLS & Ridge) :** Évaluation de la robustesse des axes explicatifs du succès commercial.

## Résultats Principaux
L'analyse a permis de mettre en évidence une forte inégalité structurelle du marché, divisé en 3 segments :
* **La masse invisible :** L'écrasante majorité du catalogue, caractérisée par un engagement quasi nul.
* **Les succès commerciaux :** Des titres très rentables, souvent à prix intermédiaire, mais avec une rétention qui s'essouffle.
* **Les phénomènes d'addiction :** Une élite très restreinte cumulant audience massive et temps de jeu exceptionnel (souvent multijoueur/Free-to-Play).

---

## Structure du projet

└── Projet_ADD/
    ├── Oster_Paulien_Parnotte_Projet_ADD.ipynb  # Notebook principal contenant toutes les analyses (ACP, ACM, Clustering)
    ├── 2526-Projet.pdf                          # Consignes données pour ce projet
    └── README.md                                # Description du projet
       
---

## 👥 Authors

* **Eliott Oster**
* **Paulien-Camy Lucas**
* **Parnotte Léo**
