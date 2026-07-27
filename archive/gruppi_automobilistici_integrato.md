# Assetto azionario e proprietario dei principali gruppi automobilistici europei — versione integrata (luglio 2026)

> **Nota sulla provenienza di questo documento.** Questo file integra due ricerche precedenti sullo stesso tema:
> - **Ricerca A** (senza accesso a strumenti web — dati stimati dalla sola conoscenza del modello, ampiamente marcati "DA VERIFICARE");
> - **Ricerca B** (con web_search/web_fetch operativi — dati verificati su fonti primarie con URL e data di consultazione).
>
> La Ricerca B **risolve quasi tutte le incertezze** della Ricerca A con numeri più precisi e datati (es. Exor→Stellantis 15,48%/23,84% invece della stima ~14,2%; KIA→Mercedes 4,97% invece di ~6,8%; Nissan→Mitsubishi Motors 24,05% invece di ~34%). Questo documento usa **la Ricerca B come base autorevole** per ogni dato numerico, e recupera dalla Ricerca A solo i punti che B non copriva, segnalandoli come *non riverificati*. Dove le due ricerche divergono senza che B risolva esplicitamente la discrepanza, è indicato in **Caveats**.
>
> **Aggiornamento (Ricerca C, luglio 2026).** Una terza ricerca ha estesso la copertura a sei gruppi europei non trattati dalle prime due: **Ferrari, AB Volvo/Volvo Group, Iveco Group, Bugatti Rimac, McLaren e Jaguar Land Rover** (§8-§13). La Ricerca C si è appoggiata quasi interamente su ricerche web tramite browser (nessuno strumento di web search dedicato disponibile in questa sessione) e su fonti secondarie di stampa finanziaria/specializzata (Reuters, BBC, Carscoops, Yahoo Finance, aggregatori azionari) più alcuni comunicati societari ufficiali (Porsche Newsroom, Iveco Group, Stellantis); pochissimi dati provengono da un filing primario diretto. Ogni dato di questa sezione è quindi tendenzialmente marcato come fonte secondaria (**st: S**) nel grafo, anche quando corroborato da più testate indipendenti.

> **Aggiornamento (Ricerca D, luglio 2026).** Una quarta ricerca ha aggiunto uno strato di **partnership industriali e partecipazioni incrociate** tra entità già presenti nel grafo, finora non mappate (§14): l'investimento **Hyundai/Kia in Rimac Group**, la quota **Volkswagen in XPeng**, le alleanze industriali senza scambio azionario **Volkswagen–Ford** e **BMW–Toyota**, la fornitura **Stellantis–Toyota** e il controllo di fatto di **Exor su CNH Industrial** (la “gamba” agricola e da costruzione del gruppo Agnelli, da cui è stata scorporata Iveco). Anche questi dati sono prevalentemente di fonte secondaria o di conoscenza generale di settore (**st: S**) e vanno trattati come tali. La stessa ricerca ha inoltre inserito i principali **costruttori europei indipendenti e di nicchia** (Pagani, Koenigsegg, Ineos Automotive, Automobili Pininfarina, Morgan) con i rispettivi proprietari e la relazione fallita Koenigsegg-NEVS, e ha completato l'**azionariato di Aston Martin** con Saudi PIF e Mercedes-Benz (§15).

---

## TL;DR

- **Capitale ≠ voto in quattro nodi chiave**, confermato su fonti primarie: **Porsche SE** detiene il **53,3% dei voti** ma solo il **31,9% del capitale** di Volkswagen AG; la **Bassa Sassonia** ha il **20,0% dei voti** VW (soglia di veto statutaria via *Volkswagen-Gesetz*, invece del consueto 25%) su un capitale nettamente inferiore; **Exor** ha il **15,48% del capitale** Stellantis ma il **23,84% dei voti** (loyalty shares); **Renault** possiede il **35,71% del capitale** Nissan ma i diritti di voto restano contrattualmente cappati al **15%**.
- **L'Alleanza Renault-Nissan-Mitsubishi è stabile dal 2024**: la quota Renault in Nissan (35,71% = 17,05% diretto + 18,66% in trust francese, 693,1 mln azioni) è **invariata da fine 2024** e confermata nei comunicati Q1/Q2 2025; nessuna ulteriore cessione dal trust risulta eseguita a luglio 2026. La fusione Honda-Nissan è **naufragata il 13 febbraio 2025**. Nissan ha ridotto la quota in Mitsubishi Motors dal 34,07% al 24,05% con un buyback nel novembre 2024.
- **Stellantis (Form 20-F 25 febbraio 2026)**: Exor 15,48%/23,84% voto, EPF/famiglia Peugeot 7,72%/11,89%, Bpifrance 6,64%/10,22%; Dongfeng ridotto a poco più dell'1%. Nessun marchio chiuso nel piano FaSTLAne 2030 (maggio 2026); Maserati resta marchio di lusso puro, Lancia e DS diventano marchi "specialty".
- **Geely resta il principale hub trasversale** del grafo (Volvo Cars 78,7%, smart 50% con Mercedes, Mercedes 9,69% capitale, Aston Martin ridotta a ~14% dal picco ~17%), ma con quote in movimento continuo — verificare ad ogni aggiornamento.
- **Nuovi archi cross-gruppo emersi solo nella Ricerca B**, assenti in A: VW→Rivian (15,9%, JV 50/50 "Rivian and Volkswagen Group Technologies"); fallimento Northvolt (VW ~21%) con asset passati a Lyten (partecipata anche da Stellantis).
- **Copertura estesa a sei nuovi gruppi europei (Ricerca C, luglio 2026)**: Ferrari, AB Volvo/Volvo Group, Iveco Group, Bugatti Rimac, McLaren e Jaguar Land Rover sono stati aggiunti al grafo. Il fatto più rilevante è che **Tata Motors** (India) è in procinto di diventare proprietario sia di **Jaguar Land Rover** (dal 2008) sia di **Iveco Group** (acquisizione da Exor annunciata il 30 luglio 2025, chiusura attesa nel terzo trimestre 2026 ma **non confermata come completata a fine luglio 2026**) — un parallelo interessante alla doppia presenza cinese già presente in Mercedes-Benz/Volvo Cars/Stellantis.
- **Porsche AG si è ritirata dagli investimenti extra-core**: il 24 aprile 2026 ha venduto sia la quota del 45% in Bugatti Rimac sia il 20,6% in Rimac Group a un consorzio guidato da HOF Capital, chiudendo un capitolo di diversificazione apertosi nel 2021.
- **Nuovo strato di partnership industriali (Ricerca D, luglio 2026)**: collegati fra loro nodi già presenti ma finora isolati — **Hyundai/Kia→Rimac Group (~12%)**, **VW→XPeng (~5%)**, **Exor→CNH Industrial (~26,9% cap./~42,5% voti**, stessa struttura di loyalty shares di Stellantis e Ferrari) e tre alleanze industriali **senza** scambio azionario (**VW–Ford**, **BMW–Toyota**, **Stellantis–Toyota**). Confermano che i grandi gruppi europei sono legati anche a costruttori extra-europei (Corea, Cina, USA, Giappone) da accordi tecnologici, non solo da partecipazioni.
- **Mappa europea completata con i costruttori indipendenti (Ricerca D, §15)**: aggiunti **Pagani** (fondatore), **Koenigsegg** (fondatore + relazione **fallita** con NEVS/Evergrande), **Ineos Automotive** (INEOS/Ratcliffe), **Automobili Pininfarina** (Mahindra) e **Morgan** (Investindustrial). Completato inoltre l'azionariato di **Aston Martin** con **Saudi PIF** (~16-18%) e **Mercedes-Benz** (<8%, partnership tecnologica in diluizione).

---

## Key Findings

1. **Non collassare mai capitale e voto** in Porsche SE/VW, Bassa Sassonia/VW, Qatar/VW, Exor-EPF-Bpifrance/Stellantis, Renault/Nissan: in tutti questi archi il dato di voto è materialmente diverso dal dato di capitale e **va rappresentato con due etichette distinte sullo stesso arco**, non collassato in un unico numero.
2. **L'assetto Renault-Nissan è più stabile di quanto la Ricerca A stimasse**: non è un processo di dismissione continua, ma una situazione **ferma da fine 2024** (35,71%/17,05%/18,66%), con solo un cambio di trattamento contabile (fair value through equity, giugno 2025, impatto non-cash ~€9,3 mld) e un'intenzione dichiarata ma non eseguita da parte di Nissan di scendere dal 15% al 10% in Renault.
3. **Stellantis è pienamente consolidata e il piano FaSTLAne 2030 chiude l'incertezza sui marchi** che la Ricerca A segnalava come dinamica: nessuna chiusura/vendita di marchio, Maserati confermata di lusso puro (con roadmap dettagliata attesa dicembre 2026), Lancia e DS declassati a "specialty" sotto Fiat e Citroën.
4. **Traton = veicoli industriali** (MAN, Scania, International Motors ex-Navistar dal 1° ottobre 2024, Volkswagen Truck & Bus Brasile); i **furgoni VW (Transporter/Crafter/Caddy) restano nel marchio Volkswagen core**, non in Traton — punto confermato da entrambe le ricerche.
5. **Doppia presenza cinese in Mercedes-Benz** (BAIC 9,98% voti, Geely/Tenaciou3 9,69% capitale) resta un nodo di interesse; la quota Kuwait Investment Authority va aggiornata a **~4,97%** (Ricerca B), non ~6,8% come indicato nella Ricerca A (dato obsoleto, ridotto già a marzo 2023).
6. **Punto non risolto da nessuna delle due ricerche**: la quota di Mitsubishi Corporation (trading house) in Mitsubishi Motors resta senza percentuale verificata su fonte primaria in entrambe le ricerche.
7. **Exor si confirma hub multi-settoriale anche fuori da Stellantis**: detiene il 21,33%/32,32% (capitale/voto) di **Ferrari** e il 27,1%/43,1% di **Iveco Group** — quest'ultima partecipazione oggetto della cessione a Tata Motors annunciata nel luglio 2025. La scomposizione capitale/voto puntuale di Ferrari proviene però da un'analisi di settore non primaria, non da un filing Exor/Ferrari.
8. **AB Volvo (camion/bus/macchine movimento terra) resta un'entità del tutto distinta da Volvo Cars** (auto, controllata da Geely): le due società si sono separate nel 1999. Il grafo va aggiornato con cautela per non confondere i due nodi.
9. **Exor è la holding più pervasiva del grafo dopo Geely**: oltre a Stellantis, Ferrari e Iveco Group, controlla di fatto anche **CNH Industrial** (~26,9% capitale / ~42,5% voti), completando la mappa dei veicoli industriali e agricoli del gruppo Agnelli. Il meccanismo di controllo è sempre lo stesso — loyalty/special voting shares che concentrano il voto ben oltre la quota di capitale — replicato su quattro entità distinte.

---

## Details — per entità

### 1. Alleanza Renault–Nissan–Mitsubishi

**Situazione storica (pre-novembre 2023):** asimmetrica — Renault deteneva 43,4% di Nissan con pieno voto; Nissan deteneva 15% di Renault privo di voto (regola francese sulle partecipazioni incrociate, Code de commerce).

**Ristrutturazione dell'8 novembre 2023 e stato attuale (confermato, invariato da fine 2024 — fonte: comunicati "Nissan's contribution" Q1 2025 del 13/5/2025 e Q2 2025 del 30/7/2025):**
- **Renault → Nissan: 35,71% del capitale totale**, composto da:
  - **17,05% detenuto direttamente** con pieno diritto di voto;
  - **18,66% conferito a un trust francese indipendente** (693,1 milioni di azioni), voto neutralizzato per la maggior parte delle decisioni ma beneficio economico mantenuto in capo a Renault, in vista di una cessione discrezionale nel tempo.
  - Percorso di dismissione dal trust (dal 28,4% iniziale al 18,66% attuale): tre vendite — 211 mln azioni (~5%, dicembre 2023), 99,1 mln (~2,5%, marzo 2024), 195,5 mln (~5,0%, €494 mln, settembre 2024). **Nessuna vendita ulteriore risulta eseguita tra metà 2025 e luglio 2026.**
  - 30 giugno 2025: cambio del trattamento contabile della quota nel trust (a fair value through equity), con impatto di perdita non-cash di circa €9,3 mld e perdita di gruppo Renault FY2025 di circa €10,9 mld.
- **Nissan → Renault: 15% del capitale, voto cappato contrattualmente al 15%.** L'amendment del **31 marzo 2025** ha abbassato la soglia minima vincolante di cross-shareholding dal 15% al 10% (lasciando esplicitamente inalterate le azioni Renault nel trust). Il CEO Nissan Ivan Espinosa ha dichiarato (giugno 2025) l'intenzione di scendere al 10%, **ma la vendita non risulta eseguita a luglio 2026**.
- ***[Da Ricerca A, non confermato da B]*** Gli accordi originari del novembre 2023 prevedevano anche un **impegno Renault-Nissan a investire in Ampere** (controllata EV/software di Renault); Renault ha ritirato l'IPO di Ampere nel 2024, rendendo probabilmente superato questo impegno. **Nessuna delle due ricerche ha verificato lo stato attuale di questa clausola: da riverificare sull'URD Renault più recente se rilevante per il grafo.**

**Nissan → Mitsubishi Motors:** ridotta dal **34,07% (506.620.577 azioni) al 24,05%** tramite buyback ToSTNeT-3 dell'8 novembre 2024 (¥460,6/azione, ~¥68,6 mld incassati), con **perdita del controllo automatico sulle nomine del board**. Mitsubishi Corporation (trading house, entità distinta dal costruttore) mantiene una partecipazione residua **non quantificata con precisione su fonte primaria in nessuna delle due ricerche**.

**Honda-Nissan:** MoU di fusione del 23 dicembre 2024, **naufragato il 13 febbraio 2025** per il rifiuto di Nissan di diventare sussidiaria di Honda. Prosegue la collaborazione tecnologica su batterie/software/EV (con coinvolgimento Mitsubishi); Foxconn è rimasta interessata a Nissan.

**Fonti primarie:** Renault Group, *Document d'enregistrement universel* 2024/2025 (AMF); comunicati Alliance/Renault "Nissan's contribution" (2023-2025); Nissan Motor, *Yūkashōken hōkokusho* (EDINET); Mitsubishi Motors, comunicato buyback 7/11/2024.

**Classificazione arco:** cross-holding **asimmetrico nel capitale (35,71% vs 15%) ma paritario nel voto (15%/15%)**; relazione storica di controllo Renault→Nissan (43,4%) **cessata dal novembre 2023**.

---

### 2. Porsche SE / Volkswagen AG / Porsche AG (dati al 31 dicembre 2025)

Capitale sociale VW: €1.283.315.873,28; 295.089.818 azioni ordinarie votanti.

- **Porsche SE → VW: 53,3% dei voti / 31,9% del capitale totale.** La divergenza deriva dalla struttura duale del capitale VW (ordinarie votanti + privilegiate quotate senza voto); Porsche SE concentra la sua presa sulle ordinarie.
- **Bassa Sassonia → VW: 20,0% dei voti / ≈11,8% del capitale totale** (stima Ricerca A, non ricontrollata puntualmente da B ma coerente). Potere di **veto statutario** via *Volkswagen-Gesetz*, che fissa la soglia di blocco al 20% dei voti invece del consueto 25% del diritto societario tedesco.
- **Qatar Holding LLC → VW: 17,0% dei voti** (terzo azionista).
- **Flottante: 9,7%** delle ordinarie.
- **VW → Porsche AG: 75% meno un'azione** delle ordinarie (indirettamente via Porsche Holding Stuttgart GmbH).
- **Porsche SE → Porsche AG: 25% più un'azione** delle ordinarie (≈12,5% del capitale totale). Le azioni privilegiate (P911) sono quotate a Francoforte; il pubblico detiene solo capitale senza voto.
- Le famiglie **Porsche e Piëch** controllano il 100% delle ordinarie di Porsche SE.

**Fonti primarie:** Volkswagen Group, *Annual Report 2025* — Shareholder structure; Porsche AG, Shareholder structure (IR); Porsche Automobil Holding SE, *Geschäftsbericht*.

**Classificazione:** Porsche SE **controllo di fatto tramite maggioranza dei voti** su VW (minoranza di capitale); VW **controllo di maggioranza** su Porsche AG; Porsche SE **minoranza di blocco diretta** in Porsche AG; Bassa Sassonia **minoranza con potere di veto statutario**.

---

### 3. Volkswagen Group / Traton SE e marchi

- ***[Da Ricerca A, non ricontrollato da B]*** **Volkswagen AG → Traton SE: ≈90% del capitale**, resto flottante. *Da riverificare sull'ultimo Annual Report Traton, non confermato con fonte primaria nella Ricerca B.*
- **Struttura Traton:** MAN (Germania), Scania (Svezia), **International Motors** (ex-Navistar, USA — ridenominazione effettiva **1° ottobre 2024**, data confermata da Ricerca B), Volkswagen Truck & Bus (Brasile/Sud America), marchio servizi RIO.
- **Punto critico confermato da entrambe le ricerche:** i **veicoli commerciali leggeri VW** (Transporter, Crafter, Caddy — marchio Volkswagen Nutzfahrzeuge) **NON fanno parte di Traton**: restano nel marchio Volkswagen core (auto). Traton = solo camion/bus pesanti.
- **Audi → Ducati:** controllata al 100% (via Lamborghini/Audi Sport).
- **SEAT / CUPRA:** CUPRA è un **marchio** di SEAT, S.A. (non un'entità legale separata); SEAT S.A. è la controllata VW che possiede entrambi i marchi.
- Altri marchi core: Volkswagen, Audi, Škoda, SEAT/CUPRA, Porsche (via VW→Porsche AG), Bentley, Lamborghini (sotto Audi).

**Fonti primarie:** Volkswagen Group, *Annual Report 2025*; Traton SE, *Annual Report*; Transport Topics (25/9/2024) sulla ridenominazione Navistar→International Motors.

**Classificazione:** VW **controllo di maggioranza** su Traton (~90%, da riconfermare); **proprietà piena (100%)** su Ducati; SEAT/CUPRA controllata VW con CUPRA sub-brand interno.

---

### 4. Stellantis N.V. (Form 20-F al 25 febbraio 2026)

- **Origine:** fusione paritaria PSA + FCA perfezionata il 16-17 gennaio 2021. **PSA e FCA non esistono più come entità legali autonome/quotate.**
- **Azionariato (capitale / voto, per effetto delle loyalty voting shares — voto aggiuntivo dopo 3 anni di detenzione continuativa registrata):**
  - **Exor N.V.: 15,48% del capitale / 23,84% dei voti** (449.410.092 azioni ordinarie + pari numero di Class A special voting shares).
  - **EPF — famiglia Peugeot, via Peugeot Invest e Peugeot 1810: 7,72% / 11,89%.**
  - **Bpifrance Participations: 6,64% / 10,22%.**
  - **Dongfeng Motor: ridotto a poco più dell'1%** (era 1,58% dopo il buyback di novembre 2023).
  - Flottante: resto sul mercato.
  - *Nota:* nel confronto con il Form 20-F 2024 (dati al 25/2/2025), i valori erano leggermente diversi (es. Exor 23,89% voto) — micro-variazioni annuali da riconfermare ad ogni nuovo 20-F.
- **Stellantis → Zhejiang Leapmotor: ≈21% del capitale** (acquisizione iniziale ~20% per €1,5 mld, ottobre 2023). **Leapmotor International B.V.: JV 51% Stellantis / 49% Leapmotor.** FAW ha acquisito un **5% di Leapmotor** per CN¥3,74 mld nel 2025.
- **Governance:** **Antonio Filosa** CEO (nominato 28 maggio 2025, pieni poteri dal 23 giugno 2025), succede a **Carlos Tavares** (uscito dicembre 2024). John Elkann resta Executive Chairman.
- **Marchi — piano FaSTLAne 2030 (€60 mld, Investor Day 21-22 maggio 2026):** **nessun marchio chiuso o venduto.** Quattro marchi globali (Jeep, Ram, Peugeot, Fiat); cinque regionali (Chrysler, Dodge, Citroën, Opel, Alfa Romeo); **DS e Lancia** gestiti come marchi "specialty" sotto Citroën e Fiat rispettivamente; **Maserati** confermata marchio di lusso puro (roadmap dettagliata attesa dicembre 2026). Risultati FY2025 (26/2/2026): perdita netta ≈€22,3 mld, guidata da un "reset" da ≈€22,2 mld annunciato il 6/2/2026.

**Fonti primarie:** Stellantis N.V., *Annual Report and Form 20-F for the year ended December 31, 2025* (25/2/2026); comunicato Stellantis-Leapmotor (8/5/2026); Automotive World su JV Leapmotor.

**Classificazione:** Exor **primo azionista, controllo di fatto rafforzato dal voto (non maggioranza assoluta)**; Leapmotor **partecipazione di minoranza significativa (~21%)** + **JV a controllo Stellantis (51%)**.

---

### 5. Mercedes-Benz Group AG

- **smart:** JV **paritaria 50/50** tra Mercedes-Benz AG e Zhejiang Geely Holding (smart Automobile Co., Ltd., costituita 2019, HQ Ningbo, operativa dal 2020).
- **Azionisti principali:**
  - **BAIC Group: 9,98% dei diritti di voto** (maggior azionista singolo).
  - **Geely (Li Shufu, via Tenaciou3 Prospect): 9,69% del capitale.**
  - **Kuwait Investment Authority: ≈4,97% del capitale** (ridotta a marzo 2023 dalla precedente ~6,8% — **la Ricerca A riportava ancora il dato obsoleto ~6,8%, superato dalla Ricerca B**; il valore esatto a luglio 2026 non è stato riconfermato su fonte primaria diretta nemmeno da B).
- **Daimler Truck Holding:** Mercedes-Benz mantiene **≈35%** dopo lo spin-off di dicembre 2021; il CFO Harald Wilhelm ha annunciato (12/2/2026) l'intenzione di vendere una parte della quota nel 2026, dettagli attesi a maggio.
- **AMG e Maybach:** divisioni/linee interne (Mercedes-AMG GmbH), non entità partecipate separatamente — da rappresentare come nodi figli senza arco percentuale.

**Fonti primarie:** Mercedes-Benz Group AG, pagina IR "Shareholder structure"; MarketScreener (12/2/2026) su vendita Daimler Truck; comunicato smart/Mercedes-Benz (2020).

**Classificazione:** smart **JV paritaria 50/50**; BAIC/Geely/KIA **partecipazioni di minoranza** (nessun controllo); Daimler Truck **ex-controllata scorporata con partecipazione residua di minoranza (~35%, in riduzione annunciata)**.

---

### 6. BMW Group

- **Famiglia Quandt/Klatten → BMW AG: ≈46,7% combinato** — Stefan Quandt ≈25,8% (via AQTON), Susanne Klatten ≈20,9% (via Susanne Klatten Beteiligungs GmbH). *Ripartizione confermata concordemente da fonti secondarie in entrambe le ricerche, ma non da un unico filing primario BMW: alcune fonti variano leggermente in base a come vengono contate le holding intermedie.*
- **Rolls-Royce Motor Cars: controllata al 100% da BMW.** Da tenere rigorosamente distinta da **Rolls-Royce Holdings plc** (motori aeronautici), società quotata completamente indipendente senza alcun legame azionario con l'auto.
- **BMW Brilliance Automotive (Cina): 75%** (aumentato dal 50% a partire da febbraio 2022).

**Fonti primarie:** BMW AG, *Geschäftsbericht/Annual Report*; comunicato BMW su aumento a 75% BMW Brilliance (2022).

**Classificazione:** Quandt/Klatten **controllo familiare di minoranza qualificata (~46,7%)**; Rolls-Royce Motor Cars **proprietà piena 100%**; BMW Brilliance **controllo di maggioranza (75%)**.

---

### 7. Interconnessioni cross-gruppo (archi trasversali)

> Le sezioni 8-13 che seguono provengono dalla **Ricerca C** (luglio 2026) e coprono i sei gruppi europei assenti nelle Ricerche A/B.

**Geely — hub principale del grafo:**
- **Volvo Cars: 78,7% del capitale** (ridotto dal precedente ~82% dopo la vendita di ~100 mln di azioni).
- **smart: JV 50/50** con Mercedes-Benz.
- **Mercedes-Benz Group: 9,69% del capitale.**
- **Aston Martin Lagonda: ridotta a ≈14%** dal picco ~17% (maggio 2023) — dato di fonte secondaria (Carscoops, maggio 2026, "insiders"), non da filing regolamentare; nello stesso periodo anche **Mercedes-Benz avrebbe ridotto la propria quota Aston Martin a <8%**. Il consorzio **Yew Tree (Lawrence Stroll)** resta primo azionista al 31%; Aston Martin ha richiesto capitale d'emergenza a maggio 2026.
- **Polestar:** controllata indirettamente (~80% combinato tramite Volvo Cars 18% + veicoli d'investimento Geely).
- Altri asset: Lotus/Lotus Technology, Lynk & Co, Zeekr, Proton, LEVC.

**Altri archi cross-gruppo:**
- **Renault ↔ Nissan ↔ Mitsubishi Motors:** vedi §1.
- **Stellantis ↔ Leapmotor:** vedi §4.
- **Doppia presenza cinese in Mercedes-Benz** (BAIC + Geely), con BAIC anche partner industriale (Beijing Benz JV in Cina).
- **Daimler-Renault-Nissan:** partecipazione incrociata triangolare (~3,1% reciproco) **sciolta nel 2021** — Daimler ha venduto la quota Renault a novembre 2021 via accelerated bookbuild (fonte: Euronews, 11/11/2021).
- **VW ↔ Rivian** *(nuovo, solo da Ricerca B)*: quota VW cresciuta da 8,6% a **15,9%** (VW primo azionista, scalzando Amazon); **JV "Rivian and Volkswagen Group Technologies" 50/50** (formalizzata novembre 2024) su architettura elettrica e software; impegno totale fino a $5,8 mld entro il 2027.
- **Northvolt** *(nuovo, solo da Ricerca B)*: fallita (bancarotta USA novembre 2024, svedese marzo 2025); VW ne deteneva ~21% (Goldman Sachs ~19%). Asset acquisiti da **Lyten** (2025-2026), a sua volta partecipata anche da **Stellantis** — arco indiretto Stellantis–ex-Northvolt; Scania (Traton) ha rilevato la divisione industriale di Northvolt Systems.

**Fonti primarie:** report annuali/comunicati IR Geely Holding, Volvo Cars, Aston Martin Lagonda; Rivian & Volkswagen Group, comunicato JV (12/11/2024); Euronews su scioglimento cross-holding Daimler-Renault (2021).

---

### 8. Ferrari N.V.

- **Origine:** scorporata da FCA nell'ottobre 2015, quotata a Milano e New York.
- **Azionariato:** **Exor N.V.: ≈21,33% del capitale / ≈32,32% dei diritti di voto**; **Piero Ferrari (tramite trust dedicato): ≈10,67% del capitale / ≈16,17% dei diritti di voto**, secondo maggiore azionista. **BlackRock: ≈3,38% dei diritti di voto** (gennaio 2026). Il flottante detiene circa il 64,2% del capitale ma solo circa il 48,13% dei voti, per effetto delle loyalty voting shares (stessa logica di Exor→Stellantis).
- **Accordo di consultazione Exor–famiglia Ferrari:** rinnovato il **3 gennaio 2026** per un triennio, sostituendo il patto rigido decennale del 2015; Ferrari ha ottenuto il **diritto unilaterale di scioglierlo con 30 giorni di preavviso**.
- **Governance:** John Elkann Executive Chairman (stesso ruolo che riveste in Stellantis, due gruppi distinti); Benedetto Vigna CEO.
- **Qualità del dato:** Reuters confirma una quota Exor "di circa il 20%" senza scomporre capitale/voto; la scomposizione puntuale (21,33%/32,32% e 10,67%/16,17%) proviene da un'analisi di settore secondaria (soar-analysis.com, 11 giugno 2026), non da un filing Exor o Ferrari. Da trattare come dato secondario nel grafo.

**Fonti:** Reuters, *Exor renews Ferrari shareholder agreement with founder's son* (3/1/2026); soar-analysis.com (11/6/2026); Exor N.V./Ferrari N.V., comunicato congiunto sul rinnovo del patto di consultazione.

**Classificazione:** Exor **primo azionista, minoranza rafforzata dal voto**; Piero Ferrari **secondo azionista di minoranza**.

---

### 9. AB Volvo / Volvo Group

- **Da non confondere con Volvo Cars:** AB Volvo (camion, autobus, macchine da costruzione) e Volvo Cars (automobili, controllata Geely) sono **entità distinte dal 1999**, quando Ford acquistò la divisione auto da AB Volvo.
- **Struttura azionaria a doppia classe:** azioni A (un voto) e azioni B (un decimo di voto), che concentra il potere decisionale rispetto al capitale nelle mani degli investitori istituzionali svedesi.
- **AB Industrivärden: ≈9,6% del capitale**, indicato come maggiore azionista singolo (fonte: aggregatore champsignal.com, dato al 20/12/2025). La pagina ufficiale Volvo Group Investor Relations sull'azionariato è stata individuata ma la tabella dinamica degli azionisti non è stata estraibile con un fetch statico in questa ricerca.
- **Non verificato:** la ripartizione precisa dei diritti di voto di Industrivärden e della sfera Wallenberg/Investor AB, entrambi tradizionalmente centrali nella governance dei gruppi svedesi, non è stata confermata su fonte primaria.
- **Ripartizione geografica del capitale** (MarketScreener): Svezia ≈27,6-31,5%, Cina ≈5,6%, Norvegia ≈0,9-1,9%, USA ≈0,5% — dato aggregato per paese, non un singolo azionista identificato.
- **Legame storico con Renault Trucks:** Renault Veicoli Industriali (RVI) fu venduta a Volvo Group nel 2001; Renault SA ricevette in cambio una quota di circa il 15% in Volvo Group, dismessa gradualmente negli anni successivi. Il marchio Renault Trucks conserva il nome ma non ha più alcun legame azionario con Renault Group.
- **Marchi:** Volvo Trucks, Mack Trucks (USA, dal 2000), Volvo Buses, Renault Trucks.

**Fonti:** Volvo Group, pagina IR *Ownership information* (struttura pagina estratta, tabella dinamica non catturata); champsignal.com (20/12/2025); MarketScreener, ripartizione geografica azionariato Volvo Group; nota storica di settore sulla transazione RVI/Volvo del 2001.

**Classificazione:** AB Industrivärden **primo azionista di minoranza (dato secondario)**; Renault Trucks **relazione storica cessata con Renault Group, oggi controllata al 100% da Volvo Group**.

---

### 10. Iveco Group

- **Origine:** scorporata da CNH Industrial nel **gennaio 2022**, sede a Torino.
- **Exor N.V.: 27,1% del capitale / 43,1% dei diritti di voto** (Reuters 18/7/2025, Yahoo Finance 21/7/2025, Construction World 22/7/2025 — dato coerente su più fonti). Quota ereditata proporzionalmente dal demerger CNH Industrial 2022.
- ***Scartato per bassa qualità:*** una fonte aggregatrice riportava anche una quota Exor in CNH Industrial (~45,5%/43,1% voto) internamente incoerente; non utilizzata nel grafo.
- **Acquisizione da parte di Tata Motors (India):** annunciata il **30 luglio 2025** — tender offer volontaria interamente in contanti, ≈€3,8 miliardi / €14,1 per azione, esclusa la divisione difesa. **Precondizione:** vendita del business difesa di Iveco a **Leonardo S.p.A.** per €1,7 miliardi (termine contrattuale 31/3/2026). **Golden Power** italiano concesso il 31 ottobre 2025. Chiusura attesa nel **terzo trimestre 2026** secondo le fonti più solide; una fonte secondaria di basso profilo la definisce già conclusa, in contraddizione con fonti più caute datate fino al 30 giugno 2026 e al 7 maggio 2026 che la descrivono ancora pendente. **Stato non risolto in modo definitivo a fine luglio 2026.**
- **Marchi:** Iveco, IVECO Bus, FPT Industrial (motori e propulsori).

**Fonti:** Reuters, *Agnellis in talks over Iveco sale, Tata Motors has made approach* (18/7/2025); Iveco Group, comunicato *Tata Motors to Acquire Iveco Group* (30/7/2025); Yahoo Finance (21/7/2025); Construction World (22/7/2025).

**Classificazione:** Exor **azionista di controllo di fatto (minoranza rafforzata dal voto)**; Tata Motors **operazione di acquisizione annunciata, non confermata come chiusa**.

---

### 11. Bugatti Rimac

- **Joint venture 2021:** Rimac Group 55% / Porsche AG 45%, costituita per il marchio Bugatti.
- **Uscita di Porsche (24 aprile 2026):** Porsche ha venduto l'intera quota del 45% in Bugatti Rimac **e** la quota separata del 20,6% in Rimac Group a un consorzio guidato da **HOF Capital** (società di investimento di New York); operazione firmata dal CEO Porsche Michael Leiters. Confermato da Porsche Newsroom (EN/DE) e corroborato da Carscoops, CNBC, Road & Track, electrive.com, ecomento.de, autocolumn.com.
- **Effetto:** Rimac Group (a maggioranza di Mate Rimac) assume il controllo pieno/rafforzato di Bugatti Rimac; il legame Porsche-Bugatti Rimac è oggi **storico/cessato**.

**Fonti:** Porsche Newsroom, *Porsche sells its stakes in Bugatti Rimac and Rimac Group to an international consortium* (24/4/2026); Wikipedia, *Bugatti Rimac*; Carscoops, CNBC (riscontro secondario).

**Classificazione:** Rimac Group **controllo di maggioranza (55%, rafforzato dopo l'uscita Porsche)**; Porsche AG **relazione storica cessata (aprile 2026)**.

---

### 12. McLaren Group / McLaren Automotive / McLaren Racing

- **Mumtalakat Holding Company** (fondo sovrano del Bahrein): azionista di McLaren dal 2007 (quota iniziale 30% dagli azionisti fondatori), ha raggiunto il **controllo totale (100%)** nel **marzo 2024** tramite conversione di azioni privilegiate.
- **McLaren Automotive** (il costruttore di supercar) è modellata come controllata al 100% da McLaren Group.
- **McLaren Racing** (team di Formula 1, governance storicamente distinta): nel **settembre 2025** gli azionisti minoritari **MSP Sports Capital** sono stati acquistati da Mumtalakat insieme a **CYVN Holdings** (fondo di Abu Dhabi, già azionista di NIO), che ne diventano co-proprietari; McLaren Racing valutata £3,5 miliardi dopo l'operazione.

**Fonti:** BBC, *Bahrain takes full control of supercar brand McLaren* (22/3/2024); AGBI; McLaren, comunicato sul consolidamento della struttura azionaria di McLaren Racing (2/9/2025); BBC, *McLaren Racing valued at £3.5bn after ownership change* (2/9/2025).

**Classificazione:** Mumtalakat **proprietà piena (100%) di McLaren Group**; CYVN Holdings **partecipazione di minoranza in McLaren Racing**.

---

### 13. Jaguar Land Rover

- **Tata Motors (India): 100% dal 2008**, quando rilevò i marchi Jaguar e Land Rover da Ford. Dato di conoscenza generale ampiamente consolidato, **non riverificato su un filing primario specifico** in questa sessione (un tentativo di fetch diretto su jlr.com/company ha restituito 404).
- **Rilevanza per il grafo:** con l'acquisizione di Iveco Group (§10), Tata Motors diventerebbe proprietaria di **due** importanti gruppi europei — un parallelo diretto alla doppia presenza cinese già presente altrove nel grafo (Geely, BAIC, FAW, Dongfeng), ma con un investitore indiano.

**Fonti:** nota di settore consolidata (acquisizione Ford→Tata Motors 2008); nessuna verifica puntuale su fonte primaria in questa ricerca.

**Classificazione:** Tata Motors **proprietà piena (100%), dato di fonte secondaria/generale.**

---

### 14. Partnership industriali e partecipazioni incrociate aggiuntive (Ricerca D)

> Questa sezione proviene dalla **Ricerca D** (luglio 2026) e collega entità già presenti nel grafo con archi finora non mappati. Nessun dato proviene da un filing primario diretto: tutte le quote sono di fonte secondaria (stampa finanziaria e comunicati aziendali) o di conoscenza generale di settore, e vanno trattate con grado di certezza inferiore a quello della Ricerca B.

**Investimenti azionari di minoranza:**
- **Hyundai Motor Group → Rimac Group (~12%):** nel 2019 Hyundai Motor e Kia investirono insieme circa 80 milioni di euro nel costruttore croato di hypercar e tecnologia EV. La quota combinata (~12%) è sopravvissuta alla riorganizzazione del 2021 che ha creato Bugatti Rimac. Ripartizione esatta non riverificata su fonte primaria.
- **Volkswagen → XPeng (~5%):** Volkswagen ha investito circa 700 milioni di dollari nel luglio 2023 per una quota di minoranza (~5%) nel costruttore cinese di veicoli elettrici, con l'obiettivo di co-sviluppare piattaforme elettriche per il mercato cinese.
- **Exor → CNH Industrial (~26,9% capitale / ~42,5% voti):** Exor è l'azionista di controllo di fatto di CNH Industrial (macchine agricole e da costruzione, marchi Case IH e New Holland) grazie alle azioni a voto speciale — la **stessa struttura di loyalty shares** che concentra il potere di voto degli Agnelli in Stellantis e Ferrari. CNH è la società **da cui Iveco Group è stata scorporata nel gennaio 2022**: la sua inclusione completa la mappa dei veicoli industriali del gruppo Exor.

**Alleanze e cooperazioni senza scambio azionario:**
- **Volkswagen ↔ Ford:** alleanza industriale senza cross-holding. Ford costruisce le elettriche **Explorer** e **Capri** sulla piattaforma **MEB** di Volkswagen e i due gruppi condividono i pickup **Ranger** e **Amarok**. La JV sulla guida autonoma **Argo AI** è stata chiusa nel 2022 e da allora la cooperazione si è ristretta agli accordi già avviati.
- **BMW ↔ Toyota:** cooperazione senza scambio azionario. Piattaforma sportiva condivisa (**BMW Z4** e **Toyota Supra**) e sviluppo congiunto di sistemi a **celle a combustibile a idrogeno**, rilanciato nel 2024-2025.
- **Stellantis ↔ Toyota:** accordo di fornitura senza scambio azionario. I van **Toyota Proace** e **Proace City** sono versioni rimarchiate dei veicoli commerciali Stellantis (ex piattaforma PSA), con produzione condivisa in Europa.

**Fonti:** comunicati Hyundai Motor Group e stampa di settore sull'investimento 2019 in Rimac; stampa finanziaria sull'investimento Volkswagen in XPeng (luglio 2023); comunicati Volkswagen/Ford e BMW/Toyota sulle rispettive alleanze; comunicati Stellantis (ex PSA)/Toyota sulla fornitura di veicoli commerciali; Exor N.V. e documenti azionari CNH Industrial.

**Classificazione:** Hyundai Motor Group, Volkswagen (→XPeng) ed Exor (→CNH) **partecipazioni di minoranza** (Exor→CNH con divergenza capitale/voto); Volkswagen↔Ford, BMW↔Toyota e Stellantis↔Toyota **alleanze o cooperazioni industriali senza cross-holding** — categoria visivamente distinta dall'alleanza *con* cross-holding di tipo Renault-Nissan.

---

### 15. Costruttori europei indipendenti e di nicchia + azionariato completo di Aston Martin (Ricerca D, estensione)

> Questa sezione completa la mappa europea con i costruttori indipendenti non legati agli otto grandi gruppi e con gli azionisti di Aston Martin finora non rappresentati. Come per il §14, i dati sono di fonte secondaria o di conoscenza generale di settore; molte di queste società non sono quotate, quindi le quote sono ordini di grandezza e non valori da filing.

**Costruttori indipendenti e di nicchia (con proprietà):**
- **Pagani** (Italia, hypercar): interamente controllata dal fondatore **Horacio Pagani** e famiglia. Nessun azionista esterno.
- **Koenigsegg** (Svezia, hypercar): controllo di maggioranza del fondatore **Christian von Koenigsegg**. Nel 2019 **NEVS** (National Electric Vehicle Sweden, gruppo **Evergrande**) investì circa 150 mln $ per il **20%** più una JV per un'EV accessibile; la relazione è **di fatto decaduta** con il crollo di Evergrande (2022-2024) — rappresentata come relazione cessata, con NEVS come entità fallita.
- **Ineos Automotive** (Regno Unito, fuoristrada Grenadier): divisione al **100%** del gruppo chimico **INEOS** di Sir Jim Ratcliffe; produce a Hambach (Francia), stabilimento ex-Smart rilevato da Mercedes nel 2020.
- **Automobili Pininfarina** (Germania, hyper-EV Battista): controllata al **100%** dal gruppo indiano **Mahindra**, distinta dalla casa di design Pininfarina S.p.A. (anch'essa ~76% Mahindra).
- **Morgan** (Regno Unito, artigianale): maggioranza del fondo di private equity italiano **Investindustrial** dal 2019; famiglia Morgan e dipendenti conservano una minoranza. Investindustrial è stato **in passato azionista di Aston Martin** (2013-2020, ~37,5%), poi uscito con l'arrivo di Yew Tree — arco storico cessato che collega Morgan al resto del grafo.

**Azionariato completo di Aston Martin** (oltre a Yew Tree 31% e Geely ~14% già presenti):
- **Saudi PIF (Public Investment Fund): ~16-18%**, secondo maggiore azionista dal 2022, con seggi nel consiglio. Quota potenzialmente variata dai numerosi aumenti di capitale.
- **Mercedes-Benz: <8%**, in diluizione da un massimo un tempo destinato al 20%. Deriva dalla partnership tecnologica (motori AMG, architettura elettrica/elettronica) in cambio di azioni.

**Fonti:** note di settore consolidate su Pagani/Koenigsegg/Ineos/Pininfarina/Morgan (società in gran parte non quotate); stampa finanziaria sull'accordo Koenigsegg-NEVS (2019) e sul crollo di Evergrande; stampa finanziaria sull'ingresso di Saudi PIF in Aston Martin (2022) e sulla diluizione della quota Mercedes.

**Classificazione:** Horacio Pagani e Christian von Koenigsegg **controllo pieno/di maggioranza** dei rispettivi marchi; INEOS→Ineos Automotive e Mahindra→Automobili Pininfarina **proprietà piena (100%)**; Investindustrial→Morgan **controllo di maggioranza**; NEVS→Koenigsegg e Investindustrial→Aston Martin **relazioni storiche cessate**; Saudi PIF e Mercedes-Benz→Aston Martin **partecipazioni di minoranza**.

---

## Recommendations — passi operativi per il grafo

1. **Usa la Ricerca B come fonte primaria per ogni percentuale numerica**; consulta la Ricerca A solo come traccia storica/contesto, non come dato da citare direttamente.
2. **Modella capitale e voto come due attributi dello stesso arco**, non come archi separati: Porsche SE→VW, Bassa Sassonia→VW, Qatar→VW, Exor/EPF/Bpifrance→Stellantis, Renault→Nissan.
3. **Classificazione tipi di arco (colore/stile):**
   - *Proprietà piena 100%*: BMW→Rolls-Royce Motor Cars; Audi→Ducati; **INEOS→Ineos Automotive**; **Mahindra→Automobili Pininfarina**.
   - *Controllo di maggioranza*: Porsche SE→VW (voto), VW→Porsche AG (75%-1), VW→Traton (~90%, da riconfermare), BMW→BMW Brilliance (75%), Geely→Volvo Cars (78,7%), **Investindustrial→Morgan**, **fondatori→Pagani e Koenigsegg**.
   - *Minoranza significativa*: Renault→Nissan (35,71% cap./15% voto), Mercedes→Daimler Truck (~35%), Stellantis→Leapmotor (~21%), VW→Rivian (15,9%), Nissan→Mitsubishi Motors (24,05%), Exor/EPF/Bpifrance→Stellantis, BAIC/Geely/KIA→Mercedes, Geely→Aston Martin (~14%), **Hyundai/Kia→Rimac Group (~12%)**, **VW→XPeng (~5%)**, **Exor→CNH Industrial (~26,9% cap./~42,5% voti)**, **Saudi PIF→Aston Martin (~16-18%)**, **Mercedes→Aston Martin (<8%)**.
   - *JV paritaria 50/50*: smart (Geely/Mercedes); Rivian-VW Group Technologies.
   - *JV a controllo*: Leapmotor International (51/49 Stellantis/Leapmotor).
   - *Alleanza o cooperazione industriale senza cross-holding (Ricerca D)*: **VW↔Ford** (piattaforma MEB, pickup Ranger/Amarok), **BMW↔Toyota** (Z4/Supra, idrogeno), **Stellantis↔Toyota** (van Proace) — da tenere visivamente distinta dall'alleanza *con* cross-holding di tipo Renault-Nissan.
   - *Relazione storica cessata (tratteggiata)*: Daimler-Renault-Nissan cross-holding (2021); Honda-Nissan fusione (fallita 2025); Northvolt (fallita, asset a Lyten); Porsche AG→Bugatti Rimac/Rimac Group (aprile 2026); Renault Group→Renault Trucks (2001); **NEVS→Koenigsegg (crollo Evergrande, 2019-2022)**; **Investindustrial→Aston Martin (2013-2020)**.
   - *Operazione di acquisizione annunciata ma non confermata come chiusa*: Tata Motors→Iveco Group (annuncio 30/7/2025, chiusura attesa T3 2026, non confermata a fine luglio 2026) — categoria da tenere visivamente distinta da una proprietà già consolidata.
4. **Marchi vs entità legali:** CUPRA, AMG, Maybach, Vauxhall, RIO = **sub-brand interni** (nodi figli senza arco percentuale), non società partecipate.
5. **Datazione obbligatoria su ogni arco** ("as of [data documento]"). I nodi più dinamici da rivedere periodicamente: Renault-Nissan (trust), Stellantis-Leapmotor, quote Geely (Aston Martin, Volvo), quota Mercedes in Daimler Truck, chiusura Tata Motors-Iveco Group.
6. **Priorità di verifica residua** (nessuna delle due ricerche l'ha risolta): quota Mitsubishi Corporation in Mitsubishi Motors; quota puntuale VW in Traton (~90%, solo da Ricerca A); stato della clausola di investimento Renault-Nissan in Ampere (probabilmente superata dal ritiro dell'IPO Ampere nel 2024).
7. **Soglie di rivalutazione a data fissa:** dicembre 2026 (roadmap Maserati definitiva); qualsiasi comunicato su esecuzione della riduzione Nissan→Renault dal 15% al 10%; esecuzione della vendita parziale Daimler Truck annunciata a maggio 2026; **esito definitivo della chiusura Tata Motors-Iveco Group (T3 2026)**.
8. **Nuove priorità di verifica (Ricerca C):** scomposizione capitale/voto di Exor e Piero Ferrari in Ferrari (solo fonte secondaria); ripartizione dei diritti di voto di AB Industrivärden/sfera Wallenberg in AB Volvo; conferma primaria del controllo Tata Motors su Jaguar Land Rover.

---

## Caveats

- **Metodo di integrazione:** questo documento privilegia sistematicamente i dati della Ricerca B (verificata su fonti primarie con URL/data) sopra quelli della Ricerca A (stime senza accesso a strumenti). Dove A conteneva un dato non ripreso da B, è segnalato esplicitamente come "da riverificare" (Traton ~90%, clausola Ampere).
- **Dati intrinsecamente dinamici** anche nella Ricerca B: azionariati Stellantis, Geely (Aston Martin/Volvo), quota Daimler Truck e riduzione Nissan→Renault al 10% possono cambiare nei mesi successivi a luglio 2026 e vanno riverificati ad ogni uso del grafo.
- **Distinzione fonti primarie vs secondarie nella Ricerca B stessa:** i dati Volkswagen, Stellantis, Renault, Mercedes (pagina IR), smart, Leapmotor International, Nissan/Mitsubishi (buyback) e Daimler Truck provengono da fonti primarie societarie o filing. I dati su **Geely-Aston Martin (~14%), KIA-Mercedes (riduzione 2023), ripartizione Quandt/Klatten e quota residua Dongfeng** provengono da media affermati (Reuters, Automotive News, Bloomberg, Carscoops) o aggregatori, e vanno trattati con un grado di certezza inferiore.
- **Bassa Sassonia→VW (≈11,8% del capitale totale):** valore proveniente dalla sola Ricerca A; la Ricerca B conferma il 20,0% dei voti ma non ricontrolla puntualmente la percentuale di capitale — da riverificare sul bilancio VW se necessaria nel grafo.
- **Mitsubishi Corporation in Mitsubishi Motors:** percentuale residua **non verificata su fonte primaria in nessuna delle due ricerche.**
- **Effetto dei buyback in corso** (Mercedes, Stellantis): alterano progressivamente le percentuali degli azionisti esistenti; i valori riportati sono fissati alle date dei documenti citati (VW 31/12/2025; Stellantis 25/2/2026; Mercedes pagina IR corrente al momento della Ricerca B).
- **Qualità delle fonti nella Ricerca C (§8-§13):** a differenza della Ricerca B, quasi nessun dato proviene da un filing societario primario direttamente consultato. Le eccezioni sono i comunicati ufficiali Porsche Newsroom (Bugatti Rimac/Rimac Group) e Iveco Group (acquisizione Tata Motors), citati come fonti dirette dell'annuncio ma non come filing regolamentari con il dettaglio delle quote. Tutti gli altri dati (Ferrari, AB Volvo/Industrivärden, McLaren, Jaguar Land Rover) provengono da stampa finanziaria o aggregatori azionari e vanno trattati con un grado di certezza inferiore a quello della Ricerca B.
- **Scomposizione capitale/voto di Ferrari (Exor 21,33%/32,32%; Piero Ferrari 10,67%/16,17%):** proviene da un'analisi di settore secondaria (soar-analysis.com), non da un filing Exor o Ferrari; Reuters corrobora solo l'ordine di grandezza ("circa il 20%").
- **Ripartizione dei diritti di voto in AB Volvo:** la pagina ufficiale Volvo Group Investor Relations sull'azionariato non ha restituito la tabella dinamica degli azionisti con un fetch statico; il dato AB Industrivärden ≈9,6% proviene da un aggregatore secondario (champsignal.com) e la ripartizione della sfera Wallenberg/Investor AB resta non verificata.
- **Chiusura dell'acquisizione Tata Motors-Iveco Group:** stato ambiguo tra le fonti a fine luglio 2026 — alcune fonti secondarie di basso profilo la indicano già conclusa, la maggioranza delle fonti (incluse quelle più recenti, fino al 30/6/2026) la indica ancora attesa nel terzo trimestre 2026. Da riverificare prima di rappresentarla come proprietà consolidata nel grafo.
- **Controllo Tata Motors su Jaguar Land Rover (100% dal 2008):** dato di conoscenza generale ampiamente consolidato ma non riverificato su un filing primario specifico in questa sessione.
- **Qualità delle fonti nella Ricerca D (§14):** nessun dato proviene da un filing primario diretto. Le quote (Hyundai/Kia ~12% in Rimac, VW ~5% in XPeng, Exor ~26,9% cap./~42,5% voti in CNH Industrial) provengono da stampa finanziaria e conoscenza generale di settore e sono da considerare ordini di grandezza, non valori riverificati. Le tre cooperazioni senza scambio azionario (VW-Ford, BMW-Toyota, Stellantis-Toyota) sono relazioni industriali/contrattuali, non partecipazioni: sono rappresentate nel grafo con l'arco “alleanza o cooperazione industriale” e non comportano alcuna quota.
- **Qualità delle fonti nella Ricerca D — costruttori indipendenti (§15):** Pagani, Koenigsegg, Ineos Automotive, Automobili Pininfarina e Morgan sono in gran parte società non quotate: le indicazioni di controllo (100% familiare/di gruppo, “maggioranza”) sono di conoscenza generale, non da filing. Lo stato legale della quota NEVS (20%) in Koenigsegg dopo il crollo di Evergrande non è chiaro ed è trattato come relazione cessata. Le quote Saudi PIF (~16-18%) e Mercedes (<8%) in Aston Martin provengono da stampa finanziaria e possono essere variate dai numerosi aumenti di capitale della casa britannica.

---

## Riferimenti (APA) — fonti primarie citate nella Ricerca B

Alliance Renault-Nissan-Mitsubishi. (2024, marzo 27). *Renault Group sold to Nissan 99,132,100 Nissan shares for €358 million*. https://media.alliancernm.com/?p=283890

Alliance Renault-Nissan-Mitsubishi. (2023). *Renault Group sold 211,000,000 Nissan shares for €764 million*. https://media.alliancernm.com/renault-group-sold-211000000-nissan-shares-for-eur764-million/

Automotive World. (2026). *Stellantis and Leapmotor deepen their JV ties*. https://www.automotiveworld.com/news/stellantis-and-leapmotor-deepen-their-jv-ties/

Carscoops. (2026, maggio). *Aston Martin asked for emergency cash for the 8th time, and Geely's watching*. https://www.carscoops.com/2026/05/aston-martin-emergency-cash/

Carscoops. (2025, febbraio). *Nissan to end Honda merger talks, Foxconn back on the table*. https://www.carscoops.com/2025/02/nissan-ends-merger-talks-with-honda-foxconn-is-back-on-the-table/

Daimler Truck. (2025). *Shareholder structure*. https://www.daimlertruck.com/en/investors/share/shareholder-structure

Euronews. (2021, novembre 11). *Daimler unwinds cross-ownership with Renault stake sale*. https://www.euronews.com/next/2021/11/11/daimer-renault-stake-sale

MarketScreener. (2026, febbraio 12). *Mercedes-Benz plans to sell portion of Daimler Truck stake*. https://www.marketscreener.com/news/mercedes-benz-plans-to-sell-portion-of-daimler-truck-stake-ce7e5ddedc81fe21

Mercedes-Benz Group AG. (2026). *Shareholder structure*. https://group.mercedes-benz.com/investors/share/shareholder-structure/

Mitsubishi Motors Corporation. (2024, novembre 7). *Mitsubishi Motors acquires its own shares from Nissan*. https://www.mitsubishi-motors.com/en/newsroom/newsrelease/2024/20241107_2.html

Motor1. (2023). *Geely now owns 17 percent of Aston Martin Lagonda*. https://www.motor1.com/news/667843/geely-17-percent-stake-aston-martin/

Porsche AG. (2025). *Shareholder structure*. https://investorrelations.porsche.com/en/the-share/shareholder-structure

Renault Group. (2025, luglio 1). *Evolution of the accounting treatment of Renault Group's stake in Nissan*. https://media.renaultgroup.com/evolution-of-the-accounting-treatment-of-renault-groups-stake-in-nissan/

Renault Group. (2024, settembre). *Renault Group to sell to Nissan up to 195,473,600 Nissan shares*. https://media.renaultgroup.com/?p=240344

Rivian Automotive & Volkswagen Group. (2024, novembre 12). *Rivian and Volkswagen Group announce the launch of their joint venture*. https://rivian.com/newsroom/article/rivian-and-volkswagen-group-announce-the-launch-of-their-joint-venture

smart / Mercedes-Benz. (2020). *Mercedes-Benz and Geely Holding formally established global joint venture "smart Automobile Co., Ltd."*. https://media.smart.com/mercedes-benz-and-geely-holding-formally-established-global-joint-venture-smart-automobile-co-ltd-for-the-smart-brand/

Stellantis N.V. (2026, febbraio 25). *Annual Report and Form 20-F for the year ended December 31, 2025*. https://www.stellantis.com/content/dam/stellantis-corporate/investors/financial-reports/Stellantis-NV-20251231-Annual-Report-and-Form-20-F.pdf

Stellantis. (2026, maggio 8). *Stellantis and Leapmotor announce their intention to take their strategic partnership to the next level*. https://www.stellantis.com/en/news/press-releases/2026/may/stellantis-and-leapmotor-announce-their-intention-to-take-their-strategic-partnership-to-the-next-level

Transport Topics. (2024, settembre 25). *Navistar to rebrand as International Motors*. https://www.ttnews.com/articles/navistar-rebrand-intl

Volkswagen Group. (2026). *Shareholder structure — Annual Report 2025*. https://annualreport2025.volkswagen-group.com/group-management-report/shares-and-bonds/shareholder-structure.html

Volvo Cars. (2024, febbraio 22). *Volvo Cars to propose a distribution of 62.7 percent of its Polestar shareholding to its shareholders*. https://www.volvocars.com/intl/media/press-releases/189C5D9BCA1BE81A/

## Riferimenti (APA) — fonti della Ricerca C (luglio 2026)

AGBI. (2024). *Bahraini fund takes control of British carmaker McLaren*. https://www.agbi.com/

BBC News. (2024, marzo 22). *Bahrain takes full control of supercar brand McLaren*. https://www.bbc.com/news/business-68639320

BBC Sport. (2025, settembre 2). *McLaren Racing valued at £3.5bn after ownership change*. https://www.bbc.com/sport/formula1/articles/cwypy6zpr39o

Carscoops. (2026, aprile). *Porsche sells its stakes in Bugatti Rimac and Rimac Group*. https://www.carscoops.com/

champsignal.com. (2025, dicembre 20). *AB Volvo — struttura azionaria*.

Construction World. (2025, luglio 22). *Exor's stake in Iveco Group*.

Iveco Group N.V. (2025, luglio 30). *Tata Motors to Acquire Iveco Group, Together Creating a Global Player in Commercial Vehicles*. https://www.ivecogroup.com/media/corporate_press_releases/2025/july/tata_motors_to_acquire_iveco_group_together_creating_a_global_player_in_commercial_vehicles

McLaren. (2025, settembre 2). *McLaren Racing consolidates shareholder structure*. https://www.mclaren.com/racing/latest-news/2025/mclaren-racing-consolidates-shareholder-structure/

Porsche Newsroom. (2026, aprile 24). *Porsche sells its stakes in Bugatti Rimac and Rimac Group to an international consortium*. https://newsroom.porsche.com/en/2026/company/porsche-bugatti-rimac-stakes-42221.html

Reuters. (2025, luglio 18). *Agnellis in talks over Iveco sale, Tata Motors has made approach, sources say*. https://www.reuters.com/world/india/agnellis-talks-over-iveco-sale-tata-motors-has-made-approach-sources-say-2025-07-18/

Reuters. (2026, gennaio 3). *Exor renews Ferrari shareholder agreement with founder's son*. https://www.reuters.com/sustainability/sustainable-finance-reporting/exor-renews-ferrari-shareholder-agreement-with-founders-son-2026-01-03/

soar-analysis.com. (2026, giugno 11). *Ferrari — azionariato ed effetto delle loyalty voting shares*.

Wikipedia. (2026). *Bugatti Rimac*. https://en.wikipedia.org/wiki/Bugatti_Rimac

Yahoo Finance. (2025, luglio 21). *Exor, Iveco Group and the Tata Motors approach*.

## Riferimenti (APA) — fonti della Ricerca D (luglio 2026)

> Nota: le fonti della Ricerca D provengono da conoscenza generale di settore e da stampa finanziaria ampiamente riportata; non sono state riverificate su un filing primario o su un URL specifico in questa sessione. Sono elencate per tracciabilità dell'affermazione, non come citazione documentale diretta.

BBC News / stampa di settore. (2019, maggio 14). *Hyundai Motor Group and Kia invest around €80 million in Rimac Automobili*.

BMW Group & Toyota Motor Corporation. (2013-2025). *Comunicati congiunti sulla piattaforma sportiva condivisa (Z4/Supra) e sulla cooperazione sui sistemi a celle a combustibile a idrogeno*.

CNH Industrial N.V. & Exor N.V. (2026). *Struttura azionaria di CNH Industrial e azioni a voto speciale (loyalty shares)*.

Ford Motor Company & Volkswagen AG. (2019-2023). *Comunicati sull'alleanza industriale: piattaforma MEB per Ford Explorer/Capri, pickup Ranger/Amarok, chiusura di Argo AI (2022)*.

Reuters / stampa finanziaria. (2023, luglio 26). *Volkswagen to invest about $700 million in China's XPeng for a stake of roughly 5%*.

Stellantis (ex Groupe PSA) & Toyota Motor Corporation. (2016-2024). *Comunicati sulla fornitura dei veicoli commerciali rimarchiati Toyota Proace / Proace City*.

INEOS Automotive. (2020-2026). *The Grenadier and the Hambach plant acquired from Mercedes-Benz*.

Investindustrial. (2019). *Investindustrial acquires a majority stake in Morgan Motor Company; former stake in Aston Martin (2013-2020)*.

Mahindra & Mahindra / Automobili Pininfarina. (2018-2026). *Automobili Pininfarina GmbH and the Battista hyper-EV*.

Reuters / stampa finanziaria. (2022). *Saudi Arabia's Public Investment Fund becomes second-largest shareholder in Aston Martin*.

Stampa di settore. (2019-2024). *Koenigsegg-NEVS partnership (20% stake, 2019) and the collapse of Evergrande*.

*Nota metodologica finale:* questo documento è una fusione di quattro ricerche indipendenti sullo stesso tema (due ricerche compass_artifact originarie, una terza ricerca di estensione sui gruppi europei e una quarta ricerca su partnership industriali e costruttori indipendenti, luglio 2026). Ove non altrimenti specificato nei Caveats, ogni dato numerico dei §1-§7 proviene dalla Ricerca B (con verifica su fonte primaria), ogni dato dei §8-§13 proviene dalla Ricerca C (prevalentemente fonti secondarie, con verifica primaria solo per gli annunci Porsche Newsroom e Iveco Group) e ogni dato dei §14-§15 proviene dalla Ricerca D (partnership, partecipazioni incrociate e costruttori indipendenti, interamente di fonte secondaria o conoscenza generale di settore); le voci esplicitamente marcate "da Ricerca A, non confermato/ricontrollato da B" restano da riverificare prima di un uso definitivo nel grafo.
