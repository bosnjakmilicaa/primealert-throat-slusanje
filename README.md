# PrimeAlert — test slušanja (simulacija throat mikrofona)

Test slušanja za projekat PrimeAlert (Katedra za telekomunikacije i obradu signala, FTN Novi Sad).

Slušalac za 20 rečenica iz baze Vibravox (20 govornika, 10 žena i 10 muškaraca) čuje snimak pravog throat mikrofona (referenca) i pet simulacija iste rečenice, i bira onu koja zvuči najsličnije referenci. Dva primera se ponavljaju radi provere doslednosti.

- `index.html` — test (statička stranica, GitHub Pages)
- `manifest.json` — raspored rečenica i snimaka
- `audio/` — snimci (16 kHz, mono, WAV), ujednačene glasnoće; nazivi su nasumični kodovi

Ključ (koji kod odgovara kojoj verziji simulatora) nije javan i čuva se odvojeno. Odgovori se šalju u Google tabelu preko Google Apps Script-a.
