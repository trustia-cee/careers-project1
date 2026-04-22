# Test technique - Trustia

## Exercice 1

Créer un programme Python qui affiche dans la console des blocs de texte encadrés comme dans l’exemple fourni. :

<img width="1045" height="276" alt="image" src="https://github.com/user-attachments/assets/e6ba23bf-da3e-4de0-9481-474417561397" />


### Contraintes

- La largeur maximale d’un bloc est de **100 caractères** et doit être facilement modifiable.
- Tout le texte doit être affiché **en minuscules**.
- Les blocs peuvent contenir **une ou plusieurs lignes**.
- Les bordures utilisent `-` pour les lignes et `|` pour les côtés.

### Organisation des données

- Toutes les phrases doivent être stockées dans un **dictionnaire**.
- Certaines phrases peuvent rester dans le dictionnaire **sans être affichées**.
- L’ordre d’affichage doit pouvoir être **facilement modifié**.

### Blocs à produire

#### Bloc 1

- Le code propre facilite la maintenance

#### Bloc 2

- Tester souvent évite beaucoup d erreurs
- Cette phrase ne doit pas s afficher

#### Bloc 3

- Cette phrase ne doit pas s afficher
- Un bon code doit rester simple et clair
- La simplicité améliore la qualité du code
- Refactoriser améliore la compréhension

### Règle importante

Les phrases suivantes **ne doivent pas apparaître dans la console**, même si elles sont dans le dictionnaire :

- "Cette phrase ne doit pas s afficher" (bloc 2)
- "Un bon code doit rester simple et clair" (bloc 3)

### Objectif

Le code doit permettre facilement :

- de modifier le texte
- de changer l’ordre des blocs
- d’ajouter ou supprimer des lignes
- de garder certaines phrases dans le dictionnaire sans les afficher

---

## Exercice 2

Créer une application web Django permettant de gérer des produits et de générer des factures. :contentReference[oaicite:1]{index=1}

### Contraintes

- Utiliser impérativement le framework **Django**
- Les produits doivent contenir :
  - id
  - nom
  - prix
  - date de péremption
- L’application doit permettre :
  - créer
  - modifier
  - supprimer
  - afficher des produits
- Les listes doivent utiliser un système de **pagination**

### Organisation des données

- Les produits sont stockés dans une **base de données**
- Une facture peut contenir **plusieurs produits**
- Chaque produit dans une facture peut avoir une **quantité**

### Fonctionnalités à produire

#### Gestion des produits

- Créer un produit
- Modifier un produit
- Supprimer un produit
- Afficher la liste des produits

#### Facturation

- Créer une facture
- Sélectionner des produits pour la facture
- Définir la quantité des produits

#### Page de détail d’une facture

- Liste des produits de la facture
- Nombre total de produits
- Total à payer

### Objectif

L’application doit permettre facilement :

- d’ajouter ou modifier des produits
- de créer des factures avec plusieurs produits
- de consulter le détail d’une facture
- de naviguer dans les listes grâce à la pagination

---

## Stack

- Django / Python
- HTML / CSS / JavaScript
- Base de données Django (SQLite ou autre)

---

## Utilisation des outils

- L’utilisation d’outils d’IA est autorisée
- Toutefois, il est **déconseillé d’utiliser l’IA pour l’exercice 1**, afin d’évaluer votre logique

---

## Rendu

Le travail doit être rendu sous la forme d’un **repository Git public**.

### Le repository doit contenir :

#### Exercice 1

- Un fichier Python unique contenant le programme demandé

#### Exercice 2

- Un projet Django complet, incluant :
  - la gestion des produits
  - le système de facturation
  - la pagination

---

## Soumission

Le lien du repository doit être envoyé par mail à :

📧 jacques.zhuang@trustia.ai
