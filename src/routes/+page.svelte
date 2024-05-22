<script>
  let src1="src/routes/agnelli.jpg";
    import Navbar from "../lib/components/navbar.svelte";
    </script>
<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Lexend&display=swap" rel="stylesheet">
</svelte:head>

<Navbar/>
    <div class="container">
        <div class="item1">
            <h1 style="color: blue;">Presentazione</h1>
            <p id="demo">
           
        

                Benvenuti nel mio portfolio! Sono Marco Tranaso, sono nato il 30 novembre 2005 a
                 Torino. 
                 <br>
                 
                 Attualmente, frequento l'Istituto Internazionale Edoardo Agnelli. Ho 
                 creato questo spazio per condividere le mie esperienze e le attività che ho 
                 svolto nel corso degli anni nel campo dell'Educazione Civica. L'obiettivo 
                 principale di questo portfolio è quello di offrire un supporto non solo a me 
                 stesso, ma che possano essere di ispirazione 
                 e aiuto per chiunqu.
                 Durante il mio percorso scolastico, ho avuto l'opportunità di partecipare a numerose attività 
                 nelle varie materie. Nel mio portfolio troverete una vasta gamma di risorse, 
                 inclusi articoli, presentazioni, video e altro ancora. Ho cercato di rendere questi contenuti 
                 accessibili e utili. Spero che esplorando il mio portfolio possiate trovare informazioni
                  interessanti e stimolanti e vi invito a esplorare le diverse sezioni del portfolio. 
                  Spero che possiate trarre ispirazione da ciò che ho condiviso e che possiate trovare utili 
                  risorse per il vostro percorso di studio.Grazie per aver visitato il mio portfolio e
                   vi auguro una piacevole esperienza di apprendimento!
                   <br>
                   Cordiali saluti, Marco Tranaso
            </p>

            
        </div>
    </div>
<style>

:root{
  background-color: #333;
    color: white;
    font-family: 'Lexend', sans-serif;  
}
  
 
 ul {
  display: flex;
  justify-content: space-between;
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

li {
    float: left;
}

li a, .dropbtn {
    display: inline-block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s;
}

li a:hover, .dropdown:hover .dropbtn {
    background-color: red;
}

li.dropdown {
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color:#333;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
}

.dropdown-content a {
    color: white;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}

.dropdown-content a:hover {background-color: red}

.dropdown:hover .dropdown-content {
    display: block;
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
    max-width: 700px;
    background-color: #fff;
    color: #333;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
    margin-bottom: 20px;
  }
  .typing {
    height: 80vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .typing-effect {
    width: ch;
    animation: typing 2s steps(22), effect .5s step-end infinite alternate;
    white-space: nowrap;
    overflow: hidden;
    border-right: 3px solid;
    font-family: monospace;
    font-size: 2em;
  }
  
  @keyframes typing {
    from {
      width: 0;
    }
  }
      
  @keyframes effect {
    50% {
      border-color: transparent;
    }
  }
  html {
    scroll-behavior: smooth;
  }
  ::selection {
    background-color: green;
    color: #f1f1f1;
    
  }
  .img1{
      width: 350px;
      height: 250px;
      float: right;
    }
p{
  text-align:justify  
}
</style>