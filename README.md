# mon-site-html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recettes Réunionnaises : plats et desserts</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Imperial+Script&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=DM+Serif+Text:ital@0;1&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
    <style>
        body {
            display: flex;
            justify-content: center; /* Centre horizontalement */
            align-items: center;     /* Centre verticalement */
            height: 100vh;           /* Utilise 100% de la hauteur de la fenêtre */
            margin: 0;               /* Supprime les marges par défaut */
            font-family: Imperial Script, sans-serif; /* Choix de police */
            background-image: url('https://t3.ftcdn.net/jpg/03/18/85/50/360_F_318855002_ub9t7PEZpTOTrh4Xqgnz1YYqoHN6G550.jpg'); /* Image de fond */
            background-size: cover; /* Permet à l'image de couvrir toute la surface */
            background-position: center; /* Centre l'image */
            background-repeat: no-repeat; /* Empêche la répétition de l'image */
            position: relative; /* Nécessaire pour positionner l'élément logo en absolu par rapport à body */
        }

        h1 {
            font-size: 5rem;        /* Taille de police grande */
            color: #ffffff;         /* Couleur du texte en noir pour le contraste */
            text-align: center;     /* Centre le texte à l'intérieur du <h1> */
            position: absolute;     /* Permet de positionner l'élément */
            top: 60px;             /* Positionne l'élément à 300px du haut de la page */
            left: 50px;             /* Positionne l'élément à 50px de la gauche */
            right: 50px;            /* Positionne l'élément à 50px de la droite (peu utile ici) */
        }

        h2 {
            font-size: 25px;
            color: #000000;         /* Couleur du texte en noir pour le contraste */
            text-align: center;     /* Centre le texte à l'intérieur du <h2> */
            position: absolute;     /* Permet de positionner l'élément */
            top: 6px;               /* Positionne l'élément à 300px du haut de la page */
            left: 850px;            /* Positionne l'élément à 50px de la gauche */
            right: 50px;            /* Positionne l'élément à 50px de la droite (peu utile ici) */
            font-family: "DM Serif Text", serif;
        }
        .subtitles h3, .subtitles h4, .subtitles h5 {
    transform: translateX(6px); /* Décale vers la droite de 10px */
                      }

        .subtitles {
            display: flex; /* Aligne les sous-titres horizontalement */
            justify-content: center; /* Centre les sous-titres horizontalement */
            margin-top: 15px; /* Espacement sous le sous-titre principal */
        }

        .subtitles h3, .subtitles h4, .subtitles h5 {
            font-size: 20px;
            color: #ffffff;
            font-family: "Roboto", serif;
            margin: 0 20px; /* Espacement entre chaque sous-titre */
            cursor: pointer; /* Change le curseur pour indiquer un lien cliquable */
        }

        /* Changer la couleur en rouge au survol */
        .subtitles h3:hover, .subtitles h4:hover, .subtitles h5:hover {
            color: red;
         }

        /* Logo */
        .logo {
            position: absolute;   /* Positionne l'image par rapport au parent (body) */
            top: 20px;             /* Place le logo à 20px du haut */
            right: 20px;           /* Place le logo à 20px du bord droit */
            width: 80px;           /* Taille du logo : 50px de largeur */
            height: auto;          /* Laisse la hauteur s'ajuster automatiquement */
        }
    </style>
</head>
<body>
    <h1>La Réunion</h1>
    <h2>ACCUEIL</h2>
    <!-- Conteneur des sous-titres avec des liens -->
    <div class="subtitles">
        <a href="plats.html"><h3>Plats</h3></a>
        <a href="dessert.html"><h4>Desserts</h4></a>
        <a href="qui-sommes-nous.html"><h5>Qui sommes nous?</h5></a>  
    </div>
    <!-- Logo dans le coin supérieur droit -->
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Proposed_flag_of_R%C3%A9union_%28VAR%29.svg/640px-Proposed_flag_of_R%C3%A9union_%28VAR%29.svg.png" class="logo" alt="Logo de La Réunion">
</body>
</html>
