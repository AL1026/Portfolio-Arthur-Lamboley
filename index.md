<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Arthur Lamboley</title>
    <style>
        /* Styles globaux */
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
            padding: 20px;
            margin: 0;
        }

        h1, h2, h3, h4, h5, h6 {
            margin: 0 0 10px 0;
            color: #333;
        }

        a {
            color: #007bff;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Conteneur principal */
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #ffffff;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Styles pour la section "Bienvenue" */
        .welcome-section {
            padding: 20px;
            background-color: #ffffff;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .welcome-section h1 {
            font-size: 2em;
            color: #333;
        }

        .welcome-section p {
            font-size: 1.2em;
            line-height: 1.5;
            color: #555;
        }

        /* Sommaire */
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            margin: 10px 0;
        }

        nav ul li a {
            display: block;
            padding: 10px;
            background-color: #e9e9e9;
            border-radius: 6px;
            transition: background-color 0.3s;
        }

        nav ul li a:hover {
            background-color: #d3d3d3;
        }

        /* Menus déroulants */
        details {
            margin-bottom: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 10px;
            background-color: #f9f9f9;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: box-shadow 0.3s ease-in-out;
        }

        details:hover {
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        summary {
            font-size: 0.85em;
            font-weight: bold;
            cursor: pointer;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 6px;
            background-color: #e9e9e9;
        }

        summary:hover {
            background-color: #d3d3d3;
        }

        /* Figure */
        figure {
            margin: 20px 0;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        figcaption {
            margin-top: 8px;
            font-style: italic;
            color: #666;
        }

        img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }

        /* Paragraphes et listes */
        p, ul {
            margin: 0 0 10px 0;
        }

        ul {
            padding-left: 20px;
        }

        li {
            margin-bottom: 5px;
        }

        /* Tableaux */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: #f4f4f4;
        }

        /* Formulaires */
        form {
            margin: 20px 0;
        }

        label {
            display: block;
            margin-bottom: 8px;
        }

        input[type="text"], input[type="email"], textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        textarea {
            resize: vertical;
        }

        button {
            background-color: #007bff;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1em;
        }

        button:hover {
            background-color: #0056b3;
        }

        /* Contact */
        .contact-info {
            margin: 20px 0;
        }

        .contact-info h2 {
            font-size: 1.5em;
        }

        .contact-info p {
            margin: 0 0 10px 0;
        }

        .contact-info a {
            color: #007bff;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        /* Autres éléments */
        code {
            background-color: #f4f4f4;
            padding: 2px 4px;
            border-radius: 4px;
        }

        blockquote {
            border-left: 4px solid #ddd;
            padding-left: 10px;
            margin: 0 0 10px 0;
            font-style: italic;
        }

        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 4px;
            overflow-x: auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="welcome-section">
            <h1>Arthur Lamboley - Ingénieur en Optique et Photonique</h1>
            <p>Bonjour ! Je suis Arthur, un étudiant en dernière année à l'école d'ingénieur Télécom Saint-Etienne, spécialisé en optique, photonique, imagerie et vision, avec une passion pour l'innovation dans le domaine de la cosmétique. Ce Portfolio vise à démontrer mes compétences en montrant les différents projets et accomplissement menés durant mon parcours. Voici comment celui-ci s'articule :</p>
            <nav>
                <ul>
                    <li><a href="#projets-stage-expérience">Projets, Stage, Expérience</a></li>
                    <li><a href="#expérience-junior-entreprise">Expérience Junior-Entreprise</a></li>
                    <li><a href="#site-web">Site Web</a></li>
                    <li><a href="#compétences">Compétences</a></li>
                    <li><a href="#cv-et-lettre-de-motivation">CV et lettre de motivation</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>

<section id="projets-stage-expérience">
<h2>Projets, Stage, Expérience</h2>

<details>
  <summary>
    <span style="display: inline-flex; align-items: center;">
      <h3 style="margin: 0; display: inline;"><u>Safran Tech : étude et automatisation des IQI, réalisation d'une interface graphique</u></h3>
    </span>
  </summary>
  <p><i>Avril 2024 - Juillet 2024</i></p>

  <p><strong>Compétences :</strong> Python, Qt, Traitement d'image, OpenCV, Template Matching</p>

  <p><strong>Description :</strong> Ce projet visait à développer une solution automatisée pour évaluer la qualité des images d'inspection de turbines, en détectant les défauts à l'aide de trois indicateurs de qualité d'image (IQI) : le duplex (flou d'image), le convergent (pouvoir de résolution), et le trou fond plat (profondeur des défauts observables).</p>

  <p><strong>Réalisation :</strong></p>
  <ul>
    <li><strong> Développement des scripts Python :</strong> Les analyses des IQI étaient entièrement automatisées via des scripts Python. Les utilisateurs n'avaient qu'à charger les images capturées des IQI, et le système procédait à l'évaluation de manière autonome. </li>
    <li><strong>Automatisation des rapports :</strong> Après chaque exécution, un rapport PDF était généré automatiquement. Ce rapport incluait des informations comme la date, l'opérateur responsable, et des graphiques illustrant les données recueillies lors des analyses (flou, résolution et profondeur des défauts détectés).</li>
    <li><strong> Interface :</strong> Une interface intuitive développée avec Qt Creator permettait aux utilisateurs de choisir soit d'exécuter les analyses de manière individuelle (par IQI), soit de lancer toutes les analyses en une seule opération. L'interface simplifiait l'intégration des images et l'accès aux résultats, avec la possibilité de générer les rapports au format PDF directement depuis l'application.</li>
    <li><strong> Contrôle de version avec Git :</strong> L'intégralité du projet était hébergée sur Git, ce qui permettait à l'équipe de développement de collaborer efficacement. Git a été utilisé à la fois pour la gestion des versions du code et pour l’hébergement de l’interface Qt, facilitant ainsi la maintenance et le déploiement du projet. </li>
  </ul>

  <div style="display: flex; flex-wrap: wrap; justify-content: center;">
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/07.jpg" alt="Table CodeV" style="width: 450px; height: auto;" />
      <figcaption>Fig.1 Table CodeV et évolution d'un spot autour du plan focale</figcaption>
    </figure>
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/08.jpg" alt="Comparaison avec un modèle double sphérique" style="width: 350px; height: auto;" />
      <figcaption>Fig.2 Comparaison avec un modèle double sphérique</figcaption>
    </figure>
  </div>
</details>

<details>
  <summary>
    <span style="display: inline-flex; align-items: center;">
      <h3 style="margin: 0; display: inline;"><u>Projet d'étude de lentille varifocale</u></h3>
    </span>
  </summary>
  <p><i>Mai 2024</i></p>

  <p><strong>Compétences :</strong> LightTool, CodeV, CAO</p>

  <p><strong>Description :</strong> Reproduire et optimiser un modèle de lentille à focale variable décrit dans une revue scientifique, en analysant ses performances à travers la modélisation par CAO et l'optimisation des paramètres optiques. Le projet visait à évaluer la capacité d'une lentille à varier sa focale en la tournant, tout en analysant des paramètres clés comme le waist</p>

  <p><strong>Réalisation :</strong></p>
  <ul>
    <li><strong> Modélisation via CodeV :</strong>
Utilisation de CodeV pour la conception assistée par ordinateur (CAO) des lentilles. Le projet a commencé par une approximation simple de la lentille à l'aide de deux lentilles sphériques avant de passer à des modélisations plus complexes. L'objectif était de reproduire une conception théorique publiée, non encore réalisée. </li>
    <li><strong>Étude des lentilles à focale variable :</strong>
Analyse approfondie de la capacité de la lentille à faire varier sa focale par rotation. L'étude portait sur les paramètres influençant ce mécanisme, notamment le waist (le point de focalisation le plus fin), permettant d'évaluer la qualité de l'image formée.</li>
    <li><strong> Algorithmes d'optimisation :</strong> Optimisation automatique des focales à l'aide d'algorithmes intégrés dans CodeV, afin de maximiser la performance de la lentille. </li>
    <li><strong> Résultats et analyse :</strong>
Bien que les résultats obtenus différaient légèrement des valeurs théoriques trouvées dans la revue, les simulations ont montré une cohérence globale du modèle. Cela a permis de tirer des conclusions sur les limites de la conception théorique initiale et les possibilités d'optimisation </li>
  </ul>

  <div style="display: flex; flex-wrap: wrap; justify-content: center;">
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/07.jpg" alt="Table CodeV" style="width: 450px; height: auto;" />
      <figcaption>Fig.1 Table CodeV et évolution d'un spot autour du plan focale</figcaption>
    </figure>
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/08.jpg" alt="Comparaison avec un modèle double sphérique" style="width: 350px; height: auto;" />
      <figcaption>Fig.2 Comparaison avec un modèle double sphérique</figcaption>
    </figure>
  </div>
</details>

<details>
  <summary>
    <span style="display: inline-flex; align-items: center;">
      <h3 style="margin: 0; display: inline;"><u>Projet de détection de défauts industriels</u></h3>
    </span>
  </summary>
  <p><i>Février 2024</i></p>

  <p><strong>Compétences :</strong> Étude de faisabilité, Système optique</p>

  <p><strong>Description :</strong> Développer une méthode de détection de défauts de surface (rayures, imperfections) sur des objets aux surfaces complexes, tels que des fonds de poêle et des flacons de parfum, en utilisant une chaîne d'acquisition visuelle et un contrôle humain.</p>

  <p><strong>Réalisation :</strong></p>
  <ul>
    <li><strong>Etude de faisabilité :</strong> Analyse des défis spécifiques liés à la détection de défauts, notamment les problèmes de réflexion spéculaire parasite et de texture irrégulière des surfaces. L’objectif était de rendre visibles des défauts difficiles à détecter à l'œil nu, en mettant en place une méthode de vision par ordinateur basée sur l’acquisition d’images d’échantillons.</li>
    <li><strong>Mise en place de la chaîne d'acquisition</strong> Conception d'une configuration précise pour capturer les images des objets inspectés, incluant le choix de l'objectif, l'éclairage et la distance. Cette chaîne permettait de détecter les défauts de surface, comme les rayures, avec une grande précision, en fonction des réglages de l'équipement.</li>
    <li><strong>Résultats et validation</strong> L’étude a démontré la faisabilité de la méthode. Nous avons pu déterminer la précision des défauts détectables selon l'objectif utilisé. Au final, un contrôle humain de l'image capturée permettait de vérifier que les défauts détectés étaient inférieurs à la taille limite spécifiée par le fabricant, garantissant ainsi la qualité des objets inspectés.</li>
  </ul>

  <div style="display: flex; flex-wrap: wrap; justify-content: center;">
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/09.jpg" alt="Détection d'un défaut sur une poêle" style="width: 364px; height: auto;" />
      <figcaption>Fig.1 Détection d'un défaut sur une poêle</figcaption>
    </figure>
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/10.jpg" alt="Extrait du CR de l'étude" style="width: 436px; height: auto;" />
      <figcaption>Fig.2 Extrait du CR de l'étude</figcaption>
    </figure>
  </div>
</details>

<details>
  <summary>
    <span style="display: inline-flex; align-items: center;">
      <h3 style="margin: 0; display: inline;"><u>Laboratoire Hubert Curien : conception et réalisation d’un système de recomposition de fréquence</u></h3>
    </span>
  </summary>
  <p><i>Mai 2023 - Juillet 2023</i></p>

  <p><strong>Compétences :</strong> 3DOptix, conception, physiques des lasers, CAO, sécurité laser</p>

  <p><strong>Description :</strong> Développer et tester un système optique permettant de scinder un faisceau laser femtoseconde en plusieurs rayons de fréquences divisées (par 2, 3, 4), avant de resynchroniser ces faisceaux pour étudier leurs effets sur différents matériaux.</p>

  <p><strong>Réalisation :</strong></p>
  <ul>
    <li><strong>Conception optique :</strong>Conception complète d'un système basé sur des miroirs polarisants, des pinholes et des miroirs ajustables montés sur des plaques mobiles pour permettre un alignement précis des faisceaux. Ce système permettait de manipuler et synchroniser les faisceaux de fréquences divisées afin de les projeter sur des matériaux et analyser les impacts et la restructuration du faisceau après interaction.</li>
    <li><strong>Simulation 3D :</strong> Utilisation du logiciel 3DOptix pour simuler le comportement du système optique et vérifier que les composants choisis (miroirs, pinholes, lentilles) étaient adaptés. Ces simulations ont permis d’optimiser la conception en laboratoire, en ajustant les distances entre les éléments optiques et en validant les choix de matériel..</li>
    <li><strong>CAO :</strong> Après une première phase de conception sur papier, la modélisation du système complet a été réalisée avec 3DOptix pour évaluer les distances optimales entre les composants et déterminer le matériel nécessaire à l’assemblage final. </li>
    <li><strong>Tests </strong> Le projet a permis d’implémenter un système fonctionnel en laboratoire, aboutissant à des résultats concluants sur la recomposition des faisceaux lasers. Les tests ont validé la faisabilité du système et ont permis d’ajuster les composants optiques pour une synchronisation précise des faisceaux. </li>
    <li><strong>Rapport technique</strong> Rédaction de deux rapports détaillés : le premier évaluant l’utilisation du logiciel 3DOptix dans un contexte de laboratoire, en soulignant ses avantages et ses limitations (notamment la disponibilité des composants de base). Le second rapport portait sur la conception et la mise en œuvre du système optique, incluant les choix de composants, les ajustements réalisés, et les résultats obtenus.</li>
  </ul>

  <div style="display: flex; flex-wrap: wrap; justify-content: center;">
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/13.jpg" alt="Diagramme d'exigence" style="width: 322px; height: auto;" />
      <figcaption>Fig.1 Diagramme d'exigence</figcaption>
    </figure>
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/12.jpg" alt="Conception sur 3DOptix" style="width: 478px; height: auto;" />
      <figcaption>Fig.2 Conception sur 3DOptix</figcaption>
    </figure>
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/11.JPG" alt="Mise en place de la solution" style="width: 322px; height: auto;" />
      <figcaption>Fig.3 Mise en place de la solution</figcaption>
    </figure>
  </div>
</details>

<details>
  <summary>
    <span style="display: inline-flex; align-items: center;">
      <h3 style="margin: 0; display: inline;"><u>Projet de classification de coquilles Saint-Jacques</u></h3>
    </span>
  </summary>
  <p><i>Décembre 2023 - Février 2024</i></p>

  <p><strong>Compétences :</strong> NI Vision, Système optique, vision industrielle</p>

  <p><strong>Description :</strong>Développer un système optique et d'éclairage pour automatiser le tri des coquilles Saint-Jacques selon plusieurs critères, tels que la couleur, la circularité, la taille, la hauteur, et la présence de défauts.</p>

  <p><strong>Réalisation:</strong></p>
  <ul>
  <li><strong>Conception du système optique et d'éclairage :</strong>
    <ul>
      <li>Développement d'une solution intégrant divers types d'éclairage : infrarouge, LED, rétroéclairage.</li>
      <li>Utilisation d'équipements standards ajustés manuellement pour optimiser la capture des images des coquilles.</li>
    </ul>
  </li>
  <li><strong>Vision par ordinateur :</strong>
    <ul>
      <li>Développement d'algorithmes de traitement d'image avec <strong>NI Vision</strong> :</li>
      <li><strong>Segmentation d'image</strong> : Séparation des coquilles du fond et des autres objets.</li>
      <li><strong>Reconnaissance de forme</strong> : Identification des formes géométriques des coquilles.</li>
      <li><strong>Filtrage</strong> : Nettoyage des images pour améliorer la détection des caractéristiques.</li>
      <li><strong>Détection de contours</strong> : Identification des contours pour évaluer la circularité et la taille.</li>
    </ul>
  </li>
  <li><strong>Défis et résultats :</strong>
    <ul>
      <li><strong>Défis</strong> : La détection de défauts de surface (rayures) a été difficile en raison de leur similarité avec les textures naturelles des coquilles.</li>
      <li><strong>Résultats</strong> : Le système a réussi à trier les coquilles selon les critères spécifiés, avec des performances satisfaisantes malgré les défis liés aux défauts de surface.</li>
    </ul>
  </li>
</ul>

  <div style="display: flex; flex-wrap: wrap; justify-content: center;">
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/14.jpg" alt="Calcul de la circularité" style="width: 392px; height: auto;" />
      <figcaption>Fig.1 Calcul de la circularité</figcaption>
    </figure>
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/15.jpg" alt="Interface réalisée" style="width: 408px; height: auto;" />
      <figcaption>Fig.2 Interface réalisée</figcaption>
    </figure>
  </div>
</details>

<details>
  <summary>
    <span style="display: inline-flex; align-items: center;">
      <h3 style="margin: 0; display: inline;"><u>Projet de classification de coccinelles</u></h3>
    </span>
  </summary>
  <p><i>Mars 2024 - Mai 2024</i></p>

  <p><strong>Compétences :</strong> Imagerie, MATLAB, classifieurs</p>

  <p><strong>Description :</strong>Développement d'un système de classification de coccinelles basé sur de l'apprentissage croisé. Le système a été conçu pour classifier les coccinelles en cinq catégories, avec 40 images par catégorie. La classification repose sur trois critères : le nombre de points, la couleur, et la circularité. Une matrice de confusion a été réalisée pour évaluer les performances du système.</p>
</p>

  <p><strong>Réalisations</strong></p>
 <ul>
  <li><strong>Classification et validation :</strong> Utilisation de 40 images par catégorie réparties en cinq catégories. Application de la cross-validation avec un découpage des données en 75% pour l'entraînement et 25% pour les tests. Les images sont échangées entre les ensembles d'entraînement et de test pour assurer une validation robuste. Les critères de classification (nombre de points, couleur, circularité) ont été déterminés arbitrairement et ajustés en fonction des résultats.</li>
  <li><strong>Algorithmes et techniques utilisés :</strong> Algorithmes de traitement d'image comprenant l'extraction de fond, la transformation de Hough, et la reconnaissance de formes. Développement de plusieurs algorithmes en MATLAB, dont un algorithme de prétraitement, un pour chaque caractéristique, et un algorithme principal regroupant l'ensemble des traitements et réalisant la cross-validation.</li>
  <li><strong>Matrice de confusion :</strong> Construction d'une matrice de confusion pour évaluer la performance du système. La matrice a montré une très bonne précision avec presque aucune erreur après plusieurs ajustements et tests.</li>
  <li><strong>Défis et résultats :</strong> Défi principal : La variabilité intra-espèce des coccinelles a rendu la classification difficile, avec des erreurs potentielles dues à cette variabilité. Résultats : Le système a réussi à classifier les coccinelles avec une haute précision, malgré les défis liés à la variabilité des caractéristiques des coccinelles.</li>
</ul>


  <div style="display: flex; flex-wrap: wrap; justify-content: center;">
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/17.jpg" alt="Individus étudiés" style="width: 450px; height: auto;" />
      <figcaption>Fig.1 Individus étudiés</figcaption>
    </figure>
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/16.jpg" alt="Matrice de confusion finale" style="width: 350px; height: auto;" />
      <figcaption>Fig.2 Matrice de confusion finale</figcaption>
    </figure>
  </div>
</details>

<details>
  <summary>
    <span style="display: inline-flex; align-items: center;">
      <h3 style="margin: 0; display: inline;"><u>Projet de suivi d’une balle (vision par ordinateur)</u></h3>
    </span>
  </summary>
  <p><i>Mars 2023 - Mai 2023</i></p>

  <p><strong>Technologies :</strong> Python, Raspberry Pi, OpenCV, traitement d'image, vision par ordinateur</p>

<p><strong>Description :</strong> Développement d'un système de vision par ordinateur pour suivre une balle en mouvement. Le système a été entièrement réalisé sur Raspberry Pi, offrant une solution compacte et efficace pour le suivi en temps réel.</p>

<p><strong>Réalisations :</strong></p>
<ul>
  <li><strong>Traitement d'image :</strong> Mise en œuvre d'algorithmes pour analyser et traiter des images vidéo en temps réel, permettant de détecter et suivre la balle en mouvement avec précision.</li>
  <li><strong>Vision par ordinateur :</strong> Développement et application de techniques avancées pour la détection et le suivi d'objets. Utilisation de méthodes telles que le filtrage de Kalman ou les algorithmes de suivi basés sur des contours pour maintenir la balle en vue.</li>
  <li><strong>Programmation en Python :</strong> Création de scripts et d'applications en Python pour le traitement des données d'image. Utilisation de bibliothèques comme OpenCV pour la capture vidéo, le traitement d'image, et le suivi de la balle.</li>
  <li><strong>Déploiement sur Raspberry Pi :</strong> Installation, configuration et optimisation des applications sur le Raspberry Pi. Gestion des contraintes de performance et d'efficacité énergétique tout en assurant un suivi fluide et précis.</li>
</ul>

  <div style="display: flex; flex-wrap: wrap; justify-content: center;">
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/01.jpg" alt="Diagramme d'exigence" style="width: 555px; height: auto;" />
      <figcaption>Fig.1 Diagramme d'exigence</figcaption>
    </figure>
    <figure style="margin: 20px; text-align: center;">
      <img src="./assets/02.png" alt="Détection de la balle" style="width: 300px; height: auto;" />
      <figcaption>Fig.2 Détection de la balle</figcaption>
    </figure>
  </div>
</details>
</section>

<section id="expérience-junior-entreprise">
<h2>Expérience Junior-Entreprise</h2>
<details>
  <summary>
    <span style="display: inline-flex; align-items: center;">
      <h3 style="margin: 0; display: inline;"><u>Auditeur conseil</u></h3>
    </span>
  </summary>
  <p><i>Janvier 2024 - Actuellement</i></p>

  <p><strong>Description :</strong> En qualité d'Auditeur-Conseil à la Confédération Nationale des Junior-Entreprises, mon parcours a débuté par une sélection rigoureuse, avec des tests écrits et un week-end de formation, avec un taux de réussite de seulement 7%. En tant qu'Auditeur-Conseil, ma mission d'une journée consiste à :</p>
  <ul>
    <li>Analyser le fonctionnement de la Junior-Entreprise (conformité légale, audit des processus de stratégie et pilotage, activité commerciale, GRH, cadre légal et réglementaire)</li>
    <li>Auditer les missions réalisées par la structure (qualité des livrables, cohérence administrative, respect de la déontologie, ...)</li>
    <li>Conseiller la Junior-Entreprise (solutions aux problèmes rencontrés, optimisation, ...)</li>
  </ul>

  <p><strong>Enjeux :</strong></p>
  <ul>
    <li>Garantir la qualité et la pérennité du Mouvement des Junior-Entreprises</li>
    <li>Développer les structures du mouvement en leur apportant une expertise adaptée</li>
    <li>Assurer le respect de la marque Junior-Entreprise</li>
    <li>Stimuler le développement et l'amélioration des performances de la structure auditée grâce aux conseils stratégiques prodigués</li>
  </ul>

  <p><strong>Compétences :</strong></p>
  <ul>
    <li><strong>Audit :</strong> Analyse stratégique de la structure, respect des normes et des lois</li>
    <li><strong>Conseil :</strong> Formulation de conseils adaptés à la structure, priorisation</li>
    <li><strong>Sens du relationnel :</strong> Bienveillance, compréhension</li>
  </ul>

  <div style="text-align: center; margin: 20px 0;">
    <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:7186641419502067712" height="1298" width="504" frameborder="0" allowfullscreen="" title="Post intégré"></iframe>
  </div>
</details>

<details>
  <summary>
    <span style="display: inline-flex; align-items: center;">
      <h3 style="margin: 0; display: inline;"><u>Responsable communication et marketing</u></h3>
    </span>
  </summary>
  <p><i>Octobre 2022 - Avril 2024</i></p>

  <p><strong>Description :</strong> En tant que Responsable Communication et Marketing au sein d'Inspire, je fais partie intégrante d'une équipe composée de trois personnes, dédiée à la coordination complète de notre communication. Mon rôle consiste à orchestrer la stratégie de communication et marketing, avec pour objectif d'optimiser notre présence et de renforcer notre impact sur le marché.</p>

  <p><strong>Mission :</strong></p>
  <ul>
    <li>Élaborer et mettre en œuvre la stratégie de communication et marketing</li>
    <li>Gérer les canaux de communication (communication sur les réseaux en accord avec la stratégie de la structure)</li>
    <li>Créer du contenu (production de contenus, qualité et pertinence)</li>
    <li>Analyser et optimiser les performances (amélioration continue, ajustement)</li>
  </ul>

  <p><strong>Enjeux :</strong></p>
  <ul>
    <li>Élever la notoriété de la marque</li>
    <li>Accroître la fidélité client grâce à des initiatives de communication</li>
    <li>Assurer la cohérence de la stratégie de communication</li>
    <li>Optimiser les performances pour une croissance continue</li>
  </ul>

  <p><strong>Compétences :</strong></p>
  <ul>
    <li><strong>Communication :</strong> Communication visuelle, relation presse, conception de matériel de prospection</li>
    <li><strong>Marketing :</strong> Analyse de l'environnement, création de stratégie, déploiement de stratégie</li>
  </ul>

  <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 20px 0;">
    <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:7118537881861677056" height="1321" width="504" frameborder="0" allowfullscreen="" title="Post intégré"></iframe>
    <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:7076142505183825920" height="1256" width="504" frameborder="0" allowfullscreen="" title="Post intégré"></iframe>
  </div>
</details>
</section>

<section id="site-web">
<h2>Site Web</h2>

<details>
  <summary>
    <span style="display: inline-flex; align-items: center;">
      <h3 style="margin: 0; display: inline;"><u>Site Web sur l'Optique et la Cosmétique</u></h3>
    </span>
  </summary>
  <p><span style="font-size: smaller;"><i>Juillet 2024 - Actuel</i></span></p>
  
  <p><strong>Description :</strong> Site Web créé pour mettre en valeur les applications de l'optique, de la photonique, de l'imagerie et de la vision dans le milieu de la cosmétique, à destination des étudiant.e.s de ces filières. L'objectif est de donner des cas d'usages des technologies étudiées en cours et d'informer les étudiant.e.s sur ce milieu, peu prisé dans mon école.</p>
  
  <p><strong>Site Web :</strong> <a href="https://cassolette5.wordpress.com/" target="_blank">https://cassolette5.wordpress.com/</a></p>
  
  <p><strong>Quelques articles :</strong></p>
  <ul>
    <li><a href="https://cassolette5.wordpress.com/2024/07/17/la-vision-par-ordinateur-pour-le-maquillage-personnalise-perfect-corp-mofiface/" target="_blank"><strong>La vision par ordinateur pour le maquillage personnalisé (Perfect Corp & MofiFace)</strong></a></li>
    <li><a href="https://cassolette5.wordpress.com/2024/07/12/imagerie-hyperspectrale-applications-innovantes-en-cosmetique/" target="_blank"><strong>Applications de l’Imagerie Hyperspectrale en Cosmétique</strong></a></li>
  </ul>
</details>
</section>

<section id="compétences">
            <h2>Compétences</h2>
                    <h3>Compétences techniques</h3>
                <ul>
                    <li>Optique et Photonique : Conception et simulation de systèmes optiques, analyse de faisabilité, traitement d'image, physique des lasers.</li>
                    <li>Imagerie et Vision : Détection et classification d'objets, vision par ordinateur, automatisation, imagerie 3D, apprentissage.</li>
                    <li>Langages de Programmation : Python, MATLAB, NI Vision, C++, SQL.</li>
                    <li>Qualité : Audit, norme ISO, Conseil, Analyse.</li>
                </ul>
                    <h3>Compétences transverse</h3>
                <ul>
                    <li>Rédaction : LaTeX, Pack Office, Git.</li>
                    <li>Adaptabilité</li>
                    <li>Communication</li>
                </ul>
        </section>

<section id="cv-et-lettre-de-motivation">
            <h2>CV et lettre de motivation</h2>
            <p>Vous pouvez consulter mon <a href="assets/Arthur_Lamboley_CV_.pdf" target="_blank">CV</a> et ma <a href="documents/Arthur_Lamboley_Lettre_de_Motivation.pdf" target="_blank">lettre de motivation (à venir)</a> en cliquant sur les liens.</p>
        </section>

<section id="contact">
            <div class="contact-info">
                <h2>Contactez-moi</h2>
                <p><strong>Email :</strong> <a href="mailto:lamboley.arthur26@gmail.com">lamboley.arthur26@gmail.com</a></p>
                <p><strong>Téléphone :</strong> +33 6 27 87 24 65</p>
                <p><strong>LinkedIn :</strong> <a href="https://www.linkedin.com/in/lamboley-arthur/" target="_blank">Arthur Lamboley</a></p>
            </div>
            <form action="mailto:arthur.lamboley26@gmail.com" method="post" enctype="text/plain">
                <label for="name">Nom :</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email :</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message :</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                <button type="submit">Envoyer</button>
            </form>
        </section>
    </div>



