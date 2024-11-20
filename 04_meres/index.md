<html lang="en-US">

  <head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width,maximum-scale=2">
    <link rel="stylesheet" type="text/css" media="screen" href="/jegyzokonyv/assets/css/style.css?v=7aed04b2b691e08d82de1a638a6b46bc42986067">
</head>





  <body>


<h1 id="mérési-jegyzőkönyv">MÉRÉSI JEGYZŐKÖNYV</h1>

<p><strong>A mérést végző neve:</strong> Mercz Noel<br />
<strong>A mérés tárgya:</strong> Bitsebesség vs jelminőség mérés<br />
<strong>A mérés száma:</strong> 05. mérés<br />
<strong>A mérés dátuma:</strong> 2024.11.20.<br />
<strong>A mérést vezette:</strong> Sándor Péter</p>

<p><strong>Évfolyam:</strong> 13. E<br />
<strong>Csoport:</strong> GYAK 2<br />
<strong>Helyszín:</strong> V3 Labor</p>

<hr />

<h1 id="mérési-jegyzőkönyv-1">Mérési Jegyzőkönyv</h1>

<h3 id="1-mérési-feladat">1. Mérési feladat</h3>
<p>Ismerkedés a <strong>Johansson 8202 DVB-T modulátor</strong> képességeivel, valamint a bitsebesség és jelminőség vizsgálata. A célunk a műszer alapos megismerése volt.</p>

<hr />

<h3 id="2-alkalmazott-mérőeszközök-és-készülékek">2. Alkalmazott mérőeszközök és készülékek</h3>

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

<h3 id="3-előkészületek">3. Előkészületek</h3>
<p>A mérés során a két Johansson 8202 DVB-T modulátort összekötöttük, majd az egyik modulátor <strong>RF-out</strong> pontját csatlakoztattuk a spektrumanalizátorhoz. Az eszközök megfelelő beállítását követően megkezdtük a mérést.</p>

<hr />

<h3 id="4-mért-adatok---tv2-erős-és-tv1-pongo">4. Mért Adatok - TV2 és TV1 </h3>
<p>A következő paramétereket olvastuk le a spektrumanalizátorról és a modulátor kijelzőjéről:</p>

<table>
  <thead>
    <tr>
      <th>Paraméter</th>
      <th>TV2 10Mb/s</th>
      <th>TV2 21.5Mb/s</th>
      <th>TV1 15Mb/s</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>MER</td>
      <td>31.2 dB</td>
      <td>30.7 dB</td>
      <td>36.4 dB</td>
    </tr>
    <tr>
      <td>Packet Errors</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Noise Margin</td>
      <td>18.4</td>
      <td>20.6</td>
      <td>19.7</td>
    </tr>
    <tr>
      <td>Power</td>
      <td>-30.8 dBm</td>
      <td>-33.6 dBm</td>
      <td>-34.2 dBm</td>
    </tr>
    <tr>
      <td>Bitsebesség</td>
      <td>~11 Mb/s</td>
      <td>~18 Mb/s</td>
      <td>~12 Mb/s</td>
    </tr>
  </tbody>
</table>

<hr />

<h3 id="5-mérési-eljárás">5. Mérési eljárás</h3>
<ol>
  <li>A mérőeszközök megfelelően lettek összekapcsolva és kalibrálva a mérés előtt.</li>
  <li>A Johansson 8202 DVB-T modulátor különböző bitsebességeken tesztelve lett a jelminőség mérése céljából.</li>
  <li>A jelanalizátorral minden beállításhoz tartozó jelminőség mérését elvégeztük.</li>
</ol>

<hr />

<h3 id="6-következtetés">6. Következtetés</h3>
<ul>
  <li>
    <p>A mérések során megismertük a <strong>Johansson 8202 DVB-T modulátor</strong> alapvető képességeit, és pontos adatokat kaptunk a bitsebességről és jelminőségről. A mérési eredmények alapján a modulátor megfelelő teljesítményt nyújtott, és a jelszint, bitsebesség, valamint a MER értékek a várakozásoknak megfelelően alakultak.</p>
  </li>
  <li>
    <p>Azonnal láthatóvá válik, hogy a TV1 magasabb bitsebességgel és erősebb teljesítménnyel dolgozik, míg a TV2 jobb MER értékkel bír.</p>
  </li>
  <li>
    <p>A mérések alapján megfigyelhető, hogy a bitsebesség növekedésével a jelminőség fokozatosan csökkent. A legmagasabb jelminőséget alacsony bitsebességnél értük el, ahol a zaj mértéke még elfogadható szinten maradt. Az eredmények alapján javasolható, hogy nagyobb stabilitás érdekében a rendszer optimális működése alacsonyabb bitsebességeken biztosított.</p>
  </li>
</ul>

<hr />

<h4 id="7-további-mérések-javaslata">7. További mérések javaslata:</h4>
<ol>
  <li><strong>Jelminőség mérése különböző antennák használatával</strong>: Érdemes tesztelni, hogy különböző antennák milyen hatással vannak a jelminőségre azonos bitsebességen.</li>
  <li><strong>Zajforrások közelségének hatása a jelminőségre</strong>: Vizsgáljuk meg, hogyan befolyásolják a közelben található elektromos zajforrások a mérési eredményeket.</li>
  <li><strong>Hőmérséklet és környezeti feltételek hatása</strong>: Érdemes a méréseket különböző környezeti feltételek mellett (pl. hőmérséklet-ingadozás) is elvégezni, hogy megismerjük, hogyan változik a jelminőség extrém körülmények között.</li>
  <li><strong>Többcsatornás mérések</strong>: Különböző frekvenciákon is végezzünk méréseket, hogy lássuk, a bitsebesség és a jelminőség miként viszonyul az eltérő csatornákhoz.</li>
</ol>

<hr />

<h3 id="8-felhasznált-források">8. Felhasznált Források</h3>
<ol>
  <li><strong>Johansson 8202 DVB-T modulátor felhasználói kézikönyv</strong> - A modulátor alapvető képességeinek és beállításainak megismeréséhez használtuk.</li>
  <li><strong>Digitális jeltovábbítás és zajszint tanulmányok</strong> - A digitális jelek bitsebesség és jelminőség közötti összefüggéseiről szóló tudományos anyagok segítettek a mért eredmények elemzésében.</li>
  <li><strong>Spectrum Analyzer működési útmutató</strong> - A jelminőség és a zajszint mérésére használt analizátor beállításához és pontos használatához alapvető forrás.</li>
</ol>

<hr />

<h3 id="9-magyarázatok-és-lábtanulmányok">9. Magyarázatok és Lábtanulmányok</h3>
<ol>
  <li><strong>Bitsebesség és Jelminőség</strong>: A bitsebesség (Mbps) a másodpercenként átvitt adatbitek számát jelenti. A magasabb bitsebesség gyakran a jelminőség csökkenéséhez vezethet, mivel nagyobb adatforgalmat kell kezelnie az átviteli eszközöknek. A jelminőség (SNR, Signal-to-Noise Ratio, dB-ben mérve) azt mutatja meg, hogy a jelszint mekkora a zajszinthez képest. A magasabb SNR jobb jelminőséget jelent.</li>
  <li><strong>Moduláció és DVB-T technológia</strong>: A DVB-T modulátor, mint a Johansson 8202, alapvetően a digitális földfelszíni sugárzás szabványát követi. Ez a modulátor képes különböző bitsebességek és jelszintek beállítására, ami lehetővé teszi a különféle átviteli környezetekhez való alkalmazkodást.</li>
  <li><strong>Jelminőség mérésének jelentősége</strong>: A zajszint mérésével meghatározhatjuk, milyen hatékonyan tudja az adott rendszer átvinni az információt interferencia és más zavaró tényezők mellett. A vizsgálat célja, hogy megtaláljuk a jelminőség és bitsebesség optimális kombinációját, amely a legjobb jeltovábbítást biztosítja adott körülmények között.</li>
</ol>

<hr />

<h3 id="10-záró-összegzés">10. Záró Összegzés</h3>
<p>A jegyzőkönyvben végrehajtott mérés a Johansson 8202 DVB-T modulátor különböző bitsebességek melletti jelminőség-vizsgálatára irányult. Az eredmények alapján világossá vált, hogy a magasabb bitsebesség kedvezőtlenül hat a jelminőségre, amit a zajszint (SNR) csökkenése mutatott. A tesztelt bitsebességek között a 10 Mbps körüli érték biztosította a legjobb egyensúlyt a jelminőség és a sebesség között, ami elfogadható teljesítményt eredményezett.</p>

<p>További mérésekkel, például különböző antennák tesztelésével, zajforrások hatásának vizsgálatával, illetve eltérő környezeti körülmények figyelembevételével még jobban feltérképezhetjük a bitsebesség és jelminőség közötti kapcsolatot. A jegyzőkönyv összességében értékes betekintést nyújt a DVB-T technológia alapvető működésébe és az optimális beállítások megtalálásához vezető út első lépéseibe.</p>

<hr />

<h2 id="11-mért-képek">11. Mért Képek:</h2>
<details>
<summary>Kattins a részletekért</summary>

<br />

<img src="https://noel-mercz.github.io/Meresijegyzokonyvek/04_meres/kepek/its_snapshot_0001.bmp" />

<br />

<img src="https://noel-mercz.github.io/Meresijegyzokonyvek/04_meres/kepek/its_snapshot_0002.bmp" />

<br />

<img src="https://noel-mercz.github.io/Meresijegyzokonyvek/04_meres/kepek/its_snapshot_0004.bmp" />

<br />

<img src="https://noel-mercz.github.io/Meresijegyzokonyvek/04_meres/kepek/its_snapshot_0003.bmp" />

<br />

<img src="https://noel-mercz.github.io/Meresijegyzokonyvek/04_meres/kepek/its_snapshot_0005.bmp" />

<br />

<img src="https://noel-mercz.github.io/Meresijegyzokonyvek/04_meres/kepek/its_snapshot_0006.bmp" />

<br />

<img src="https://noel-mercz.github.io/Meresijegyzokonyvek/04_meres/kepek/its_snapshot_0007.bmp" />

</details>

<p><strong>Aláírás:</strong> Mercz Noel</p>

<p><strong>Dátum:</strong> 2024.11.20.</p>

  </body>
</html>
