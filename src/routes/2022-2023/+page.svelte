<script>
    import Navbar from "../../lib/components/navbar.svelte";


</script>
<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Lexend&display=swap" rel="stylesheet">

</svelte:head>
<Navbar/>
  <div class="container">                                                  
    <div class="item1">
      <h1 style="text-align:cen ter; color: blue;">Tpsi</h1>
      <p>Durante l'anno 2022-2023 con il professore Mancuso, abbiamo avuto l'opportunità di scrivere un articolo per il suo blog personale specializzato nell'ambito dell'informatica. Dopo aver completato la stesura del nostro articolo, la docente di italiano ha corretto il testo, apportando eventuali correzioni e suggerimenti. Successivamente, abbiamo pubblicato l'articolo nel blog utilizzando il linguaggio di <a target="_blank" href="https://it.wikipedia.org/wiki/Markdown">Markdown</a>.
        <br>
        <br>
      </p>
      
        <iframe src="https://profmancusoa.github.io/blog/le-criptovalute-e-il-mining/" ></iframe>
    </div>
    <div class="item2">
     <a id="ciro"> <h1 style="text-align:center; color: blue;">Italiano</h1></a>  
      <p>Durante l'anno 2020-2021, insieme alla professoressa Giannatasio, abbiamo affrontato il tema della mafia e delle persone che si sono opposte ad essa. Ogni studente ha avuto l'opportunità di scegliere una figura che ha combattuto contro la mafia, e io ho deciso di approfondire la vita di Rocco Chinnici. Ora desidero condividere con voi la mia presentazione.
      </p>
      <br>
      <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRMPRSAzAAG65zFSAO4vuq0l9m3OqlYBcw3juwVeS_aB6dEClcOsl9PJ-OczxugH1UXbziArSO6dKtI/embed?start=false&loop=false&delayms=3000" frameborder="0" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
    </div>
    <div class="item3">
      <h1 style="text-align:center; color: blue;" id="3">Telecomunicazioni</h1>
      <p>Durante l'anno 2022-2023, con il professore Cadili, abbiamo avuto l'opportunità di approfondire una componente elettronica a nostra scelta e svolgere una presentazione. Ho deciso di concentrarmi sul tema dei condensatori e qui sotto vi lascio la mia presentazione.
        
      </p>
      <br>
      <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQb7hpdk2IC53vJh8f6sggrbFSqr-g-M1vghIT6s9AHRM3gjiNP6SsLBimVvW6KTYHZ-l1F_qjVLPCY/embed?start=false&loop=false&delayms=3000" frameborder="0" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
    </div>
  </div>

  <style>
    iframe {
  width: 100%;
  height: 600px;
  border: none;
  border-radius: 10px;
}

:root {
  background-color: #333;
  color: white;
  font-family: 'Lexend', sans-serif;
}

@media all and (max-width: 720px) {
  .item1,.item2,.item3 {
    width: 80%;
  }
}

iframe {
  width: 100%;
  height: 500px;
  border: none;
  border-radius: 10px;
}
html{
  scroll-behavior:smooth;
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

    html{
      scroll-behavior: smooth;
    }
    p{
      text-align: justify;
    }
  </style>