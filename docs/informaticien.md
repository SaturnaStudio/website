# Document HTML

```html
<!-- Déclaration du type de document HTML -->
<!DOCTYPE html>
<html lang="fr">

<!-- En-tête du document avec les métadonnées -->
<head>
    <!-- Encodage du document -->
    <meta charset="UTF-8">
    
    <!-- Définition de la vue initiale sur les appareils mobiles -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- Liaison vers une feuille de style externe -->
    <link rel="stylesheet" href="../css/style.css">
    
    <!-- Titre du document HTML -->
    <title>Accueil - NSIWEB</title>
</head>

<!-- Corps du document HTML -->
<body>
    <!-- Section d'en-tête avec le titre principal du site -->
    <header class="navbar">
        <h1 class="element title">Site Web</h1>
        
        <!-- Liens de navigation -->
        <div class="links">
            <!-- Lien vers la page de présentation -->
            <a href="../" class="element removestyle">Notre Présentation</a>
            
            <!-- Lien vers la page actuelle (surlignée comme actuelle) -->
            <a href="./informaticien.html" class="element current removestyle">Informaticien</a>
        </div>
    </header>
    
    <!-- Saut de ligne -->
    <br>
    
    <!-- Section d'informations avec une image -->
    <div class="infos haspicture">
        <div>
            <!-- Titre avec le nom de la personne -->
            <h1 class="name">Linus Torvalds</h1>
            
            <!-- Liste d'informations sur Linus Torvalds -->
            <ul>
                <!-- Élément de liste : Né en 1969 en Finlande -->
                <li>Né en 1969 en Finlande</li>
                
                <!-- Élément de liste : A créé le noyau Linux à l'âge de 21 ans -->
                <li>Il crée à 21 ans le noyau Linux.</li>
                
                <!-- Élément de liste : Également le créateur de Git -->
                <li>Il est également le créateur de Git</li>
                
                <!-- Élément de liste : A reçu des prix en 2012 et 2014 pour son travail -->
                <li>En 2012 et en 2014, il reçoit des prix pour ses travaux.</li>
            </ul>
            
            <!-- Lien vers la page Wikipedia de Linus Torvalds en italique -->
            <a href="https://fr.wikipedia.org/wiki/Linus_Torvalds" target="_blank" class="element removestyle"><em>Consulter la page Wikipédia</em></a>
        </div>
        
        <!-- Image de Linus Torvalds avec texte alternatif -->
        <img class="picture" src="../images/LinusTorvalds.jpg" alt="Image de Linus Torvalds en 2014.">
    </div>
    
    <!-- Paragraphe avec un lien vers la source de l'image et une description -->
    <p class="element"><a class="removestyle" href="https://commons.wikimedia.org/wiki/File:LinuxCon_Europe_Linus_Torvalds_03.jpg">Source</a> de l'image:<br>Une image rognée et tournée de Linus Torvalds parlant à la conférence "LinuxCon Europe 2014" à Düsseldorf</p>
</body>
</html>
