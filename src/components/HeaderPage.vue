<template>

  <div class="menu-header">

    <div>
      <img src="../assets/logo.svg" class="logo" />
      </div>

      <div>
        <nav>
          <ul class="nav1">
            <li>Accueil</li>
            <li>Nos services</li>
               <!-- <li>Location de bennes</li>
               <li>Terrassement</li>
               <li>Terre</li>
               <li>Produits de carrière</li> -->

            <li>Contact</li>
          </ul>
        </nav>
      </div>

  </div>

</template>

<script>
export default {
    name: "headerPage"
}
</script>

<style>

.menu-header {
  background: #03224c;
  background: -webkit-linear-gradient(to right, #03224c, #0082c8, #0082c8, #03224c);
  background: linear-gradient(to right, #03224c, #0082c8, #0082c8, #03224c);
}

.logo {
  width: 350px;
  padding-left: 1%;
  padding-top: 1%;
  margin: auto;
  display: block;
}

ul {
  list-style: none;
}

.nav1 {
  display: flex;
  justify-content: space-around;
  margin-bottom: 0;
  padding-right: 7%;
   /* background: url('../assets/separateur.png') repeat-x bottom; */
}

li {
  color:#cdebf8;
  /* color: #444d5a; */
  font-size: 20px;
  padding-top: 5%;
  padding-bottom: 5%;
}
</style>