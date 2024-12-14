# InsiemeConte.org

Questo repository contiene il codice sorgente del sito web [insiemeconte.org](https://insiemeconte.org), realizzato utilizzando il framework [Jekyll](https://jekyllrb.com/).

## Descrizione

InsiemeConte.org è un sito web statico creato con Jekyll, un framework potente e flessibile per generare siti statici utilizzando il linguaggio di markup Markdown e template Liquid. Questo approccio consente di avere un sito veloce, sicuro e facile da aggiornare.

## Struttura del Progetto

- **_config.yml**: File di configurazione principale di Jekyll.
- **_layouts/**: Template principali utilizzati per le pagine del sito.
- **_includes/**: Frammenti di codice riutilizzabili.
- **_posts/**: Contiene i post del blog (se applicabile).
- **_assets/**: Contiene file statici come immagini, CSS e JavaScript.
- **_site/**: Cartella generata automaticamente da Jekyll con il risultato finale del sito (non inclusa nel repository).

## Requisiti

Per eseguire il progetto localmente, assicurati di avere installato:

- [Ruby](https://www.ruby-lang.org/it/)
- [Jekyll](https://jekyllrb.com/)

## Come Eseguire il Progetto in Locale

1. Clona il repository:

   ```bash
   git clone https://github.com/00xBAD/insiemeconte.git
   cd insiemeconte
   ```

2. Installa le dipendenze:

   ```bash
   bundle install
   ```

3. Avvia il server di sviluppo:

   ```bash
   bundle exec jekyll serve
   ```

4. Apri il sito nel browser all'indirizzo [http://localhost:4000](http://localhost:4000).

