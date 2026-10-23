# Analyse et Simulation de la Marche Aléatoire de l'Éléphant

Projet de recherche réalisé dans le cadre de la Licence de Mathématiques de l'Université de Toulouse (Mars 2025).

## Auteurs
* **Héléna CROS**
* **Sylvie HO**
* **Solène LORY**
* **Éloïse SALLET**

---

## Présentation du Projet

La marche aléatoire est un modèle probabiliste fondamental utilisé pour décrire des phénomènes physiques, économiques et biologiques. Alors que la marche classique repose sur des pas indépendants et équiprobables, certains processus naturels présentent une dépendance temporelle où les choix passés influencent les déplacements futurs.

Ce projet étudie la **Marche Aléatoire de l'Éléphant** (*Elephant Random Walk*), une extension non-markovienne introduite par Schutz et Trimper (2004). Ce modèle incorpore une mémoire infinie du passé : à chaque étape, l'agent (« l'éléphant ») sélectionne uniformément un pas antérieur dans son histoire et le reproduit (ou l'inverse) avec une probabilité fixée $p$.

### Objectifs principaux :
1. **Étude du modèle sans mémoire (sur $\mathbb{Z}$)** : Analyse théorique de l'irréductibilité, de la récurrence (temps de premier retour en 0) et des déviations par l'inégalité de Bienaymé-Tchebychev.
2. **Formalisation de la marche de l'éléphant** : Modélisation des probabilités conditionnelles complexes sous l'influence de l'historique complet (paramètres $p$ et $q$).
3. **Analyse de la mémoire initiale** : Étude explicite de l'impact des premiers pas et preuve par récurrence de la formule de décomposition des probabilités conjointes.
4. **Simulations numériques** : Implémentation d'expérimentations Monte-Carlo sous Python pour illustrer le comportement asymptotique et la transition de phase selon les valeurs de $p$.

---

## Stack Technique & Dépendances

Les simulations et visualisations ont été développées en **Python 3.x**.

* **Calcul scientifique** : `numpy`
* **Visualisation graphique** : `matplotlib`
* **Génération d'aléatoire** : `random`
