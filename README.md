# Mémoire de maîtrise sur l'extraction automatique de taxonomie à partir de plongements vectoriels de graphe


### Plan

🔴 Non commencé / 🟠 Commencé / 🟡 Avancé / 🟢 Fini

- Introduction
  - 🔴 Problématique
  - 🔴 Objectifs de recherche
  - 🟠 Plan du mémoire  
- Revue de littérature
  - 🔴 Web sémantique et logique descriptive
  - 🔴 Extraction automatique d'ontologie et de taxonomie
  - 🔴 Regroupement hiérarchique sur les graphes
- Chapitre 1 : plongements vectoriels de graphe de connaissance
  - 🟠 Introduction et motivation
  - 🟠 Modèles de plongement
    - Modèles algébriques : RESCAL et ses variantes
      - 🟡 RESCAL
      - 🟠 DistMult
      - 🟡 ComplEx
    - Modèles géométriques : l'exemple des modèles translationnels
      - 🟠 TransE
      - 🟠 TransH
      - 🟡 TransD
    - Autres modèles
      - 🟠 RDF2Vec
      - 🔴 GCN
      - 🔴 Modèles non-euclidiens
  - 🟡 Séparabilité des plongements
    - 🟡 Tâche proposée
      - 🟡 Description
      - 🟡 Distance lexicale
      - 🟡 Distance taxonomique
      - 🟡 Influence de la fréquence
    - Résultats et discussion
      - 🟠 Résultats
      - 🔴 Discussion
- Chapitre 2 : extraction de taxonomie non-expressive
  - Exposé du problème
    - Problème
    - Données
  - Méthode proposée
    - Regroupement hiérarchique
    - Association type-cluster
      - Hard Mapping
      - Soft Mapping
    - Construction de la taxonomie
  - Évaluation et discussion
    - Méthode d'évaluation
    - Résultats
    - Discussion
  - Hyperparamètres
    - Base du softmax
    - Seuil de probabilité
- Chapitre 3 : extraction de taxonomie expressive
  - Motivation et principes généraux
  - Méthode proposée
    - Regroupement hiérarchique récursif avec retirage
    - Extraction d'axiomes
  - Évaluation et discussion
    - Évaluation quantitative sur la tâche non-expressive
    - Évaluation qualitative des axiomes obtenus
- Discussion et conclusion
  - Synthèse des travaux
  - Limitations de la solution proposée
  - Améliorations futures
