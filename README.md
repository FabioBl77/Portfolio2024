# Portfolio2024

Portfolio2024 e un sito web statico realizzato in HTML e CSS per presentare il profilo professionale di Fabio Blanna. Il progetto funziona senza backend, database o fase di compilazione: basta aprire `index.html` in un browser per visualizzare il sito.

## Scopo del programma

Il programma e un portfolio personale pensato per raccogliere in un unico punto:

- una presentazione professionale;
- il curriculum vitae in formato PDF;
- le conoscenze e competenze tecniche;
- i progetti realizzati;
- i collegamenti alle pagine interne del sito.

L'obiettivo principale e fornire una pagina semplice, consultabile e facilmente condivisibile, utile per candidature, presentazioni personali o pubblicazione online tramite servizi di hosting statico.

## Come funziona

Il sito e composto da piu pagine HTML collegate tra loro da link di navigazione. Ogni pagina contiene una parte specifica del portfolio, mentre il file `styles.css` definisce l'aspetto grafico comune.

Non sono richiesti server, linguaggi lato backend, framework JavaScript o installazioni aggiuntive. Il browser legge direttamente i file HTML e applica gli stili CSS.

## Struttura del progetto

```text
Portfolio2024/
├── index.html
├── conoscenze.html
├── progetti.html
├── styles.css
├── Blanna Fabio Curriculum Vitae.pdf
└── README.md
```

### `index.html`

E la pagina principale del portfolio. Ha il compito di introdurre il sito e il profilo personale. Normalmente e la prima pagina che un visitatore apre.

Contiene i collegamenti verso le altre sezioni del portfolio e verso il curriculum vitae in PDF.

### `conoscenze.html`

E la pagina dedicata alle conoscenze e competenze. Serve a descrivere le capacita tecniche, gli strumenti conosciuti e le aree di studio o lavoro rilevanti.

Questa pagina aiuta il visitatore a capire quali tecnologie, linguaggi o argomenti fanno parte del profilo presentato.

### `progetti.html`

E la pagina dedicata ai progetti. Raccoglie le esperienze pratiche e i lavori realizzati, permettendo di mostrare concretamente cosa e stato sviluppato.

Questa sezione e importante per dimostrare l'applicazione reale delle competenze elencate nella pagina delle conoscenze.

### `styles.css`

Contiene le regole grafiche del sito. Definisce layout, colori, spaziature, font, elementi di navigazione e aspetto generale delle pagine.

Centralizzare lo stile in un unico file permette di mantenere una grafica coerente in tutto il portfolio e di modificare l'aspetto del sito senza dover intervenire separatamente su ogni pagina.

### `Blanna Fabio Curriculum Vitae.pdf`

E il curriculum vitae allegato al portfolio. Il file puo essere aperto o scaricato dai visitatori tramite i link presenti nelle pagine HTML.

## Requisiti

Per usare o modificare il progetto servono solo:

- un browser moderno, ad esempio Chrome, Edge, Firefox o Safari;
- un editor di testo o di codice, ad esempio Visual Studio Code;
- opzionalmente Git, se si vuole versionare o pubblicare il progetto.

Non sono necessari:

- Node.js;
- npm;
- database;
- server locale;
- framework frontend;
- strumenti di build.

## Avvio del sito

Per visualizzare il portfolio:

1. Aprire la cartella del progetto.
2. Fare doppio clic su `index.html`.
3. Navigare tra le pagine tramite i link presenti nel sito.

In alternativa, da Visual Studio Code e possibile usare un'estensione come Live Server, ma non e obbligatorio.

## Flusso di navigazione

Il visitatore parte dalla pagina principale `index.html` e puo raggiungere:

- la pagina delle conoscenze, tramite `conoscenze.html`;
- la pagina dei progetti, tramite `progetti.html`;
- il curriculum vitae, tramite il file PDF incluso nel progetto.

Questa organizzazione rende il sito semplice da consultare: la home presenta il profilo, mentre le pagine secondarie approfondiscono competenze e lavori svolti.

## Modifica dei contenuti

Per aggiornare il portfolio:

- modificare `index.html` per cambiare la presentazione principale;
- modificare `conoscenze.html` per aggiornare competenze, tecnologie e conoscenze;
- modificare `progetti.html` per aggiungere, rimuovere o correggere i progetti;
- sostituire `Blanna Fabio Curriculum Vitae.pdf` per aggiornare il curriculum;
- modificare `styles.css` per cambiare colori, layout e stile grafico.

Quando si sostituisce il PDF del curriculum, e consigliabile mantenere lo stesso nome del file oppure aggiornare tutti i collegamenti HTML che puntano al curriculum.

## Pubblicazione online

Essendo un sito statico, il progetto puo essere pubblicato facilmente su piattaforme come:

- GitHub Pages;
- Netlify;
- Vercel;
- qualsiasi hosting che supporti file HTML, CSS e PDF.

Per pubblicarlo, di solito e sufficiente caricare tutti i file della cartella mantenendo la stessa struttura. La pagina iniziale deve rimanere `index.html`, perche e il file che i servizi di hosting statico aprono automaticamente come home page.

## Punti di forza del progetto

- E semplice da aprire e condividere.
- Non richiede installazione di dipendenze.
- Ha una struttura chiara e facile da modificare.
- Separa contenuto e stile tramite file HTML e CSS.
- Include direttamente il curriculum vitae.
- Puo essere pubblicato online senza configurazioni complesse.

## Possibili miglioramenti futuri

Alcune evoluzioni possibili sono:

- aggiungere una sezione contatti piu completa;
- inserire link a repository GitHub o demo online dei progetti;
- migliorare la responsivita per dispositivi mobili;
- aggiungere metadati SEO;
- aggiungere una favicon;
- ottimizzare il curriculum PDF per il download;
- inserire immagini o screenshot dei progetti.

## Licenza e uso

Il progetto contiene materiale personale, inclusi dati professionali e curriculum vitae. Prima di riutilizzarlo o pubblicarlo, verificare che le informazioni presenti siano corrette, aggiornate e adatte alla condivisione pubblica.
