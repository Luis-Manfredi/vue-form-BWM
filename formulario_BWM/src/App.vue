<script setup>
  import introduction from "./components/form_introduction.vue";
  import business from "./components/form_business_root.vue";
</script>

<template>
  <div class="margin">
    <div class="container">
    
      <div class="intro-container">
        <!-- <img 
          src="\src\assets\logo-bw white.png" 
          alt="logo-bw" 
          class="logo-bw"> -->
        <div class="hero-text">
          <img 
          src="\src\assets\logo-bw white.png" 
          alt="logo-bw" 
          class="logo-bw">
          <h3>¡En Bestway Marketing estamos encantados de trabajar contigo!</h3>
          <p>Puedes visitar nuestra página web para explorar otras soluciones al hacer click en el siguiente botón</p>
          <button>Ir a web</button>
        </div>
        <!-- <div style="height: 300px"></div> -->
      </div>

      <!-- <introduction message="¡A conocernos a fondo!"/> -->

      <business title="Cuéntanos de tu marca" />

    </div>
  </div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Roboto&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

  * {
    font-family: 'Roboto', sans-serif;
  }

  body {
    margin: 0;
    padding: 0;
    min-height: 100vh;
    min-width: 100vw;
    overflow: hidden;
    background-color: whitesmoke;
  }

  h1, h2, h3 {
    font-family: 'Bebas Neue', cursive;
    font-family: 'Roboto', sans-serif;
  }

  button {
    margin: 10px auto;
    width: 150px;
    height: 40px;
    background-color: rgba(255, 255, 255, 0.2);
    border-radius: 8px;
    border-width: 1px;
    border-color: white;
    border-style: solid;
    color: white;
    cursor: pointer;
    font-size: 16px;
    transition: 0.3s;
  }

  button:hover {
    background-color: white;
    color: #02aba4;
    font-weight: bold;
  }

  .submit_btn {
    border-color: #02aba4;
    color: #02aba4;
    border-width: 2px;
  }

  .submit_btn:hover {
    background-color: #02aba4;
    color: white;
  }

  .margin {
    display: flex;
    justify-content: center;
    min-height: 100vh;
  }

  .container {
    display: flex;
    margin: auto;
    background-color: white;
    height: 90vh;
    width: 1200px;
    border-radius: 20px;
    box-shadow: 0px 2px 4px 4px rgba(0, 0, 0, 0.1);
  }

  .intro-container {
    position: relative;
    height: 100%;
    width: 600px;
    /* background-color: #02aba4; */
    background-image: linear-gradient(rgba(28, 196, 176, 0.7), rgba(28, 196, 176, 0.7)), 
    url('C:\Users\Manfre\Desktop\Development\web\Formulario_BWM\formulario_BWM\src\assets\teamwork.jpg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    border-top-left-radius: 20px;
    border-bottom-left-radius: 20px;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .hero-text {
    width: 300px;
    padding: 10px;
    color: white;
    margin: auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
  }

  .logo-bw {
    margin: 0 auto;
    height: 300px;
    width: 300px;
  }

</style>
