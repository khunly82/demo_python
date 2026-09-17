# Exercice 1 - Tableaux et dictionnaires

En considérant la liste ci dessous

```python
livres = [
    {
        "titre": "Le Petit Prince",
        "auteurs": ["Antoine de Saint-Exupéry"],
        "nbpages": 96,
        "categories": ["Fiction", "Philosophie", "Jeunesse"],
    },
    {
        "titre": "1984",
        "auteurs": ["George Orwell"],
        "nbpages": 328,
        "categories": ["Dystopie", "Science-Fiction", "Classique"],
    },
    {
        "titre": "L'Étranger",
        "auteurs": ["Albert Camus"],
        "nbpages": 159,
        "categories": ["Philosophie", "Classique"],
    },
    {
        "titre": "Dune",
        "auteurs": ["Frank Herbert"],
        "nbpages": 688,
        "categories": ["Science-Fiction", "Aventure"],
    },
    {
        "titre": "Le Seigneur des Anneaux : La Communauté de l'Anneau",
        "auteurs": ["J.R.R. Tolkien"],
        "nbpages": 576,
        "categories": ["Fantasy", "Aventure"],
    },
    {
        "titre": "Harry Potter à l'école des sorciers",
        "auteurs": ["J.K. Rowling"],
        "nbpages": 304,
        "categories": ["Fantasy", "Jeunesse"],
    },
    {
        "titre": "Fahrenheit 451",
        "auteurs": ["Ray Bradbury"],
        "nbpages": 248,
        "categories": ["Dystopie", "Science-Fiction"],
    },
    {
        "titre": "Les Misérables",
        "auteurs": ["Victor Hugo"],
        "nbpages": 1488,
        "categories": ["Classique", "Roman Historique"],
    },
    {
        "titre": "Le Comte de Monte-Cristo",
        "auteurs": ["Alexandre Dumas"],
        "nbpages": 1248,
        "categories": ["Aventure", "Classique"],
    },
    {
        "titre": "L'Alchimiste",
        "auteurs": ["Paulo Coelho"],
        "nbpages": 192,
        "categories": ["Philosophie", "Développement Personnel"],
    },
    {
        "titre": "Sapiens : Une brève histoire de l'humanité",
        "auteurs": ["Yuval Noah Harari"],
        "nbpages": 512,
        "categories": ["Histoire", "Non-fiction", "Anthropologie"],
    },
    {
        "titre": "Fondation",
        "auteurs": ["Isaac Asimov"],
        "nbpages": 256,
        "categories": ["Science-Fiction"],
    },
    {
        "titre": "Le Nom de la Rose",
        "auteurs": ["Umberto Eco"],
        "nbpages": 560,
        "categories": ["Policier", "Roman Historique"],
    },
    {
        "titre": "Guerre et Paix",
        "auteurs": ["Léon Tolstoï"],
        "nbpages": 1225,
        "categories": ["Classique", "Roman Historique"],
    },
    {
        "titre": "Ne tirez pas sur l'oiseau moqueur",
        "auteurs": ["Harper Lee"],
        "nbpages": 384,
        "categories": ["Classique", "Fiction"],
    },
    {
        "titre": "Le Meilleur des mondes",
        "auteurs": ["Aldous Huxley"],
        "nbpages": 288,
        "categories": ["Dystopie", "Science-Fiction"],
    },
    {
        "titre": "L'Ombre du vent",
        "auteurs": ["Carlos Ruiz Zafón"],
        "nbpages": 640,
        "categories": ["Mystère", "Fiction"],
    },
    {
        "titre": "Des souris et des hommes",
        "auteurs": ["John Steinbeck"],
        "nbpages": 120,
        "categories": ["Classique", "Drame"],
    },
    {
        "titre": "L'Hitchhiker's Guide to the Galaxy",
        "auteurs": ["Douglas Adams"],
        "nbpages": 216,
        "categories": ["Science-Fiction", "Humour"],
    },
    {
        "titre": "Good Omens",
        "auteurs": ["Terry Pratchett", "Neil Gaiman"],
        "nbpages": 416,
        "categories": ["Fantasy", "Humour"],
    },
]
```

Afficher:

1. le titre des livres dont le nombre de pages est > 250
2. le titre des livres de science-fiction
3. le nombre de pages total des livres de Fantasy
4. le nombre de pages moyen