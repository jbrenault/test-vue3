<template>
  <pc-configurator-header configurator-name="gate and fence"></pc-configurator-header>
  <pc-selectable-model
      id="dumb"
      label="dumb"
      img-src="https://www.francetvinfo.fr/pictures/si9iFOPV1UO8tFtNS10SPe3-MQM/1500x843/2016/08/23/internet-troll.jpg"
      img-alt="gate default"
      miscellaneous="à partir de"
      pricing="1549.00€"
  >
    <div slot="title">Babord - Coulissant aspect 2 vantaux</div>
    <div slot="subtitle">Aluminium · Semi-ajouré</div>
    <div slot="content">
      Hauteur : min 751 - max 3052 mm <br />
      Largeur : min 751 - max 3052 mm
    </div>
  </pc-selectable-model>
</template>

<script>


export default {
  name: 'App',
  components: {

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
