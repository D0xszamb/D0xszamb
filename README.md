
<!DOCTYPE html>
<html lang="lt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kontaktų Blokas</title>
    <style>
        
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        .kontaktai {
            border: 1px solid #ddd;
            padding: 15px;
            border-radius: 5px;
            background-color: #f9f9f9;
        }
        .kontaktai h2 {
            margin-top: 0;
        }

    </style>
</head>
<body>
    <div class="kontaktai" id="kontaktai"></div>

    <script>

        let vardas = "Dominykas";
        let pavarde = "Šambarys";
        let elPastas = "dominykas.sambarys@stud.ktmc.lt";
        let telefonoNumeris = "+370 681 42619";
        let adresas = "Baltijos pr., 7-76, Klaipėda";
        let pastoKodas = "12345";
        let komentaras = "Susisiekti dėl bendradarbiavimo galimybių.";

        let kontaktuBlokas = `
            <h2>Kontaktai:</h2>
            <p><strong>Vardas:</strong> ${vardas}</p>
            <p><strong>Pavardė:</strong> ${pavarde}</p>
            <p><strong>El. pašto adresas:</strong> ${elPastas}</p>
            <p><strong>Telefono numeris:</strong> ${telefonoNumeris}</p>
            <p><strong>Adresas:</strong> ${adresas}</p>
            <p><strong>Pašto kodas:</strong> ${pastoKodas}</p>
            <p><strong>Komentaras:</strong> ${komentaras}</p>
        `;

        document.getElementById('kontaktai').innerHTML = kontaktuBlokas;
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="lt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prekės Blokas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .preke {
            border: 1px solid #ddd;
            padding: 15px;
            border-radius: 5px;
            background-color: #f9f9f9;
            max-width: 300px;
        }
        .preke img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .preke h2 {
            margin-top: 0;
        }
        .preke p {
            margin: 5px 0;
        }
        .preke a {
            text-decoration: none;
            color: #007bff;
        }
        .preke a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="preke" id="prekesBlokas"></div>

    <script>
        let prekesPavadinimas = "Samsung Galaxy S24 Ultra 5G 12GB/512GB Titanium Black";
        let kainaEurais = 1249;
        let trumpasAprasymas = "Tikėtina, kad „Galaxy S24 Ultra“ turės didelį ir aukštos kokybės AMOLED ekraną, galbūt su 120 Hz arba 144 Hz atnaujinimo dažniu ir dideliu raiškos lygiu, pavyzdžiui, 2K arba 4K. Ekrano dydis gali siekti apie 6,8-7 colius.Naujausias „Exynos“ ar „Snapdragon“ procesorius priklausomai nuo rinkos, kuris užtikrins greitą našumą ir efektyvumą.„Ultra“ serijos modeliai dažnai pasižymi pažangiausiais kameros moduliais. Galima tikėtis, kad „S24 Ultra“ turės keturių ar daugiau kamerų, įskaitant 200 MP pagrindinę kamerą, plačiakampę, teleobjektyvą ir galbūt periskopinį objektyvą su dideliais optiniais priartinimo gebėjimais. Modelis gali pasiūlyti įvairius variantus, nuo 12 GB RAM iki 16 GB RAM ir 256 GB iki 1 TB vidinės atminties, priklausomai nuo konfigūracijos. Akumuliatorius greičiausiai bus apie 5000-6000 mAh su greitu įkrovimu, galbūt iki 45W arba daugiau, ir galbūt belaidžiu įkrovimu bei atvirkštiniu įkrovimu. „Galaxy S24 Ultra“ veiks su naujausia „Android“ versija ir „One UI“ sąsaja, kuri suteiks įvairias pritaikymo galimybes ir papildomas funkcijas. Priklausomai nuo modelio, jis gali būti pagamintas iš aukštos kokybės medžiagų, tokių kaip stiklas ir metalas, ir turėti IP68 atsparumo vandeniui bei dulkėms klasę. Tikėtina, kad bus palaikoma 5G, Wi-Fi 6E arba 7, Bluetooth 5.3, stereo garsiakalbiai, ir gali būti įdiegtas S Pen.";
        let paveikslėlioNuoroda = "https://www.technorama.lt/6111112-large_default/ismanusis-telefonas-samsung-galaxy-s24-ultra-5g-12gb-512gb-titanium-black.jpg";
        let prekesNuoroda = "https://www.technorama.lt/telefonai/1571122-ismanusis-telefonas-samsung-galaxy-s24-ultra-5g-12gb-512gb-titanium-black-8806095308180.html";

        let prekesBlokas = `
            <h2>${prekesPavadinimas}</h2>
            <p><strong>Kaina:</strong> €${kainaEurais}</p>
            <p><strong>Aprašymas:</strong> ${trumpasAprasymas}</p>
            <a href="${prekesNuoroda}" target="_blank">
                <img src="${paveikslėlioNuoroda}" alt="${prekesPavadinimas}">
            </a>
            <p><a href="${prekesNuoroda}" target="_blank">Žiūrėti daugiau informacijos</a></p>
        `;

        document.getElementById('prekesBlokas').innerHTML = prekesBlokas;
    </script>
</body>
</html>


<!DOCTYPE html>
<html lang="lt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kvadratinės Lygties Apskaičiavimas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .lygties-blokas {
            border: 1px solid #ddd;
            padding: 15px;
            border-radius: 5px;
            background-color: #f9f9f9;
            max-width: 500px;
        }
        .lygties-blokas h2 {
            margin-top: 0;
        }
    </style>
</head>
<body>
    <div class="lygties-blokas" id="lygtiesBlokas"></div>

    <script>
       
        let a = 1;  
        let b = -3;
        let c = 2; 


        let lygtiesIsvedimas = `${a}x² + ${b}x + ${c} = 0`;


        let diskriminantas = (b * b) - (4 * a * c);
        

        let diskriminantoIsvedimas = `D = ${b}² - 4(${a})(${c}) = ${diskriminantas}`;

        let x1, x2, x1Isvedimas, x2Isvedimas;
        if (diskriminantas >= 0) {
            x1 = (-b + Math.sqrt(diskriminantas)) / (2 * a);
            x2 = (-b - Math.sqrt(diskriminantas)) / (2 * a);

            x1Isvedimas = `x1 = (-${b} + √${diskriminantas}) / (2 * ${a}) = ${x1.toFixed(2)}`;
            x2Isvedimas = `x2 = (-${b} - √${diskriminantas}) / (2 * ${a}) = ${x2.toFixed(2)}`;
        } else {
            x1Isvedimas = x2Isvedimas = "Nėra realių sprendinių";
        }


        let isvedimas = `
            <h2>Kvadratinės Lygties Išvedimas ir Apskaičiavimas</h2>
            <p>Lygtis: ${lygtiesIsvedimas}</p>
            <p>${diskriminantoIsvedimas}</p>
            <p>${x1Isvedimas}</p>
            <p>${x2Isvedimas}</p>
        `;

        document.getElementById('lygtiesBlokas').innerHTML = isvedimas;
    </script>
</body>
</html>
