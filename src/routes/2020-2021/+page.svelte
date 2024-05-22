<script>
    import Navbar from "../../lib/components/navbar.svelte";
    let src1="/immagini/immagine1.png";
    let src2="/immagini/immagine2.png";
    let src3="/immagini/immagine3.jpeg";
    let src4="/immagini/immagine4.png";
    let src5="/immagini/covid19.png";

</script>
 <svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Lexend&display=swap" rel="stylesheet">

 </svelte:head> 
 <Navbar/>


  <div class="container">
    <div class="item1">
      <h1 style="color: blue;">Italiano</h1>
      <p>Durante l'anno 2020-2021 con la professoressa Randone abbiamo trattato molto l'argomento della migrazione
        approfondendo l'argomento con la lettura del libro "Le stelle di Lampedusa" e tramite l'incontro con
        l'autore.
        <br>
        Qui sotto vi lascio il riassunto del libro.
      </p>
      <div class="item6">
      <iframe
        src="https://docs.google.com/document/d/e/2PACX-1vQTqfys1JC0zlkcpKNXJacIMzmYzNuuOhCeWuYrmHJAiquXOb0V5HZpfpyAPuV7Eu2Pdn3H-yaGhbZr/pub?embedded=true"
        style="width:800px; height:800px; border: 1px solid black;"></iframe>
      </div>
      <p>
        Abbiamo avuto modo di leggere il libro "Le Stelle di Lampedusa" del dottor Pietro Bartolo, che ci ha fornito un toccante ritratto delle esperienze vissute dai residenti e dai migranti sull'isola. Inoltre, abbiamo visto il film "Fuocoammare" di Gianfranco Rosi, un documentario che descrive la vita quotidiana a Lampedusa e il dramma delle migrazioni attraverso testimonianze e immagini intense. Entrambe le opere ci hanno profondamente colpito, offrendo una comprensione più profonda della complessità e dell'umanità di questa situazione.
      </p>

      <iframe width="560" height="315" src="https://www.youtube.com/embed/eHEZwiyect4?si=V_rUy2TYYtoKbiQf&amp;start=5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
    
    <div class="item2">
      <a id="ciro"><h1 style="color: green;">Biologia</h1></a>
      <p> Durante l'anno 2020-2021 con la professoressa Nervo, ho avuto l'opportunità di approfondire, insieme alla
        professoressa Nervo,
        l'argomento del COVID-19, una pandemia che ha colpito l'intero mondo dall'inizio del 2020
      </p>
      <br>
      <div class="img-center">
      <img class="covid19" src={src5} alt="photo">
        <div class="container1">
          <div class="wrapper">
            <img class="img1" src={src1} alt="photo">
            <img class="img2" src={src2} alt="photo">
            <img class="img3" src={src3} alt="photo">
            <img class="img4" src={src4} alt="photo">
        </div>  
        </div>
      </div>

    </div>
    <div class="item3">
      <h1 style="color:lightblue">Diritto</h1>
      Durante l'anno 2020-2021 con la professoressa Foti, ognuno di noi studenti aveva la possibilità di scegliere un
      presidente italiano da studiare. Io ho optato per Luigi Einaudi, e ora voglio condividere con voi la mia
      presentazione.
      <br>
      <br>
      <iframe
        src="https://docs.google.com/presentation/d/e/2PACX-1vRHY_I5z4H7IE0mOH4oVZiPkKrG5bCsN0cvk-NZLrCxLNlPfJuAvb0r0mBxEj8NedLOoa06lmrR8DWH/embed?start=false&loop=false&delayms=3000"
        frameborder="0" allowfullscreen="true" mozallowfullscreen="true"
        webkitallowfullscreen="true">
      </iframe>

    </div>
    <div class="item4">
      
      <h1 style="color:purple">Chimica</h1>
    
   
    </div>

  </div>

  
<style>
    .item2 {
  height: 1300px;
}

iframe {
  width: 100%;
  height: 500px; 
  border: none;
  border-radius: 10px;
}

:root {
  background-color: #333;
  color: white;
  font-family: Arial, sans-serif;
}

.img-center {
  text-align: center;
}

html {
  scroll-behavior: smooth;
}

@media all and (max-width: 720px) {
  .item1,.item2,.item3,.item4,.item5,.item6 {
    width: 80%;
  }
}

::selection {
  background-color: green;
  color: #f1f1f1;
}

.container1 {
  width: 500px;
  height: 500px;
  transform: translate(-50%, -50%);
  margin-top: 350px;
  margin-left: 400px;
  overflow: hidden;
  border: 20px solid #ffffff;
  border-radius: 8px;
  box-shadow: 20px 50px 60px rgba(30, 30, 200, 0.3);
}

.wrapper {
  width: 100%;
  display: flex;
  animation: slide 8s infinite;
}

@keyframes slide {
  0% {
    transform: translateX(0);
  }

  25% {
    transform: translateX(0);
  }

  30% {
    transform: translateX(-100%);
  }

  50% {
    transform: translateX(-100%);
  }

  55% {
    transform: translateX(-200%);
  }

  75% {
    transform: translateX(-200%);
  }

  80% {
    transform: translateX(-300%);
  }

  100% {
    transform: translateX(-300%);
  }
}

img {
  width: 100%;
}

.img1 {
  object-fit: cover;
}

.img3 {
  width: 100%;
  object-fit: cover;
}

.img4 {
  width: 100%;
  object-fit: cover;
}

.covid19 {
  width: 600px;
  height: 450px;
}
  .container {
      display: flex;
      flex-wrap: wrap;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      margin-top: 20px;
    }
    
    .item1,.item2,.item3,.item4 {
      width: 100%;
      max-width: 800px;
      background-color: #fff;
      color: #333;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
      margin-bottom: 20px;
    }

    ::selection {
        background-color: green;
        color: #f1f1f1;
      }
      
      body{
        font-family: 'Lexend', sans-serif;
      }
      p{
      text-align: justify;
    }
</style>