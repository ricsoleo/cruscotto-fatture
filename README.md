# Fatture elettroniche XML in Excel, gratis e senza caricare file

**Usalo qui: https://ricsoleo.github.io/cruscotto-fatture/strumento.html**

Uno strumento che legge le fatture elettroniche italiane (FatturaPA, SdI) direttamente nel browser e le trasforma in
un file Excel. I file non vengono caricati su nessun server: restano sul tuo computer, e la pagina funziona anche
staccando internet dopo averla aperta.

## Cosa legge
- File `.xml` FatturaPA (FPR12 e FPA12), anche con più fatture nello stesso file.
- File firmati `.xml.p7m`, anche codificati in base64.
- Archivi `.zip` scaricati dal cassetto fiscale o esportati dal gestionale, anche misti.
- Fatture duplicate, per esempio la stessa in `.xml` e in `.p7m`: vengono contate una volta sola.

## Cosa ottieni
- Riconoscimento automatico della tua azienda e divisione fra fatture emesse e ricevute.
- Fatturato mese per mese, con le note di credito (TD04) sottratte e le autofatture (TD16–TD28) escluse.
- Primi 10 clienti degli ultimi 12 mesi.
- Scadenze dei prossimi 60 giorni indicate nelle fatture emesse.
- Un Excel con i fogli Fatture emesse, Fatture ricevute, Righe (il dettaglio di ogni riga, che spesso gli export dei
  portali non danno), Scadenze, Fatturato mensile.

## Dove trovare le fatture
Sul portale **Fatture e Corrispettivi** dell'Agenzia delle Entrate (accesso con SPID, CIE o CNS) → Consultazione →
fatture emesse o ricevute, scegliendo il periodo. Oppure chiedi lo zip al tuo gestionale o al commercialista.

## Il cruscotto completo
Lo strumento gratuito legge le fatture, non il conto in banca: non sa chi ha già pagato. Il
[cruscotto completo](https://ricsoleo.github.io/cruscotto-fatture/) abbina anche gli incassi e mostra crediti
scaduti per anzianità, clienti da sollecitare, incassi attesi nelle prossime settimane e stima dell'IVA del mese.
Un [esempio con dati inventati](https://ricsoleo.github.io/cruscotto-fatture/esempio.html).

Contatti: pistore3141592@gmail.com
