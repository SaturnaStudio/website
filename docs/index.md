# PAGE: INDEX.HTML

```html
<!-- Définit le type de document HTML -->
<!DOCTYPE html>

<!-- Balise d'ouverture de l'élément HTML avec une langue spécifiée (français) -->
<html lang="fr">

<!-- Balise d'ouverture de l'élément head qui contient des métadonnées et liens vers des fichiers externes -->
<head>

    <!-- Spécifie l'encodage des caractères pour le document -->
    <meta charset="UTF-8">

    <!-- Spécifie la largeur de la vue pour les appareils et l'échelle initiale -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Lien vers une feuille de style externe -->
    <link rel="stylesheet" href="css/style.css">

    <!-- Titre de la page affiché dans la barre de titre du navigateur -->
    <title>NSI: Présentations</title>

<!-- Balise de fermeture de l'élément head -->
</head>

<!-- Balise d'ouverture de l'élément body qui contient le contenu de la page -->
<body>

    <!-- Balise d'ouverture de l'en-tête avec une classe "navbar" -->
    <header class="navbar">

        <!-- Balise de titre de niveau 1 avec une classe "element title" -->
        <h1 class="element title">Présentations</h1>

        <!-- Div contenant des liens avec une classe "links" -->
        <div class="links">

            <!-- Lien vers la page d'accueil avec une classe "element current removestyle" -->
            <a href="./" class="element current removestyle">Notre Présentation</a>

            <!-- Lien vers la page d'un informaticien avec une classe "element removestyle" -->
            <a href="./pages/informaticien.html" class="element removestyle">Informaticien</a>

        <!-- Balise de fermeture de la div -->
        </div>

    <!-- Balise de fermeture de l'en-tête -->
    </header>
    <!-- Saut de Ligne -->
    <br>

    <!-- Div avec une classe "infos" contenant des informations sur un élève -->
    <div class="infos">

        <!-- Titre de niveau 1 avec une classe "name" -->
        <h1 class="name">Kylliam **</h1>

        <!-- Paragraphe avec une classe "description" -->
        <p class="description">Élève de la classe <b>1G3</b> dans le <em>Lycée Paul Lapie</em>, j'étudie dans les chinoiseries en tout genre. J'ai déjà mangé un chien et j'aime les enfants.</p>

        <!-- Paragraphe avec une classe "fact" -->
        <p class="fact">LGBT ET FIERE DE L'ETRE 🏳️‍🌈🏳️‍🌈</p>

    <!-- Balise de fermeture de la div -->
    </div>

    <!-- Saut de ligne -->

    <!-- Autre div avec une classe "infos" contenant des informations sur un autre élève -->
    <div class="infos">

        <!-- Titre de niveau 1 avec une classe "name" -->
        <h1 class="name">Thibault *****</h1>

        <!-- Paragraphe avec une classe "description" -->
        <p class="description">Je suis un élève de <b>1G3</b> passionné par les jeux vidéos et le développement. Dans le futur, j'ai pour ambition de raser le lycée (et de rejoindre une grande boite de tech comme Microsoft).</p>

        <!-- Paragraphe avec une classe "fact" -->
        <p class="fact">Fun Fact: J'ai laché un prout pendant le brevet. 😃<br>(Conseil: Ne venez pas avec des chewing-gums en examen ça donne mal au ventre).</p>

    <!-- Balise de fermeture de la div -->
    </div>

    <!-- Paragraphe contenant du texte -->
    <p>Le nom est censuré volontairement.</p>

<!-- Balise de fermeture de l'élément body -->
</body>

<!-- Balise de fermeture de l'élément HTML -->
</html>
