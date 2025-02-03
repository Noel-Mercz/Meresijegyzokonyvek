# MÉRÉSI JEGYZŐKÖNYV

**Vizsgálat tárgya:** DVB-T jel fejállomásba küldése és IPTV rendszeren való kiadása

**Vizsgálat helye:** Villamos 3 labor

**Vizsgálat dátuma:** 2025.02.03.

**Vizsgálatot végezte:** Mercz Noel

---

## 1. Szükséges eszközök
- **Antenna:** Beltéri - Iskra P2845 Logper
- **Fejállomás:** LEMCO SCL-824CT
- **Set-top box:** MAG IPTV
- **Hálózati eszközök:** Switch - HP 2312 procurve
- **Mérőműszer:** METEK HDD 240003 digitális TV jelmérő
- **Kábelezés:** Koaxiális és UTP kábelek
- **Egyéb szerelési eszközök:** Csavarhúzó, villáskulcs, kábelvágó, iránytű, dőlésszögmérő

---

## 2. Antenna beállítása és jelmérés
- **Adótorony:** MiskolcTV, Avasi adótorony
- **Multiplex adatok:**
  - **Frekvencia:** [MHz]
  - **Teljesítény:** [dB]
  - **Polarizáció:** Horizontális
  - **Adás típusa:** DVB-T
- **Antenna pozíció:**
  - **Dőlésszög:** [°]
  - **Irány:** Dél-Nyugat 233°
- **Mért jelszintek:**
  - **Jelerősség:** 52 dBu
  - **Jel-zaj viszony (SNR):** [dB]
  - **Bit Error Rate (BER):** [Érték]
  - **Modulation Error Ratio (MER):** [dB]
  - **Csillapítás:** [dB]
  - **Lock állapot:** [ ] Igen [ ] Nem
- **Időjárási körülmények:**
  - **Hőmérséklet:** 0 °C
  - **Szélsebesség:** 5 km/h
  - **Egyéb megjegyzések:** 90% páratartalom

---

## 3. Fejállomás beállítása és IPTV konfiguráció
- **Jel osztása a fejállomás bemeneteire:**
  - **Multiplexek hozzárendelése:** Igen

            - Multiplex D - 1 port

            - Multiplex A - 2 port

            - Multiplex E - 7 port

            - Miskolc városi tv - 8 port
  - **DVB-T jel IP streamre konvertálása:** Igen
- **Multicast IP tartomány:** [239.x.x.x]
- **IPTV Set-top box beállításai:**
  - **Hálózati kapcsolat:** [Beállítva/Nincs beállítva]
  - **Multicast IP címek hozzáadva:** [Igen/Nem]
  - **Csatornakeresés eredménye:** [Sikeres/Sikertelen]

---

## 4. IPTV stream vizsgálata
- **Multicast IP címek ellenőrzése:** [Igen/Nem]
- **Stream stabilitása:** [Stabil/Ingadozó]
- **Hálózati késleltetés:** [ms]
- **Csomagvesztés:** [Érték]
- **Mért adatok rögzítése:**
  - **Spektrum analizátor képe csatolva:** [Igen/Nem]
  - **Stream adatok mentve:** [Igen/Nem]
  - **Mért IPTV paraméterek:**
    - **Bitráta:** [Mbps]
    - **Késleltetés:** [ms]
    - **Csomagvesztés:** [%]

---

## 5. Összegzés és jegyzőkönyv lezárása
- **Mérési eredmények alapján a rendszer megfelelően működik?** Igen
- **Jegyzőkönyv lezárásának dátuma:** 2025.02.03.
- **Vizsgálatot végző aláírása:** Mercz Noel

---

## Mellékletek
- Spektrum analizátor képei
- Mérési grafikonok
- IPTV stream ellenőrzési logok

**Megjegyzés:** A mérési jegyzőkönyv minden releváns paramétert tartalmaz a DVB-T vétel, fejállomás konfiguráció és IPTV rendszer működésének ellenőrzéséhez.