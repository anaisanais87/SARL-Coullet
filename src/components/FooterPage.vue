<template>
  <div id="footer">
    <p> Copyright  &#169; SARL Coullet</p>
    <p>Mentions légales - Conditions générales d'utilisation</p>
  </div>
</template>

<script>

export default {
  name: "FooterPage",
};
</script>

<style>

#footer {
  margin-bottom: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 85px;
  /* background-color: #54d1e4; */
  background: #03224c;
  background: -webkit-linear-gradient(to right, #03224c, #0082c8, #0082c8, #03224c);
  background: linear-gradient(to right, #03224c, #0082c8, #0082c8, #03224c);
}

#footer p {
  color: #cdebf8;
  /* color: #444d5a; */
  font-size: 16px;
  text-align: center;
  margin: 0.5%;
}

</style>