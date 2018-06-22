<template>
  <div id="app">
    <h1>Welcome To Burro's Website</h1>
    <img src="./assets/zack.gif"></img>
    <img src="./assets/ed.gif"></img>
    <img src="./assets/matt.gif"></img>
    <img src="./assets/tyler.gif"></img>
    </br>
    </br>
    </br>
    <p>Burro is a rock n' roll band from Sacramento, CA! We are available for events/parties/concerts in and around the greater Sacramento area! Come see us live acoustic under highway 160 every Thursday afternoon!</p>
    </br>
    <a href="https://www.facebook.com/BURROvision/">Like us on Facebook!</a>
    </br>
    </br>
    </br>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/46-28MU3-X0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
    <h2>Pre-pre-order our new-ish CD, "Muck O'Clock", soon!</h2>
    <br>
    <img src="./assets/buck.gif"></img>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
    }
  }
}
</script>

<style lang="scss">
iframe {
  border-style: double;
  border-width: 5px;
}
h2 {
  background-color: orange;
}
p {
  background-color: black;
}
h1 {
  background-color: blue;
}
a {
  font-size: 20px;
  font-weight: 1000;
  color: yellow;
  background-color: green;
  padding: 10px;
}
body {
  background-attachment: fixed;
  background-image: url("./assets/burrologo.jpg");
  background-color: black;
  color: white;
  text-align: center;
}
img {
  border-style: double;
  border-width: 5px;
}
#app {
}

</style>
