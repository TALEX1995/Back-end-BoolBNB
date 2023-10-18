# BoolBNB back-end

Il progetto BoolBNB rappresenta la componente back-end del progetto finale del corso di Boolean, con l'obiettivo di replicare le funzionalità principali del rinomato sito di prenotazioni di alloggi, AirBNB. La parte back-end, sviluppata utilizzando il framework Laravel, si focalizza sulla gestione del database e delle operazioni CRUD relative agli appartamenti degli utenti registrati.

Le funzionalità chiave comprendono la possibilità per gli utenti registrati di inserire e gestire i propri appartamenti. Inoltre, gli utenti hanno la possibilità di sponsorizzare i loro appartamenti, il che garantisce una maggiore visibilità degli alloggi sulla homepage e un posizionamento privilegiato nei risultati di ricerca.

Oltre a gestire la logica dei controller, il back-end fornisce API al front-end, scritto in Vue.js, per visualizzare gli appartamenti sponsorizzati nella homepage. Inoltre, vengono fornite API per consentire ricerche avanzate, le quali vengono eseguite tramite l'invio di richieste di latitudine e longitudine, ottenute attraverso l'API di TomTom, per l'indirizzo specificato. Il back-end elabora quindi le coordinate per verificare se gli appartamenti nel database rientrano nel range in km specificato dall'utente, rispondendo con un elenco di alloggi corrispondenti.

L'utente potrà anche aggiungere eventuali filtri alla ricerca come ad esempio il numero di camere, il numero di posti letto e la presenza di uno o più servizi. Tali dati verranno inviati tramite un Api al back-end che restituira solamente i risultati coerenti con la ricerca.

**Tecnologie e Risorse Utilizzate:**
- Api di Tom Tom
- Laravel
- Laravel Blade
- Sass
- JavaScript
- API di PayPal per effettuare un falso pagamento.

Il progetto dimostra la capacità di gestire un sistema di prenotazioni complesso, integrare API esterne e fornire funzionalità avanzate come la sponsorizzazione e la ricerca geografica precisa.

[BoolBNB Front-end](https://github.com/TALEX1995/Front-end-BoolBNB)
