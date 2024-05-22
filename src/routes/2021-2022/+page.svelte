<script>
  import Navbar from "../../lib/components/navbar.svelte";
  export let immagine1="/immagini/Donne-che-manifestano-per-una-giusta-causa.jpg"
</script>

<svelte:head>
  <link
    href="https://fonts.googleapis.com/css2?family=Lexend&display=swap"
    rel="stylesheet"
  />
</svelte:head>
<Navbar />
<div class="container">
  <div class="item1">
    <h1 style="color: blue;">Informatica</h1>
    <p>
      Durante l'anno 2021-2022 con la professoressa Arruzza, abbiamo dedicato
      del tempo all'approfondimento del tema della sicurezza online. Come parte
      di questo percorso di apprendimento, ci è stato assegnato il compito di
      creare una presentazione Power Point per condividere ciò che abbiamo
      imparato.
      <br />
      Qui sotto vi lascio la mia presentazione
    </p>
    <iframe
      src="https://docs.google.com/presentation/d/e/2PACX-1vT23ZFWOKAjX1ZqYNfJ9acINdi8HdZh4JxXkqjZ7Hm8fybWfbLrQlYPDYq6ORzGCv5LVWvfkS8o2TiJ/embed?start=false&loop=false&delayms=3000"
      frameborder="0"
      width="100%"
      height="450px"
      allowfullscreen="true"
      mozallowfullscreen="true"
      webkitallowfullscreen="true"
    ></iframe>
  </div>
  <div class="item3">
    <h1 style="color: blue;">Italiano</h1>
    <p>
      Durante l'anno 2021-2022 con la professoressa Maura Giannatasio, abbiamo esplorato due temi di grande rilevanza:
      la mafia e l'emancipazione femminile.
      Abbiamo dedicato particolare attenzione al tema della mafia, concentrandoci su due tragici eventi che hanno profondamente segnato l'Italia: la strage di Capaci, che ha causato la morte del giudice Giovanni Falcone, e quella di via D'Amelio, in cui ha perso la vita Paolo Borsellino.
      Grazie alla professoressa abbiamo avuto l' opportunità di intervistare Salvatore Borsellino, fratello di uno dei due valorosi magistrati uccisi nella lotta contro la mafia. L'intervista è stata un'occasione straordinaria per approfondire la nostra comprensione di questi tragici eventi e delle loro ripercussioni sulla società italiana.
      <br />
      <br>
      Qui sotto vi lascio l'intervista a Salvatore Borsellino.
    </p>
    <br>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/b3_VRm8kE8E?si=NFBCWLKIvjyin5x4&amp;start=5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

    <br>
    <p>
      Nell'ambito dell'emancipazione femminile, abbiamo approfondito il ruolo fondamentale del movimento per i diritti delle donne e l'importanza del "Codice Rosso". 
      Questo codice rappresenta un significativo progresso nella protezione dei diritti delle donne in Italia, 
      concentrandosi sulla prevenzione e il contrasto della violenza di genere.
       Il "Codice Rosso" prevede misure più rapide ed efficaci per affrontare le denunce di
        violenza domestica e sessuale, garantendo che le vittime ricevano un immediato supporto
         e protezione. Abbiamo esaminato come questa legislazione sia stata accolta nella società italiana 
         e il suo impatto nel promuovere una maggiore consapevolezza e responsabilità riguardo ai diritti delle donne.
    </p>
    <img class="donna" src={immagine1}>
  </div>
</div>

<style>
  .donna{
    display: block;
    margin: auto                                                                                                                                                                        ;
    width: 726px;                                                                           
    height: 408px;
  }           
  iframe {
    width: 100%;
    height: 600px;
    border: none;
    border-radius: 10px;
  }

  :root {
    background-color: #333;
    color: white;
    font-family: "Lexend", sans-serif;
  }

  @media all and (max-width: 720px) {
    .item1,
    .item2,
    .item3 {
      width: 80%;
    }
  }

  iframe {
    width: 100%;
    height: 500px;
    border: none;
    border-radius: 10px;
  }
  html {
    scroll-behavior: smooth;
  }

  .container {
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 20px;
  }

  .item1,
  .item2,
  .item3,
  .item4 {
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

  body {
    font-family: "Lexend", sans-serif;
  }
  p{
      text-align: justify;
    }
</style>
