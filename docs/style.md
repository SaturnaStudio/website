# CSS: STYLE.CSS


```css
/* Importe les polices de caractères Lexend (300 et 400) et Quicksand (700) depuis Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Lexend:wght@300;400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@700&display=swap');

/*
Variables globales définies dans :root.
Ces variables seront utilisées pour définir des couleurs réutilisables.
*/
:root {
    --background: #202020;       /* Couleur d'arrière-plan globale */
    --primary: #005B41;          /* Couleur principale */
    --secondary: #232D3F;        /* Couleur secondaire */
    --no-style-links: #F39F5A;   /* Couleur pour les liens sans style */
}

/* Style global pour le corps de la page */
body {
    font-family: 'Lexend', sans-serif;  /* Utilise la police Lexend pour le texte du corps de la page */
    margin: 0;
    padding: 0;
    background-color: var(--background); /* Utilise la couleur d'arrière-plan définie dans :root */
}

/* Style pour la barre de navigation */
.navbar {
    display: flex;
    background-color: var(--primary);   /* Utilise la couleur principale définie dans :root */
    justify-content: space-around;
    align-items: center;
}

/* Style pour les éléments de la page */
.element {
    font-family: 'Quicksand', sans-serif; /* Utilise la police Quicksand pour les éléments de la page */
    color: white;                         /* Couleur du texte */
    background: none;
    padding-inline: 10px;
}

/* Style pour les liens sans style (classe removestyle) */
.removestyle {
    text-decoration: inherit;
    color: var(--no-style-links);  /* Utilise la couleur pour les liens sans style définie dans :root */
}

/* Style pour les éléments qui ne sont pas actuellement sélectionnés (classe current) */
.element:not(.current) {
    transition: color 1s ease 0s;  /* Effet de transition pour la couleur pendant 1 seconde avec un fondu en douceur */
}

/* Style pour les liens sans style qui ne sont pas actuellement sélectionnés (classe current) au survol */
.removestyle:not(.current):hover {
    color: #2baaca;  /* Change la couleur au survol */
}

/* Style pour les éléments actuellement sélectionnés (classe current) */
.current {
    color: var(--secondary);  /* Utilise la couleur secondaire définie dans :root */
}

/* Style pour les faits (éléments de texte centrés) */
.fact {
    text-align: center;
}

/* Style pour les informations (conteneur avec des éléments alignés verticalement) */
.infos {
    display: flex;
    align-items: center;
    flex-direction: column;
    background-color: white;
    flex-wrap: wrap-reverse;  /* Inverse l'ordre de l'enroulement des éléments flexibles */
    padding: 10px;
}

/* Style pour les conteneurs qui ont une image (classe haspicture) */
.haspicture {
    justify-content: center;
    flex-direction: row;  /* Aligne les éléments horizontalement */
}

/* Style pour la marge à gauche des images (classe picture) */
.picture {
    margin-left: 50px;
}
```