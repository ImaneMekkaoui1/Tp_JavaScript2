# TD n°2 — Introduction à JavaScript (Évènements)

**Établissement :** École Normale Supérieure de l’Enseignement Technique de Mohammedia
**Master :** SDIA
**Module :** Technologies du Web & Web Sémantique

---

# Objectif du TP

L'objectif de ce TP est de pratiquer **JavaScript et la gestion des évènements** dans une page web.
Les exercices consistent à manipuler les éléments HTML et à exécuter des actions lorsque l'utilisateur clique sur des boutons.

Les fonctionnalités sont réalisées en **HTML, CSS et JavaScript pur (Vanilla JS)**.

---

# Exercices réalisés

## Exercice 1 : Permutation

Cet exercice consiste à créer un formulaire contenant :

* Deux zones de texte
* Un bouton *Permuter*

Lorsque l'utilisateur clique sur le bouton, les valeurs des deux champs sont échangées.

### Principe

1. Récupérer les valeurs des deux champs
2. Utiliser une variable temporaire
3. Permuter les valeurs

---

## Exercice 2 : Calculatrice simple

Cet exercice consiste à créer une calculatrice permettant d'effectuer les opérations de base :

* Addition (+)
* Soustraction (-)
* Multiplication (*)
* Division (/)

### Interface

La page contient :

* Deux champs pour saisir les nombres
* Un champ pour afficher le résultat
* Quatre boutons pour les opérations

### Fonctionnement

Lorsqu'un bouton est cliqué, l'opération correspondante est exécutée en JavaScript et le résultat est affiché.

---

## Exercice 3 : Calculateur d’IMC

Cet exercice consiste à développer un **calculateur d’Indice de Masse Corporelle (IMC)**.

### Formule utilisée

IMC = Poids / Taille²

où :

* Poids est exprimé en **kilogrammes**
* Taille est exprimée en **mètres**

### Fonctionnement

L'utilisateur saisit :

* son poids
* sa taille

Après avoir cliqué sur le bouton **Calculer**, le programme affiche :

* la valeur de l’IMC
* une interprétation du résultat

### Interprétation de l'IMC

| IMC         | Interprétation |
| ----------- | -------------- |
| < 18.5      | Maigreur       |
| 18.5 – 24.9 | Poids normal   |
| 25 – 29.9   | Surpoids       |
| ≥ 30        | Obésité        |

---

## Exercice 4 : Calculatrice scientifique

Cet exercice consiste à créer une **calculatrice scientifique** en utilisant :

* **JavaScript pur**
* **CSS Grid** pour organiser les boutons.

### Fonctionnalités implémentées

* Opérations mathématiques de base
* Fonctions trigonométriques :

  * sin
  * cos
  * tan
* Fonctions logarithmiques :

  * log
  * ln
* Puissance et carré :

  * x²
  * xʸ
* Racine carrée
* Constante π
* Pourcentage
* Effacement (CE)
* Activation (ON)

Les calculs sont effectués avec les fonctions mathématiques de JavaScript (`Math`).

---

# Technologies utilisées

* **HTML5**
* **CSS3**
* **JavaScript**

---

# Structure du projet

```
TD2_JS/
│
├── exercice1.html
├── exercice2.html
├── exercice3_imc.html
├── exercice4_calculatrice.html
│
└── README.md
```

---

# Auteur

Étudiante : **Imane Mekkaoui**
Master **SDIA**

---

# Conclusion

Ce TP a permis de :

* comprendre la gestion des **évènements JavaScript**
* manipuler le **DOM**
* créer des interfaces interactives
* utiliser les **fonctions mathématiques de JavaScript**

Ces exercices constituent une première étape vers le développement d'applications web interactives.
