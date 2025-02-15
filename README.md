# GANDHIJS2425

## Exercices JavaScript - Les Bases

### Exercice 1: 
- Créez une variable 'age' avec var
- Créez une variable 'nom' avec let
- Créez une constante 'PAYS' 
- Affichez-les dans la console

### Exercice 2
Déclarez trois variables dans le même bloc de code :
- Une constante `AGE_MINIMUM` égale à 18
- Une variable `age` égale à 25
- Une variable `message` sans valeur initiale
Affichez les valeurs dans la console

### Exercice 3
Créez une variable `score` sans lui assigner de valeur.
Puis, à la ligne suivante, assignez-lui la valeur 10.
Enfin, augmentez le score de 5 points.
Affichez les valeurs dans la console.

### Exercice 4
Déclarez une constante `PI` avec la valeur 3.14. Affichez la valeur dans la console.
Essayez ensuite de modifier sa valeur. Que se passe-t-il ?

### Exercice 5
Déclarez une variable `nomUtilisateur` qui peut être modifiée, avec la valeur initiale "Alice".Affichez la valeur dans la console.
Puis modifiez sa valeur pour "Bob", reaffichez la valeur dans la console.


### Exercice 6: Manipulation de Chaînes
- Créez une variable 'prenom' et 'nom'
- Concatenez-les avec un espace entre
- Mettez le résultat en majuscules
- Affichez le nombre de caractères

### Exercice 7: 
Creer une variable 'presentation' qui prend la valeur 'Je suis Gandhiste'
- Diviser le contenu en caractere affecter à une variable 'presentationDiviser' et afficher.
- Renverser le contenu de 'presentationDiviser' joigner et afficher 

### Exercice 8: Calculs de Base
- Créez deux variables numériques
- Effectuez les opérations: +, -, *, /
- Calculez le reste de leur division
- Incrémentez la première variable

### Exercice 6: Tests Logiques
- Créez deux variables booléennes
- Testez AND (&&) entre elles
- Testez OR (||) entre elles
- Inversez (!) le résultat

### Exercice : Comparaisons de Valeurs
- Comparez deux nombres avec ==
- Comparez deux chaînes avec ===
- Testez une inégalité avec !=
- Vérifiez si un nombre est >= à un autre

### Exercice : Structure Conditionnelle Simple
- Créez une variable 'age'
- Si age >= 18, affichez "Majeur"
- Sinon affichez "Mineur"
- Ajoutez une condition pour age >= 65

### Exercice : Boucle Basique
- Créez une boucle qui compte de 1 à 5
- Affichez chaque nombre
- Arrêtez la boucle si nombre = 3
- Utilisez for et while

### Exercice : Variables et Conversions
- Créez une variable avec un nombre en texte
- Convertissez-la en nombre
- Ajoutez 10 au résultat
- Convertissez le résultat en texte

### Exercice : Manipulation de Texte
- Créez une phrase avec des espaces
- Enlevez les espaces au début et à la fin
- Remplacez un mot par un autre
- Vérifiez si la phrase contient un mot

### Exercice : Calculatrice Simple
- Créez 2 variables numériques
- Créez une variable operation (+,-,*,/)
- Faites le calcul selon l'opération
- Affichez le résultat

### Exercice : Validation de Données
- Créez une variable email
- Vérifiez si elle contient @
- Vérifiez si elle se termine par .com
- Affichez si l'email est valide

### Exercice : Boucle avec Condition
- Créez une boucle de 1 à 10
- Affichez "pair" si le nombre est pair
- Affichez "impair" pour les autres
- Utilisez l'opérateur modulo (%)

### Exercice : Manipulation de Variables
- Créez une variable score = 0
- Incrémentez-la de 5 si une condition est vraie
- Décrémentez-la de 2 si une autre condition est vraie
- Affichez le score final

### Exercice : Structure Conditionnelle Complexe
- Créez variables jour et heure
- Si jour = "samedi" ou "dimanche" → "Weekend"
- Si heure < 9 ou heure > 17 → "Fermé"
- Sinon → "Ouvert"

  
---------------------------------------------------------------------------------------------

# Le Gestionnaire de Notes

## Contexte
Vous développez un système de gestion de notes pour un établissement scolaire.

## Phase 1 - Structure Initiale
Créez une fonction `calculerMoyenne` qui :
- Prend en paramètres un nom d'étudiant de MIAGE L1 et ses 3 notes dans les 3 matieres
- Calcule la moyenne
- Retourne un message formaté avec le nom, les notes et la moyenne
L'établissement doit maintenant gérer :
- Pour les étudiants de MIAGE L2 qui ont 4 matieres
- Pour les étudiants de MIAGE L3 qui ont 5 matieres
- Pour les étudiants de MIAGE L4 qui ont 6 matieres
Il y'a une possibilité d'etendre ce programme pour les autres departements dont le nombre de matieres varie aussi.

### Exercice 1 : Somme des Carrés
Écrivez une fonction `sumOfSquares` qui prend un nombre variable d'arguments et retourne la somme de leurs carrés.

### Exercice : Concaténation de Chaînes
Écrivez une fonction `concatenateStrings` qui prend un nombre variable de chaînes de caractères et les concatène en une seule chaîne, séparées par un espace.


### Exercice : Filtrage des Nombres Pairs et Impairs
Écrivez une fonction `filterEvenAndOdd` qui prend un nombre variable d'arguments et retourne un objet contenant deux tableaux :

- `even` : les nombres pairs.
- `odd` : les nombres impairs.

=========================================================== Object, Contructeur, Class ==================================

# Exercice 1 : Objet Littéral

## Énoncé
Créez un objet littéral `voiture` avec les propriétés suivantes :

- `marque` (chaîne de caractères),
- `modele` (chaîne de caractères),
- `annee` (nombre).

Ajoutez une méthode publique `afficherDetails` qui affiche dans la console les informations de la voiture sous la forme :

> "Cette voiture est une [marque] [modele] de l'année [année]."

Ensuite, créez une propriété privée `_kilometrage` initialisée à 0 et ajoutez une méthode publique `ajouterKilometres(km)` qui incrémente le kilométrage de la voiture. Ajoutez également une méthode publique `obtenirKilometrage` pour afficher le kilométrage actuel.

---

# Exercice 2 : Constructeur et Prototype

## Énoncé
Créez une fonction constructeur `Livre` qui prend comme arguments :

- `titre` (chaîne de caractères),
- `auteur` (chaîne de caractères),
- `pages` (nombre).

Ajoutez une méthode au prototype de `Livre` appelée `afficherResume` qui affiche dans la console :

> "Le livre '[titre]' écrit par [auteur] contient [pages] pages."

Ensuite, créez deux instances de `Livre` et appelez la méthode `afficherResume` pour chacune d'elles.

---

# Exercice 3 : Classe avec Propriétés/Méthodes Privées

## Énoncé
Créez une classe `CompteBancaire` avec les éléments suivants :

- Une propriété privée `#solde` initialisée à 0,
- Une méthode privée `#verifierSolde` qui vérifie si le solde est positif ou nul,
- Une méthode publique `depot(montant)` qui ajoute un montant au solde,
- Une méthode publique `retrait(montant)` qui retire un montant du solde (vérifie que le solde est suffisant avant de faire le retrait),
- Une méthode publique `afficherSolde` qui affiche le solde actuel.

Testez votre classe en créant une instance et en effectuant des dépôts et retraits.

---

# Exercice 4 : Héritage et Encapsulation

## Énoncé
Créez une classe parente `Animal` avec les éléments suivants :

- Une propriété privée `#nom`,
- Une méthode publique `nourrir()` qui affiche :
  
  > "L'animal [nom] a été nourri."
  
Puis, créez une classe enfant `Chien` qui hérite de `Animal` et ajoute :

- Une méthode publique `aboyer()` qui affiche :
  
  > "Woof ! Je suis [nom]."
  
Enfin, testez votre code en créant une instance de `Chien`, en l'alimentant et en le faisant aboyer.


## PROJETS
### Plateforme de messagerie instantanéen (Bouba - G1)
### Plateforme multijoueur de jeux de dé (Oussou Bobo BARRY G3)
### Application de Transfert FTP (Alpha Oumar - G2)
