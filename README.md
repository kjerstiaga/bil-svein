# 🚗 BMW Prutemester — Strategisk Bilkjøp med AI

> Ein praktisk demonstrasjon av **Principles of Top Performers**-rammeverket brukt på eit reelt problem: å kjøpe bruktbil på FINN.no.

---

## Kva er dette?

Dette prosjektet brukar 5 kjerneprinsipper for topp-performere til å strukturere ein forhandlingsstrategi for bilkjøp. Det er både ein bruksanvisning og eit levande eksempel på korleis analytisk tenking slår magefølelse — også når du kjøper bil.

Rammeverket er universelt. Bilen er berre konteksten.

---

## Dei 5 prinsippa i bruk

| Prinsipp | Kva det betyr i praksis | Bileksempel |
|---|---|---|
| **Ghost Notes** | Les det usagte — kva nemner ikkje seljar? | «Kosmetiske merker på felgar» er alltid verdt å undersøke |
| **Loss Function** | Definer kva «betre» betyr, mål feilpunkt | Sett ein walk-away-pris før du ringer |
| **Adaptive Tension** | Nysgjerrig, ikkje aggressiv — bruk CORE | Still tekniske spørsmål som signaliserer ekspertise |
| **Time Horizon** | Seljar har kortare horisont enn deg | Ein bil som har stått 3 mnd kostar seljar pengar kvar dag |
| **Identity as Anchor** | Opptre som ein kunnskapsrik kjøpar — det skiftar maktbalansen | Nemn DPF, EGR og injektorar. Seljar veit at du veit. |

---

## Prosjektstruktur

```
/
├── README.md                    # Dette dokumentet
├── prutemaster/
│   ├── strategi.md              # Fullstendig prute-protokoll
│   ├── bil1_analyse.md          # BMW 530d 2019, Bergen — Car4Sale
│   ├── bil2_analyse.md          # BMW 530xd 2015, Sævareid — privat
│   └── markedsanalyse.md        # Samanlikning + transportkalkyle Trondheim
├── rammeverk/
│   ├── principles.md            # Dei 5 prinsippa, fullt utdjupa
│   └── core_model.md            # Adaptive Tension — CORE-rammeverket
└── verktøy/
    ├── prutemester.html          # Interaktiv guide (standalone)
    └── markedsanalyse.html       # Samanlikningsverktøy med transportkalkyle
```

---

## Snøgg start

### Bruk prutemaster-guiden

Opne `verktøy/prutemester.html` direkte i nettlesaren — ingen installasjon naudsynt.

Guiden inneheld:
- Systemet og dei 7 reglane
- Analyse av kvar enkelt bil
- Ferdige manus du kan bruke ord for ord

### Bruk prinsippa på din eigen situasjon

```
1. Ghost Notes    →  Les annonsen tre gongar. Kva manglar?
2. Loss Function  →  Skriv ned walk-away-pris FØR du kontaktar seljar
3. Adaptive       →  Ring — ikkje meld. Lytt til tonen.
4. Time Horizon   →  Kor lenge har bilen stått? Sjekk «sist oppdatert»
5. Identity       →  Still eitt teknisk spørsmål seljar må tenkje på
```

---

## Casestudie: BMW 530d 2019 — Bergen vs. Trondheim

### Bil 1 — Car4Sale, Bergen

| Parameter | Verdi |
|---|---|
| Listepris | 399 900 kr |
| Km-stand | 179 000 km |
| Årsmodell | 2019 |
| Eiarar | 2 |
| EU | Teke juni 2025 |
| Transport til Trondheim | ~4 000–8 000 kr |
| **Reell totalkostnad** | **~405 000 kr** |
| **Tilrådd opningsbud** | **358 000 kr** |
| **Realistisk sluttmål** | **368 000 kr** |

**Sterkaste forhandlingsargument:** Du bur 680 km unna. Transportkostnad er reell merkostnad. Tilsvarande 2021-modellar med garanti finnast i Trondheim for 430–480k.

### Bil 2 — Privat, Sævareid

| Parameter | Verdi |
|---|---|
| Listepris | 364 434 kr |
| Km-stand | 133 000 km |
| Årsmodell | 2015 |
| Steg 2 tune | Ja — dokumentert |
| Stormskade-lakk | Sept. 2023 |
| EU | Sept. 2027 |
| **Tilrådd opningsbud** | **320 000 kr** |
| **Realistisk sluttmål** | **335 000 kr** |

**Sterkaste forhandlingsargument:** Tune + stormskadelakk avgrensar kjøpargruppa. Seljar veit dette.

---

## Principles of Top Performers — rammeverket

Dette prosjektet er ein del av eit større arbeid med å kartleggje og gjere brukbart korleis topp-performerar tenkjer og opererer.

Meir om rammeverket:
- [Principles of Top Performers — oversikt](rammeverk/principles.md)
- [CORE-modellen for vanskelege samtalar](rammeverk/core_model.md)

---

## Bidrag

Pull requests og issues er velkomne — særleg:
- Fleire casestudiar der prinsippa er brukte
- Forbetringar av prute-protokollen
- Nye domene der rammeverket kan testast (jobbforhandlingar, innkjøp, leigeavtalar)

---

## Lisens

MIT — bruk det fritt, kreditter gjerne.

---

*Bygd med nysgjerrighet, markedsdata og ein sunn respekt for at seljarar òg har lest bøker om forhandlingsteknikk.*
