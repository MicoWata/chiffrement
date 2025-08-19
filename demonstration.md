# Démonstration

### Objectif : Rendre césar asymétrique

---

### César symétrique

---
Voici le contenu d'un document top secret

> banane

Voici notre clé

> 1

Avec cette clé, le contenu de notre document, une fois chiffré, devient

> cbobof

---

Le problème ici n'est pas de passer le message chiffré à mon collègue, mais de lui passer la clé.

(Démonstration)

---

### César asymétrique

---

Voici ma clé privée

> 1

Mon algorithme secret

> | chiffrement | déchiffrement |
> | ---         | ---           |
> | clé * 3     |       clé / 3 |

La clé publique

> 3

Le contenu de mon document reste le même

> cbobof

---

Je peux vous montrer la clé publique, mais vous manquez encore d'information pour déchiffrer le message.

---

Quelles sont les faiblesses de cet example ?

><details><summary></summary>L'algorithme est terriblement faible.</details>
><details><summary></summary>Si je connais l'algorithme, je peux trouver la clé privée.</details>
><details><summary></summary>Si je connais l'opération de déchiffrement, je peux l'inverser pour trouver la clé de chiffrement et obtenir la clé privée.</details>

