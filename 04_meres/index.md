<html lang="en-US">

  <head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width,maximum-scale=2">
    <link rel="stylesheet" type="text/css" media="screen" href="/jegyzokonyv/assets/css/style.css?v=fd8824f5d621979eab4af03bf6a18efe7538639e">

  </head>

  <body>

<h1 id="mérési-jegyzőkönyv">MÉRÉSI JEGYZŐKÖNYV</h1>

<p><strong>A mérést végző neve:</strong> Mercz Noel<br />
<strong>A mérés tárgya:</strong> Frekvencia vs. Moduláció mérés</p>

<p><strong>A mérés száma:</strong> 4. mérés<br />
<strong>A mérés dátuma:</strong> 2024. 11. 20.<br />
<strong>A mérést vezette:</strong> Sándor Péter</p>

<p><strong>Évfolyam:</strong> 13. E<br />
<strong>Csoport:</strong> GYAK 2<br />
<strong>Helyszín:</strong> V3 Labor</p>

<hr />

<h1 id="mérési-jegyzőkönyv-1">Mérési Jegyzőkönyv</h1>

<h2 id="1-mérés-célja">1. Mérés Célja</h2>
<p>A mérés célja a <strong>Johansson 8202 DVB-T modulátor</strong> működésének megismerése, konfigurációjának tesztelése, valamint a METEK HD spektrum- és jelszintanalizátor használatával a modulátor által generált jel paramétereinek mérése. A mért paraméterek: <strong>jelszint</strong>, <strong>bitsebesség</strong>, <strong>MER (Modulation Error Rate)</strong>.</p>

<hr />

<h2 id="2-használt-eszközök">2. Használt Eszközök</h2>

<table>
  <thead>
    <tr>
      <th>Eszköz</th>
      <th>Típus</th>
      <th>Funkció</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Johansson 8202</td>
      <td>DVB-T modulátor</td>
      <td>Bitsebesség és jelminőség vizsgálata</td>
    </tr>
    <tr>
      <td>RF kábel</td>
      <td>Koaxiális kábel</td>
      <td>Modulátorok és spektrumanalizátor összekötése</td>
    </tr>
    <tr>
      <td>Metek HDD</td>
      <td>Spektrum/jelszint analizátor</td>
      <td>Frekvencia, moduláció, sávszélesség, jelszint, MER és bitsebesség mérése</td>
    </tr>
  </tbody>
</table>

<hr />

<h2 id="3-beállítások">3. Beállítások</h2>
<ul>
  <li><strong>Frekvencia</strong>: 474 MHz</li>
  <li><strong>Sávszélesség</strong>: 8 MHz</li>
  <li><strong>Modulációs típusok tesztelése</strong>:
    <ul>
      <li>QPSK</li>
      <li>16QAM</li>
      <li>64QAM</li>
    </ul>
  </li>
</ul>

<hr />

<h2 id="4-mérési-eredmények">4. Mérési Eredmények</h2>
<p>Az alábbi táblázatban összefoglaljuk a mérések eredményeit különböző modulációs beállítások mellett.</p>

<table>
  <thead>
    <tr>
      <th><strong>Moduláció</strong></th>
      <th><strong>Jelszint [dBm]</strong></th>
      <th><strong>Bitsebesség [Mbps]</strong></th>
      <th><strong>MER [dB]</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>QPSK</td>
      <td>-19.2 dBm</td>
      <td>3.2 - 3.9 Mbps</td>
      <td>39.7 dB</td>
    </tr>
    <tr>
      <td>16QAM</td>
      <td>-30.1 dBm</td>
      <td>7.5 - 9.1 Mbps</td>
      <td>33.2 dB</td>
    </tr>
    <tr>
      <td>64QAM</td>
      <td>-30.5 dBm</td>
      <td>11.4 - 13.9 Mbps</td>
      <td>35.5 dB</td>
    </tr>
  </tbody>
</table>

<hr />

<h2 id="5-lépések">5. Lépések</h2>
<ol>
  <li><strong>Modulátor konfigurációja</strong>:
    <ul>
      <li>A Johansson 8202 DVB-T modulátoron beállítottuk a kívánt frekvenciát (474 MHz) és a sávszélességet (8 MHz).</li>
      <li>A modulációs típusokat egyesével módosítottuk: QPSK, 16QAM, 64QAM.</li>
    </ul>
  </li>
  <li><strong>Jel vizsgálata METEK HD analizátorral</strong>:
    <ul>
      <li>Az RF kábellel csatlakoztattuk a METEK HD spektrum/jelszint analizátort a modulátor kimenetéhez.</li>
      <li>Minden egyes modulációs típus esetén elvégeztük a jelszint, bitsebesség és MER mérést.</li>
    </ul>
  </li>
</ol>

<hr />

<h2 id="6-következtetések">6. Következtetések</h2>
<ul>
  <li>A mérés során megfigyelhető volt, hogy a moduláció típusának növelésével (QPSK → 64QAM) a bitsebesség jelentősen nőtt, miközben a <strong>MER érték</strong> változásai nem mutattak egyértelmű tendenciát.</li>
  <li>A mérések a DVB-T elméleti követelményeinek megfelelő eredményeket adtak.</li>
</ul>

<hr />

<h2 id="7-megjegyzések">7. Megjegyzések</h2>
<ul>
  <li>A méréseket stabil környezeti feltételek mellett végeztük, zavarforrásoktól mentes helyiségben.</li>
  <li>Az adatok alapján a különböző modulációs technikák közötti különbségek jól megfigyelhetőek voltak.</li>
</ul>

<hr />

<h2 id="8-további-mérési-javaslatok">8. További Mérési Javaslatok</h2>

<details>   

<summary>Kattins a részletekért</summary>   

<h1>Mérési Javaslatok</h1>

    <h2>1. Szélsőséges Jelszint Tesztelése</h2>
    <ul>
        <li><strong>Cél:</strong> Vizsgálni, hogyan viselkedik a rendszer különböző jelszint értékek mellett.</li>
        <li><strong>Lépések:</strong>
            <ol>
                <li>Állítsuk be a jelszintet az RF kimeneten szélsőségesen alacsony és magas értékekre (pl. -60 dBm, -20 dBm).</li>
                <li>Mérjük meg a bitsebességet és a MER-t a kiválasztott modulációs típusok mellett.</li>
            </ol>
        </li>
        <li><strong>Elvárt eredmények:</strong> Magasabb jelszintnél stabilabb adatátvitel, alacsonyabb jelszintnél romló MER és csökkenő bitsebesség.</li>
    </ul>

    <hr />

    <h2>2. Szűkebb és Szélesebb Sávszélesség Hatásai</h2>
    <ul>
        <li><strong>Cél:</strong> Megvizsgálni a sávszélesség változtatásának hatását a jel minőségére és teljesítményére.</li>
        <li><strong>Lépések:</strong>
            <ol>
                <li>Állítsuk be a sávszélességet különböző értékekre (pl. 6 MHz, 7 MHz, 8 MHz).</li>
                <li>Rögzítsük a jelszintet, MER-t és a bitsebességet.</li>
            </ol>
        </li>
        <li><strong>Elvárt eredmények:</strong> Szélesebb sávszélességnél nagyobb bitsebesség, de csökkenhet a MER.</li>
    </ul>

    <hr />

    <h2>3. Zavarforrások Hatása</h2>
    <ul>
        <li><strong>Cél:</strong> Meghatározni, hogy a közeli rádiófrekvenciás zavarok hogyan befolyásolják a jelek minőségét.</li>
        <li><strong>Lépések:</strong>
            <ol>
                <li>Helyezzünk egy zavarforrást (pl. másik RF jeladó) a vizsgált frekvencia közelébe.</li>
                <li>Mérjük meg a jelszintet, MER-t és a bitsebességet különböző távolságokból.</li>
            </ol>
        </li>
        <li><strong>Elvárt eredmények:</strong> Zavarforrás jelenléte csökkentheti a MER-t és növelheti a hibaarányt.</li>
    </ul>

    <hr />

    <h2>4. Moduláció Stabilitásának Vizsgálata Időfüggvényében</h2>
    <ul>
        <li><strong>Cél:</strong> Tesztelni, hogy hosszabb időtartam alatt mennyire stabil a jel különböző modulációs típusok esetén.</li>
        <li><strong>Lépések:</strong>
            <ol>
                <li>Állítsuk be az eszközt egy modulációs típusra (pl. 64QAM).</li>
                <li>Mérjünk jelszintet, MER-t és bitsebességet óránként legalább 12 órán keresztül.</li>
            </ol>
        </li>
        <li><strong>Elvárt eredmények:</strong> Stabil rendszer esetén a paramétereknek változatlannak kell maradniuk.</li>
    </ul>

    <hr />

    <h2>5. Szomszédos Csatornák Vizsgálata</h2>
    <ul>
        <li><strong>Cél:</strong> Megérteni, hogyan befolyásolja a szomszédos csatornák jelenléte a méréseket.</li>
        <li><strong>Lépések:</strong>
            <ol>
                <li>Aktiváljunk egy szomszédos csatornán (pl. 482 MHz vagy 498 MHz) másik DVB-T jelet.</li>
                <li>Mérjük meg a főcsatorna (490 MHz) paramétereit.</li>
            </ol>
        </li>
        <li><strong>Elvárt eredmények:</strong> Növekvő interferencia esetén csökkenhet a MER és romolhat a jel minősége.</li>
    </ul>

    <hr />

    <h2>6. Jelkésleltetés Vizsgálata</h2>
    <ul>
        <li><strong>Cél:</strong> Ellenőrizni a rendszer válaszidejét különböző beállítások mellett.</li>
        <li><strong>Lépések:</strong>
            <ol>
                <li>Állítsunk be eltérő modulációkat és sávszélességeket.</li>
                <li>Mérjük meg a jelkésleltetést (pl. speciális analizátorral vagy műszerekkel).</li>
            </ol>
        </li>
        <li><strong>Elvárt eredmények:</strong> A sávszélesség és moduláció változtatása hatással lehet a késleltetésre.</li>
    </ul>

    <hr />

    <h2>7. Hőmérséklet Hatásának Vizsgálata</h2>
    <ul>
        <li><strong>Cél:</strong> Megérteni, hogyan befolyásolja a környezeti hőmérséklet a rendszer teljesítményét.</li>
        <li><strong>Lépések:</strong>
            <ol>
                <li>Végezze el a méréseket különböző hőmérsékleteken (pl. 0°C, 25°C, 30°C).</li>
                <li>Rögzítse a jelszint, MER és bitsebesség értékeket.</li>
            </ol>
        </li>
        <li><strong>Elvárt eredmények:</strong> Szélsőséges hőmérsékleteken csökkenhet a rendszer stabilitása.</li>
    </ul>  

</details>

<p><br /></p>

<hr />

<h2 id="9-diagramm">9. Diagramm</h2>
<ul>
  <li>Mérési jegyzőkönyv grafikon: 
KÉSŐBB BÁCSI ÁLTAL
    </li>
</ul>


<hr />


<h2 id="11-mért-képek">11. Mért Képek</h2>

<details>
<summary>Kattins a részletekért</summary>

<br />

<img src="https://noel-mercz.github.io/Meresijegyzokonyvek/04_meres/kepek/kep1.bmp" />

<br />

<img src="https://noel-mercz.github.io/Meresijegyzokonyvek/04_meres/kepek/kep2.bmp" />

<br />

<img src="https://noel-mercz.github.io/Meresijegyzokonyvek/04_meres/kepek/kep3.bmp" />

<br />

<img src="https://noel-mercz.github.io/Meresijegyzokonyvek/04_meres/kepek/kep4.bmp" />

<br />

<img src="https://noel-mercz.github.io/Meresijegyzokonyvek/04_meres/kepek/kep5.bmp" />

<br />

<img src="https://noel-mercz.github.io/Meresijegyzokonyvek/04_meres/kepek/kep6.bmp" />

<br />


</details>

<p><strong>Aláírás:</strong> Mercz Noel</p>

<p><strong>Dátum:</strong> 2024. 11. 20.</p>
