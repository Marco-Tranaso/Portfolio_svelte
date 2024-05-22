<script>
    import Navbar from "../../lib/components/navbar.svelte";
    let src1="/immagini/9788806252793_0_536_0_75.jpg"
    let src2="/immagini/064416074-2639e960-15f0-42a9-9acc-2d3c09493308.jpg"
</script>

<svelte:head>
    <link
        href="https://fonts.googleapis.com/css2?family=Lexend&display=swap"
        rel="stylesheet"
    />
</svelte:head>
<Navbar />
<body>
    <div class="container">
        <div class="item1">
            <a id="1"
                ><h1 style="text-align:center; color: blue;">
                    Educazione Civica
                </h1></a
            >
            <p>
                Durante l'anno accademico 2023-2024, insieme alla
                professoressa Giannatasio, abbiamo approfondito il tema 
                dei gulag e dei campi di concentramento, esaminando con
                attenzione le dure realtà vissute dai prigionieri all'interno di
                tali struttura penitenziarie. Abbiamo esplorato in dettaglio le
                condizioni disumane in cui erano costretti a sopravvivere,
                cercando di comprendere le implicazioni storiche, sociali e
                umane di questi luoghi oscuri della storia.
                <br>
                Per ulteriori approfondimenti su questo tema, vi invito a consultare il seguente video: 
            
            </p>
            

            <iframe
                width="560"
                height="315"
                src="https://www.youtube.com/embed/SKOP830ETKk?si=UsrV-87oaZgUiGKH"
                title="YouTube video player"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                referrerpolicy="strict-origin-when-cross-origin"
                allowfullscreen
            ></iframe>

            <div class="container_italiano">
            <p class="item_italiano" style="width: 420px; text-align:justify:">
                Inoltre, abbiamo avuto la fortuna di incontrare Benedetta Tobagi per discutere degli "anni di piombo", un periodo di intensa violenza politica in Italia dagli anni '60 agli anni '80. Benedetta Tobagi, figlia del giornalista assassinato Walter Tobagi, ha esplorato questo periodo nel suo libro "Come mi batte forte il tuo cuore", che abbiamo avuto il privilegio di leggere. 
                
        Abbiamo anche dedicato un'importante parte del nostro tempo alla situazione carceraria in Italia durante un incontro con Cosima Buccoliero, ex direttrice del carcere di Torino.
        Inoltre, abbiamo esplorato il libro "Senza sbarre", che ci ha regalato uno sguardo intimo e rivelatore sulla vita dietro le sbarre.

        
            </p>

            <div class="item_italiano"><img class="img1" src={src1}></div>
        </div>

<br>
<p>
        Infine, abbiamo trattato il tema della legge Basaglia e degli ospedali psichiatrici in Italia. Prima della promulgazione della legge Basaglia nel 1978, 
gli ospedali psichiatrici nel nostro paese erano famigerati per il sovraffollamento, gli abusi e i trattamenti inumani. 
I pazienti erano segregati e privati della loro dignità e delle opportunità di riabilitazione. 
    La legge Basaglia ha segnato una svolta abolendo gli ospedali psichiatrici e promuovendo un approccio più umano e comunitario alla salute mentale.
            </p>
            <img class="img2" src={src2}>
        </div>
        
        <div class="item2">
            <h1 style="text-align:center; color: blue;">Inglese</h1>
            <p>
                Durante l'anno accademico 2023-2024, insieme alla professoressa
                Pantos, abbiamo avuto l'opportunità di affrontare in modo
                approfondito il tema dei rischi e dei pericoli legati all'uso
                della tecnologia. È stata organizzata una serie di presentazioni
                in cui ogni studente della classe doveva esporre e analizzare i
                vari rischi associati all'utilizzo della tecnologia. Questa
                iniziativa ha consentito agli studenti di esaminare criticamente
                gli impatti negativi della tecnologia sulla società,
                sottolineando l'importanza di un utilizzo responsabile e
                consapevole delle risorse tecnologiche a nostra disposizione.
            </p>
            <br />
            <iframe
                title="Presentazione"
                src="https://docs.google.com/presentation/d/e/2PACX-1vRhQPz9qGuOcfqt54N-VXJt3EnbajLyIUoDz7x8f3ZzT1PsoIFXuwtrGFLhzntuUaXIN-knMKyVdJeW/embed?start=false&loop=false&delayms=3000"
                frameborder="0"
                allowfullscreen="true"
                mozallowfullscreen="true"
                webkitallowfullscreen="true"
                
            ></iframe>
        </div>
    </div>
</body>

<style>
     p{
      text-align: justify;
    }
    .img1{
        margin-top: 15px;
        margin-left: 90px;
        width: 200px;
        height: 329px;
    }
    .img2{
        display: block;
        margin: 0 auto;
    }
    .item_italiano{
        
    }
    .container_italiano{
        display: flex;
    
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
        .item2 {
            width: 80%;
        }
    }

    iframe {
        width: 100%;
        height: 500px;
        border: none;
        border-radius: 10px;
    }
    body {
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
    .item2 {
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
</style>
