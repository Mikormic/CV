<template>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <v-row>
        <div id="scroll_watcher"></div>
        <v-col>
            <div id="big-screen">
                <v-card id="miky" class="card">
                    <v-img class="pp" :width="100" src="../assets/icons8-son-goku-150.png"></v-img>
                    <h1 id="mike">MICKAËL</h1>
                    <h1>LESUEUR</h1>
                    <h4 id="h4A">ALTERNANCE MSC PRO</h4>
                    <h4>2025 - 2026</h4>
                    <h4>2026 - 2027</h4>
                    <h4>3 JOURS ENTREPRISES</h4>
                    <h4>2 JOURS ECOLES</h4>
                    <div id="roww" class="row"></div>
                    <div id="btnn">
                        <v-btn class="bg-blue-accent-1 text-center bouton"><a href="#info">INFORMATION</a></v-btn>
                        <v-btn class="bg-blue-accent-1 text-center bouton"><a href="#cali">QUALITÉS</a></v-btn>
                        <v-btn class="bg-blue-accent-1 text-center bouton"><a href="#centre">HOBBYS</a></v-btn>
                    </div>
                </v-card>
                <v-card id="exp" class="card">
                    <v-img class="pp" :width="200" src="../assets/Epitech.png"></v-img>
                    <h1 class="title-cv">EXPÉRIENCES PROFESSIONNELLES</h1>
                    <h3>Alternant Release and Build specialist Assistant | Ubisoft</h3>
                    <p class="date">Montreuil | Sep 2023 - Août 2024</p>
                    <ul>
                        <li>Développement d'applications web</li>
                        <li>Maintenance des outils déjà mis en place</li>
                        <li>Participation à des projets de développement</li>
                    </ul>
                    <h3>Assistant manager | Boulangerie Land & Monkeys</h3>
                    <p class="date">Paris | Déc 2021 - Sep 2022</p>
                    <ul>
                        <li>Accueil et service clientèle</li>
                        <li>Management d'une équipe et commande de produits</li>
                        <li>Gestion de la réserve, mise en place des produits Barista</li>
                    </ul>
                    <h3>Vendeur | Intersport</h3>
                    <p class="date">Torcy Bay 2 | Mars 2019 - Mars 2020</p>
                    <ul>
                        <li>Accueil et conseil client</li>
                        <li>Gestion de la caisse : encaissement, remboursement, compatge</li>
                        <li>Approvisionnement des rayons, réserves</li>
                    </ul>
                    <h3>Intérimaire | Carelec</h3>
                    <p class="date">Région parisienne | Juin 2018 - Mai 2019</p>
                    <ul>
                        <li>Vendeur : Conseil client, remise en état des rayons, gestion cabine</li>
                        <li>Manutentionnaire : réception et traitement des livraisons</li>
                        <li>Administratif : Carte employé, classement dossier, traitement papier</li>
                    </ul>
                    <h3>Vendeur | McDonald's</h3>
                    <p class="date">DisneyLand | Nov 2017 - Avril 2018</p>
                    <ul>
                        <li>Prise et préparation des commandes client</li>
                        <li>Préparation des produits en cuisine</li>
                        <li>Maintien de la propreté dans les espaces de travail</li>
                        <li>Travail d'équipe et prise d'initiative</li>
                    </ul>
                    <h1 class="title-cv">FORMATION</h1>
                    <h3>Développeur Web</h3>
                    <p class="date">Paris | Nov 2022 - Août 2024</p>
                    <p>WebAcademy by Epitech,</p>
                    <h3>Piscine 42</h3>
                    <p class="date">Paris | Sep - Oct 2022</p>
                    <p>Ecole 42</p>
                    <h3>Certificat Pro Technique de développement Web</h3>
                    <p class="date">Paris | Décembre 2020 - Mai 2021</p>
                    <p>Ecole Webforce 3</p>
                    <h3>Certification Bootcamp "Into Tech" Apprentissage métier du web</h3>
                    <p class="date">INCO Academy | Juillet - Août 2020</p>
                    <p> Projets réalisés: 3 sites internet sur wordpress, 1 portfolio</p>
                    <h3>Niveau Bac S</h3>
                    <p class="date">Champs-sur-marne | 2014 - 2017</p>
                    <p>Lycée René Descartes</p>
                    <h1 class="title-cv">COMPÉTENCES</h1>
                    <h3>Informatique:</h3>
                    <h3>Language:</h3>
                    <p>JavaScript, python, JAVA, Html, CSS, PHP, MySQL, C</p>
                    <h3>Framework:</h3>
                    <p>VUeJS, vuetify, Prime Vue, Tailwind CSS, React, Nodejs, MongoDB, Bootstrap, Jquery</p>
                    <h3>Bureautique:</h3>
                    <p>Windows, Linux, MAC OS</p>
                    <h3>Langues:</h3>
                    <p>Anglais B2</p>
                </v-card>
            </div>
            <v-card id="infor" class="card">
                <div class="row"></div>
                <h1 id="info">INFORMATIONS</h1>
                <h4>mickaël1.lesueur@epitech.eu</h4>
                <h4>0663828896</h4>
                <h4>Portfolio: <a class="link-info" href="https://mike-co.onrender.com/" target="_blank">mike-co.onrender.com</a></h4>
                <h4><a class="link-info" href="https://github.com/Mikormic/" target="_blank">github.com/Mikormic</a></h4>
                <h4>26 ans</h4>
                <div class="row"></div>
                <h1 id="cali">QUALITÉS</h1>
                <h1>PERSONELLES</h1>
                <h4>Polyvalent</h4>
                <h4>Résilient</h4>
                <h4>Esprit d'équipe</h4>
                <div class="row"></div>
                <h1 id="centre">CENTRE D'INTÉRÊTS</h1>
                <h4>Boxe, musculation</h4>
                <h4>Streamer Twitch</h4>
                <h4>Manga, Anime</h4>
                <div class="row"></div>
            </v-card>
            <a id="to-up" href="#miky"><img :width="50" src="../assets/icons8-double-haut-100.png" alt=""></a>
        </v-col>


    </v-row>
</template>

<style>
html {
    scroll-behavior: smooth;
}

body {
    font-family: "Montserrat", sans-serif;
}

#h4A {
    margin-top: 1vw
}

h4 {
    font-weight: 500;
}

h3 {
    color: #212121;
    margin-left: 3%;
    margin-bottom: 2vw;
    margin-top: 2vw
}
.link-info{
    color: #424242;
    font-weight: bold;
}
.date {
    color: #212121;
    font-weight: 600;
    text-align: end;
    margin-right: 3%;

}

p {
    color: #212121;
    margin-left: 3%;


}

li {
    color: #212121;
    padding-right: 10vw;
    margin-left: 3%;
    list-style: none;

}

.pp {
    margin: auto;
    margin-top: 5%;
    -webkit-animation: scale-in-ver-center 1s cubic-bezier(0.680, -0.550, 0.265, 1.550) both;
    animation: scale-in-ver-center 1s cubic-bezier(0.680, -0.550, 0.265, 1.550) both;
}

@-webkit-keyframes scale-in-ver-center {
    0% {
        -webkit-transform: scaleY(0);
        transform: scaleY(0);
        opacity: 1;
    }

    100% {
        -webkit-transform: scaleY(1);
        transform: scaleY(1);
        opacity: 1;
    }
}

@keyframes scale-in-ver-center {
    0% {
        -webkit-transform: scaleY(0);
        transform: scaleY(0);
        opacity: 1;
    }

    100% {
        -webkit-transform: scaleY(1);
        transform: scaleY(1);
        opacity: 1;
    }
}

.row {
    margin-top: 5%;
    margin-bottom: 5%;
    height: 1px;
    position: relative;
    left: 10vw;
    width: 80vw;
    background-color: #ffe7d4;
}

.title-cv {
    background-color: #ffe7d4;
    margin: 2%;
    padding-left: 5vw;
    width: 95vw;
    color: #424242;

}

#scroll_watcher {
    position: fixed;
    top: 0;
    background-color: #ffa600;
    transform-origin: left;
    z-index: 1000;
    width: 100%;
    height: 10px;
    scale: 0 1;
    animation: scroll-watcher linear !important;
    animation-timeline: scroll() !important;
}


@keyframes scroll-watcher {
    to {
        scale: 1 1;
    }
}

.bouton {
    margin-right: 5vw;
}

a:visited {
    text-decoration: none !important;
    color: #424242;
    font-weight: bold
}

a {
    text-decoration: none !important;
    color: #424242;
    font-weight: bold
}

#mike {
    margin-top: 2vw;
}

#to-up {
    position: fixed;
    bottom: 2vw;
    right: 5vw;
    background-color: transparent !important;
}

#miky {
    text-align: center;
    color: #ffe7d4;
    background-color: #5c76d1;
}

#exp {
    background-color: #F5F5F5;
    padding-bottom: 2vw;
}

#infor {
    text-align: center;
    color: #ffe7d4;
    background-color: #5c76d1;
}

#btnn {
    margin-bottom: 2%;
}

@media only screen and (max-width: 520px) {
    #btnn {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
    }

    .bouton {
        margin: auto;
        margin-top: 2%;
        margin-bottom: 1%;
    }

    .title-cv {
        margin-top: 10vw;
        margin-bottom: 10vw;
        font-size: 8vw;

    }

    h3 {
        margin-bottom: 5vw;
        margin-top: 5vw
    }

    ul {
        margin-top: 5vw;
        margin-bottom: 5vw;
    }

    .date {
        margin-top: 5vw;
        margin-bottom: 5vw;
    }

    .card {
        margin-bottom: 2vw;
    }
}

@media only screen and (min-width: 1024px) {
    #big-screen {
        display: flex;
    }

    #btnn {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        align-items: center;
        margin-left: 5vw;
    }

    .bouton {
        margin-top: 1vw;
    }

    #miky {
        width: 30vw;
    }

    #exp {
        width: 71vw;
        margin-right: 1vw
    }

    #infor {
        width: 100vw;
        background-color: #ee6363 !important;
    }

    #roww {
        margin-top: 2vw;
        margin-bottom: 2vw;
        height: 1px;
        position: relative;
        left: 0;
        width: 100vw;
        background-color: #ffe7d4;
    }

    .card {
        margin-bottom: 0;
    }
}
</style>