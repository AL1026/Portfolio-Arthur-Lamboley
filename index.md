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

  <p><strong>Technologies :</strong> Python, Qt, Traitement d'image, OpenCV, Template Matching</p>

  <p><strong>Description :</strong> Étude et automatisation des indicateurs de qualité d'image (IQI) (3 IQI principaux, un duplex, un convergent, un trou fond plat). Des rapports sont émis automatiquement après chaque exécution. Une interface développée avec Qt Creator permet de lancer chacun des programmes individuellement (ou de tout lancer de manière groupée). L'ensemble a été hébergé sur Git.</p>

  <p><strong>Compétences :</strong></p>
  <ul>
    <li><strong>Automatisation :</strong> Développement de processus automatisés pour l'évaluation des IQI.</li>
    <li><strong>Traitement d'image :</strong> Analyse des images pour détecter et évaluer les défauts.</li>
    <li><strong>Programmation en Python :</strong> Création de scripts pour automatiser les tâches d'analyse.</li>
  </ul>

  <div style="display: flex; justify-content: center; align-items: center; flex-wrap: wrap;">
    <figure style="margin: 10px; text-align: center;">
      <img src="./assets/05.jpg" alt="Interface graphique" style="width: 393px; height: auto;" />
      <figcaption>Fig.1 Interface graphique</figcaption>
    </figure>
    <figure style="margin: 10px; text-align: center;">
      <img src="./assets/06.jpg" alt="Détection des trous" style="width: 407px; height: auto;" />
      <figcaption>Fig.2 Détection des trou pour l'IQI trou fond plat</figcaption>
    </figure>
    <figure style="margin: 10px; text-align: center;">
      <img src="./assets/04.jpg" alt="Dichotomie" style="width: 381px; height: auto;" />
      <figcaption>Fig.3 Dichotomie associée à l'IQI convergent</figcaption>
    </figure>
    <figure style="margin: 10px; text-align: center;">
      <img src="./assets/03.jpg" alt="Template matching" style="width: 419px; height: auto;" />
      <figcaption>Fig.4 Template matching pour l'IQI duplex</figcaption>
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

  <p><strong>Technologies :</strong> LightTool, CodeV, CAO</p>

  <p><strong>Description :</strong> Modélisation et étude des limites des lentilles à focale variable à l'aide de la conception assistée par ordinateur (CAO).</p>

  <p><strong>Compétences :</strong></p>
  <ul>
    <li><strong>CAO :</strong> Réalisation de système numérique pour modéliser les lentilles.</li>
    <li><strong>Optimisation :</strong> Recherche des rayons de courbure idéaux.</li>
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

  <p><strong>Technologies :</strong> Étude de faisabilité, Système optique</p>

  <p><strong>Description :</strong> Études de faisabilité concernant la détection de défauts sur des objets, tels que des fonds de poêle et des flacons de parfum.</p>

  <p><strong>Compétences :</strong></p>
  <ul>
    <li><strong>Analyse de faisabilité :</strong> Évaluation des possibilités et des défis de la détection de défauts.</li>
    <li><strong>Traitement d'image :</strong> Application de techniques pour identifier et analyser les défauts.</li>
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

  <p><strong>Technologies :</strong> 3DOptix</p>

  <p><strong>Description :</strong> Conception et réalisation d'un système de recomposition de fréquence. Test et rapport avec le logiciel 3DOptix.</p>

  <p><strong>Compétences :</strong></p>
  <ul>
    <li><strong>Conception optique :</strong> Développement de systèmes pour recomposer les fréquences.</li>
    <li><strong>Simulation 3D :</strong> Utilisation de logiciels pour tester et valider les conceptions.</li>
    <li><strong>CAO :</strong> Modélisation avec le logiciel 3DOptix, étude des possibilités du logiciel.</li>
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

  <p><strong>Technologies :</strong> NI Vision, Système optique</p>

  <p><strong>Description :</strong> Conception d'un système optique et d'éclairage pour la classification de coquilles Saint-Jacques. L'objectif était, en accord avec notre client, de définir puis réaliser un système pour faciliter le tri des coquilles selon certains critères, notamment la couleur, la circularité, la taille, la hauteur ou encore la présence de défaut.</p>

  <p><strong>Compétences :</strong></p>
  <ul>
    <li><strong>Conception de systèmes optiques :</strong> Développement de systèmes pour des applications spécifiques.</li>
    <li><strong>Vision par ordinateur :</strong> Utilisation de techniques de classification pour différencier les coquilles.</li>
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

  <p><strong>Technologies :</strong> Imagerie, MATLAB</p>

  <p><strong>Description :</strong> Développement d'un système de classification de coccinelles basé sur de l'apprentissage croisé. Trois critères ont été retenus : le nombre de points, la couleur, et la circularité. Réalisation d'une matrice de confusion pour rendre compte des résultats.</p>

  <p><strong>Compétences :</strong></p>
  <ul>
    <li><strong>Traitement d'image :</strong> Utilisation d'algorithmes pour analyser et classifier les images.</li>
    <li><strong>Vision par ordinateur :</strong> Mise en place de techniques pour la classification des objets.</li>
    <li><strong>Programmation en MATLAB :</strong> Développement d'algorithmes et d'applications.</li>
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

  <p><strong>Technologies :</strong> Python, Raspberry Pi, OpenCV</p>

  <p><strong>Description :</strong> Développement d'un système de vision par ordinateur pour suivre une balle en mouvement. L'ensemble réalisé sur Raspberry Pi.</p>

  <p><strong>Compétences :</strong></p>
  <ul>
    <li><strong>Traitement d'image :</strong> Capacité à utiliser des algorithmes pour analyser et traiter des images vidéo en temps réel.</li>
    <li><strong>Vision par ordinateur :</strong> Expertise en techniques de détection et de suivi d'objets.</li>
    <li><strong>Programmation en Python :</strong> Développement de scripts et d'applications pour le traitement des données d'image.</li>
    <li><strong>Déploiement sur Raspberry Pi :</strong> Installation, configuration et optimisation d'applications sur des micro-ordinateurs.</li>
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
            <p>Vous pouvez consulter mon <a href="documents/Arthur_Lamboley_CV.pdf" target="_blank">CV</a> et ma <a href="documents/Arthur_Lamboley_Lettre_de_Motivation.pdf" target="_blank">lettre de motivation</a> en cliquant sur les liens.</p>
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



