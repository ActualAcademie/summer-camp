Bac à sable sympa : https://console-basthon.sct.pf/

# Découverte de Python — 25 exercices

L'objectif de cette journée est de découvrir progressivement les bases de Python et de la programmation backend

Nous allons travailler :

1. Les variables, `print()` et `input()`
2. Les conditions `if`
3. Les boucles `for`

---

# 1. Variables, `print()` et `input()`

## Exercice 1 — Hello Python

Affiche simplement le message :

Hello Python !

---

## Exercice 2 — Se présenter

Crée une variable `prenom` contenant ton prénom.

Affiche ensuite :

Bonjour Tom

en utilisant la variable.

Exemple :

```text
Bonjour Tom
````

---

## Exercice 3 — Prénom et âge

Crée deux variables :

* `prenom`
* `age`

Puis affiche une phrase comme :

```text
Je m'appelle Tom et j'ai 30 ans.
```

---

## Exercice 4 — Demander le prénom

Demande son prénom à l'utilisateur avec `input()`.

Puis affiche :

```text
Bonjour Tom !
```

---

## Exercice 5 — Demander prénom et ville

Demande à l'utilisateur :

* son prénom
* sa ville

Puis affiche une phrase comme :

```text
Tom habite à Paris.
```

---

## Exercice 6 — Quel âge l'année prochaine ?

Demande l'âge de l'utilisateur.

Affiche ensuite son âge l'année prochaine.

Exemple :

```text
Quel âge as-tu ? 25

L'année prochaine tu auras 26 ans.
```

Attention : `input()` retourne du texte.

Il faudra peut-être utiliser :

```python
int()
```

---

## Exercice 7 — Addition

Demande deux nombres à l'utilisateur.

Puis affiche leur somme.

Exemple :

```text
Premier nombre : 10
Deuxième nombre : 5

Résultat : 15
```

---

## Exercice 8 — Calculatrice simple

Demande deux nombres.

Affiche :

* leur addition
* leur soustraction
* leur multiplication

Exemple :

```text
Nombre 1 : 10
Nombre 2 : 4

Addition : 14
Soustraction : 6
Multiplication : 40
```

---

## Exercice 9 — Prix total

Demande :

* le prix d'un produit
* la quantité achetée

Calcule le prix total.

Exemple :

```text
Prix : 4
Quantité : 3

Prix total : 12 €
```

---

## Exercice 10 — Convertisseur minutes

Demande une durée en minutes.

Convertis cette durée en heures et minutes.

Exemple :

```text
Nombre de minutes : 135

2 heure(s) et 15 minute(s)
```

Indice :

```python
//
%
```

---

# 2. Les conditions `if`

## Exercice 11 — Majeur ou mineur

Demande l'âge de l'utilisateur.

Affiche :

```text
Tu es majeur.
```

si l'utilisateur a au moins 18 ans.

Sinon affiche :

```text
Tu es mineur.
```

---

## Exercice 12 — Positif ou négatif

Demande un nombre.

Indique s'il est :

* positif
* négatif
* égal à zéro

---

## Exercice 13 — Pair ou impair

Demande un nombre.

Indique s'il est pair ou impair.

Exemple :

```text
Nombre : 12

12 est pair.
```

Indice :

```python
%
```

---

## Exercice 14 — Mot de passe

Demande un mot de passe.

Le mot de passe attendu est :

```text
python123
```

Si le mot de passe est correct :

```text
Accès autorisé
```

Sinon :

```text
Accès refusé
```

---

## Exercice 15 — Le plus grand

Demande deux nombres.

Affiche le plus grand.

Exemple :

```text
Nombre 1 : 12
Nombre 2 : 25

Le plus grand nombre est 25.
```

---

## Exercice 16 — Note d'un étudiant

Demande une note sur 20.

Affiche :

* moins de 10 → `Échec`
* entre 10 et 11 → `Passable`
* entre 12 et 13 → `Assez bien`
* entre 14 et 15 → `Bien`
* 16 ou plus → `Très bien`

---

## Exercice 17 — Tarif cinéma

Demande l'âge d'une personne.

Le tarif est :

* moins de 12 ans → 5 €
* de 12 à 17 ans → 7 €
* 18 ans et plus → 10 €

Affiche le prix du billet.

---

## Exercice 18 — Feu tricolore

Demande une couleur :

```text
rouge
orange
vert
```

Affiche :

* rouge → `Stop`
* orange → `Ralentir`
* vert → `Avancer`

Si la couleur n'existe pas :

```text
Couleur inconnue
```

---

## Exercice 19 — Livraison gratuite

Demande le montant d'une commande.

Si le montant est supérieur ou égal à 50 € :

```text
Livraison gratuite
```

Sinon affiche :

```text
Livraison : 4.99 €
```

---

## Exercice 20 — Mini calculatrice

Demande :

* un premier nombre
* une opération : `+`, `-`, `*` ou `/`
* un deuxième nombre

Effectue ensuite le calcul.

Exemple :

```text
Nombre 1 : 10
Opération : *
Nombre 2 : 5

Résultat : 50
```

Bonus : empêcher une division par zéro.

---

# 3. Les boucles `for`

## Exercice 21 — Compter jusqu'à 10

Utilise une boucle `for` pour afficher les nombres de 1 à 10.

Résultat :

```text
1
2
3
4
5
6
7
8
9
10
```

---

## Exercice 22 — Compte à rebours

Affiche :

```text
10
9
8
7
6
5
4
3
2
1
Décollage !
```

---

## Exercice 23 — Les nombres pairs

Affiche tous les nombres pairs entre 0 et 20.

Résultat :

```text
0
2
4
6
8
10
12
14
16
18
20
```

---

## Exercice 24 — Table de multiplication

Demande un nombre.

Affiche sa table de multiplication de 1 à 10.

Exemple avec 5 :

```text
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
...
5 x 10 = 50
```

---

## Exercice 25 — Somme de 1 à 100

Utilise une boucle pour calculer :

```text
1 + 2 + 3 + ... + 100
```

Puis affiche le résultat.

---