<template>
  <div class="home">
    <headerPage></headerPage>

    <div id="photo-wall">
      <h1>Entreprise familiale</h1>
      <h2>depuis 1975</h2>
      <div class="tel">
      <img src="../assets/phone.svg" width="30px" class="phone"/><p>06 16 90 80 42</p>
      </div>
    </div>

    <p>
      Nore entreprise familiale SARL COULLET est implantée à Sanary depuis 1975, notre secteur d’activité se porte essentiellement
      autour du transport (matériaux, engins, etc.), de la location de bennes
      (tous déchets, plusieurs cubages possibles), du terrassement (fouille,
      enrochement, chemin, tranchées, etc.) et de la vente de divers produits
      livrés (terre, produits de carrière, remblais, etc.).
    </p>
    <p>
      De plus, nos camions étant de taille modeste, nous sommes en mesure de
      passer dans des lieux étroits (ruelles, portails étroits, etc.).
    </p>

    <img src="../assets/camion.jpg" class="photo-camion"/>


      <div class="btn">
      <button class="services">
        <p>Nos Services</p>
        <img src="../assets/fleche1.svg" class="arrow" />
      </button>
      </div>


    <!-- <div class="contact">
      <h2>SARL COULLET</h2>
      <p>Port : 06 16 90 80 42</p>
      <p>Fax : 04 94 74 49 98</p>
    </div> -->

    <footerPage></footerPage>
  </div>
</template>

<script>
import HeaderPage from "./HeaderPage.vue";
import FooterPage from "./FooterPage.vue";

export default {
  name: "homePage",

  components: {
    headerPage: HeaderPage,
    footerPage: FooterPage,
  },
};
</script>

<style>
@font-face {
  font-family: "Montserrat";
  src: url("../fonts/Montserrat-Regular.eot");
  src: url("../fonts/Montserrat-Regular.eot?#iefix") format("embedded-opentype"),
    url("../fonts/Montserrat-Regular.woff2") format("woff2"),
    url("../fonts/Montserrat-Regular.woff") format("woff"),
    url("../fonts/Montserrat-Regular.ttf") format("truetype"),
    url("../fonts/Montserrat-Regular.svg#Montserrat-Regular") format("svg");
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: "Montserrat";
  src: url("../fonts/Montserrat-Bold.eot");
  src: url("../fonts/Montserrat-Bold.eot?#iefix") format("embedded-opentype"),
    url("../fonts/Montserrat-Bold.woff2") format("woff2"),
    url("../fonts/Montserrat-Bold.woff") format("woff"),
    url("../fonts/Montserrat-Bold.ttf") format("truetype"),
    url("../fonts/Montserrat-Bold.svg#Montserrat-Bold") format("svg");
  font-weight: bold;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: "Montserrat";
  src: url("../fonts/Montserrat-Italic.eot");
  src: url("../fonts/Montserrat-Italic.eot?#iefix") format("embedded-opentype"),
    url("../fonts/Montserrat-Italic.woff2") format("woff2"),
    url("../fonts/Montserrat-Italic.woff") format("woff"),
    url("../fonts/Montserrat-Italic.ttf") format("truetype"),
    url("../fonts/Montserrat-Italic.svg#Montserrat-Italic") format("svg");
  font-weight: normal;
  font-style: italic;
  font-display: swap;
}

@font-face {
  font-family: "Courgette";
  src: url("../fonts/Courgette-Regular.eot");
  src: url("../fonts/Courgette-Regular.eot?#iefix") format("embedded-opentype"),
    url("../fonts/Courgette-Regular.woff2") format("woff2"),
    url("../fonts/Courgette-Regular.woff") format("woff"),
    url("../fonts/Courgette-Regular.ttf") format("truetype"),
    url("../fonts/Courgette-Regular.svg#Courgette-Regular") format("svg");
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

html {
  font-family: "Montserrat";
}

#photo-wall h1 {
  color: #03224c;
  font-size: 32px;
  padding-top: 120px;
  margin-top: 0;
  text-align: center;
}
#photo-wall h2 {
  color: #03224c;
  font-size: 32px;
  margin-top: 0;
  margin-bottom: 0;
  text-align: center;
  font-family: "Courgette";
}

#photo-wall p {
  color: #03224c;
  font-size: 28px;
  text-align: center;
}

#photo-wall {
  width: 450px;
  height: 380px;
  background: url(../assets/mur-pierre2.jpg) no-repeat;
  background-size: cover;
}

.tel {
  display: flex;
}

.phone {
  margin-left: 90px;
}

.home p {
  color: #03224c;
  font-size: 18px;
  text-align: justify;
  margin-top: 8%;
  margin-bottom: 8%;
  padding-left: 4%;
  padding-right: 4%;
}

.photo-camion {
  overflow:hidden;
    -webkit-border-radius:350px;
    -moz-border-radius:350px;
    border-radius:350px;
    width:350px;
    height:350px;
    margin: auto;
    display: block;
}


.btn {
  padding-top: 30px;
  padding-bottom: 30px;
}

.services {
  background-color: white;
  width: 300px;
  display: flex;
  margin: auto;
  border-radius: 8px;
  /* box-shadow: 5px 5px 5px#192A48; */
  color: #192a48;
  border: solid #192a48 0.5px;
  cursor: pointer;
}

.services p {
  font-size: 24px;
  margin: 0;
  padding: 10px 16px 10px 16px;
  font-weight: bold;
  color: #03224c;
}

.arrow {
  width: 15px;
  margin-top: 17px;
  padding-left: 30%;
}

.services:hover {
  transform: scale(1.05);
  transition-duration: 400ms;
}

.contact {
  margin-bottom: 40px;
}
.contact h2{
  text-align: center;
  margin-bottom: 10px;
  margin-top: 40px;
}

.contact p {
  margin: 0;
  text-align: center;
}
</style>