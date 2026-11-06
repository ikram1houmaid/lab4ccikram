# TP : Attributs et Méthodes Statiques en C++

## Présentation
Ce TP a pour objectif de comprendre et de pratiquer les attributs statiques, les méthodes statiques, les associations entre classes et les pointeurs d'objets en langage C++.

---

## Exercice 1 : Suivi des Livres dans une Bibliothèque

### Objectif
Créer une classe `Livre` permettant de gérer les informations des livres et de compter automatiquement le nombre total de livres créés.

### Classe Livre
La classe contient les attributs suivants :
- `titre` : titre du livre.
- `auteur` : nom de l'auteur.
- `annee` : année de publication.
- `nbLivres` : attribut statique qui compte le nombre total de livres créés.

### Méthodes implémentées
- **Constructeur** : initialise les informations du livre et incrémente le compteur.
- `afficher()` : affiche les informations d'un livre.
- `afficherTotal()` : méthode statique qui affiche le nombre total de livres créés.

### Test
Dans la fonction `main()`, trois objets sont créés :
- 1984 – George Orwell – 1949.
- Le Petit Prince – Antoine de Saint-Exupéry – 1943.
- L'Étranger – Albert Camus – 1942.

**Résultat attendu :** le nombre total de livres affiché est 3.

---

## Exercice 2 : Gestion des Étudiants et de l'Université

### Objectif
Créer deux classes associées `Universite` et `Etudiant` pour gérer les étudiants d'une université et compter automatiquement leur nombre.

### Classe Universite
Cette classe contient :
- `nom` : nom de l'université.
- `afficherNom()` : affiche le nom de l'université.

### Classe Etudiant
Cette classe contient :
- `nom` : nom de l'étudiant.
- `age` : âge de l'étudiant.
- `universite` : pointeur vers un objet de la classe `Universite`.
- `nbEtudiants` : attribut statique qui compte le nombre total d'étudiants créés.

### Méthodes implémentées
- **Constructeur** : initialise les informations de l'étudiant et incrémente le compteur.
- `afficher()` : affiche le nom, l'âge et l'université de l'étudiant.
- `afficherTotal()` : méthode statique qui affiche le nombre total d'étudiants créés.

### Test
Dans la fonction `main()` :
1. Création d'une université : Université de Casablanca.
2. Création de deux étudiants : Amine (20 ans) et Sara (21 ans).
3. Affichage des informations des deux étudiants.
4. Affichage du nombre total d'étudiants.

**Résultat attendu :** le nombre total d'étudiants affiché est 2.

---

## Concepts C++ abordés

- Les classes et les objets.
- Les attributs privés (`private`).
- Les constructeurs.
- Les attributs statiques (`static`).
- Les méthodes statiques.
- L'initialisation des attributs statiques en dehors de la classe.
- Les pointeurs d'objets.
- L'opérateur `&` pour récupérer une adresse mémoire.
- L'opérateur `->` pour accéder aux membres d'un objet via un pointeur.
- L'association entre deux classes.

---

## Conclusion

Ce TP permet de maîtriser l'utilisation des attributs et méthodes statiques en C++, ainsi que la manipulation des pointeurs et l'association entre classes.

Les deux exercices montrent comment partager un compteur entre plusieurs objets et comment appeler une méthode statique directement à partir du nom de la classe, sans créer une nouvelle instance.

**Langage utilisé :** C++  
**Fichier source :** `main.cpp`
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/b558efd5-f72c-436c-811c-2dcf5da3a618" />
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/ea9df8ba-9516-44ff-8025-552b338c49a3" />
