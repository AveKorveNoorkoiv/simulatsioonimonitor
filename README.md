# Simulatsioonimonitor

Autor ja looja: **Ave Kõrve-Noorkõiv** · © 2026 Ave Kõrve-Noorkõiv · Litsents [CC BY-NC 4.0](LICENSE) (mitteäriline kasutus)

Patsiendimonitori simulaator tervishoiuõppe simulatsioonideks. Instruktor muudab elutähtsaid näitajaid reaalajas, õppijad näevad realistlikku monitori projektoril, teleril või tahvlil.

> **Ainult õppeotstarbeks.** Õppevahend simulatsiooniks. Ei ole meditsiiniseade ega mõeldud kliiniliseks kasutamiseks.

## Võimalused

- EKG (II juhe) ja rütmid: siinus, kodade virvendus, VT, VF, asüstoolia, PEA
- SpO₂ pletüsmogramm, EtCO₂ kapnogramm (kPa või mmHg), hingamissagedus, NIBP, temperatuur
- Alarmid ja helid, valmisstsenaariumid, CPR-metronoom
- Defibrillaator: AED, manuaalne laadimine ja šokk, sünkroonne kardioversioon (SYNC), väline stimulatsioon
- Sündmuste logi järelaruteluks
- Eesti ja inglise keel

## Kasutamine

Avalehel on kolm valikut:

| Valik | Kuidas |
|---|---|
| **Alusta uut sessiooni** | Juhtpult on selles seadmes (arvuti või telefon). Ekraanile tuleb QR-kood ja 6-kohaline kood |
| **Monitori ooteekraan** | Tahvel, teler või arvuti on monitor: sisesta kood või skanni QR-kood kaameraga |
| **Üks arvuti + projektor** | Vajuta **Juhtpult → Ava instruktori aken**, lohista monitori aken projektorile |
| Ilma internetita | Laadi `index.html` alla ja ava see arvutis. Kahe akna režiim töötab ka ilma internetita |

Wifi-ühendus kasutab seadmetevahelist otseühendust (WebRTC). Mõlemad seadmed vajavad internetti. Kui asutuse võrk otseühendust ei luba, kasuta telefoni levi või külalisvõrku.

## Kolmanda osapoole teegid

Laaditakse ainult wifi-ühenduse loomisel, cdn.jsdelivr.net kaudu:

- [PeerJS](https://github.com/peers/peerjs) 1.5.4 (MIT), koos avaliku PeerJS-serveriga ühenduse loomiseks
- [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) 1.4.4 (MIT)

## Litsents

Simulatsioonimonitor © 2026 Ave Kõrve-Noorkõiv. Litsents: [Creative Commons Autorile viitamine-Mitteäriline 4.0 rahvusvaheline (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.et).

| Lubatud | Tingimused |
|---|---|
| Kasutada, kopeerida ja jagada | Autor tuleb nimetada: „Simulatsioonimonitor, autor Ave Kõrve-Noorkõiv“ koos lingiga litsentsile |
| Muuta ja edasi arendada | Muudatused tuleb ära märkida |
| Kasutada õppetöös, sh õppeasutustes ja haiglate koolitustel | Kasutus ei tohi olla äriline (nt müük või tasuline teenus) |

Ärilise kasutuse kohta küsi luba autorilt. Logod ei kuulu litsentsi alla: need kuuluvad vastavatele asutustele ja neid kasutatakse nende loal.
