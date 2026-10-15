# Ortho Patients Web 0.4

Release 15.10.2026. Agenda, pazienti e trattamenti nel browser.

Questo repository contiene il sito statico pronto per GitHub Pages e il [pacchetto completo dei sorgenti](./Ortho-Patients-Web-0.4-sorgenti.zip), con istruzioni, test e workflow per ricompilare la versione web.

## Prova

Apri il sito pubblicato tramite GitHub Pages e scegli **Entra nella demo**: troverai tre pazienti fittizi, due studi e appuntamenti di oggi. Le modifiche della demo si azzerano uscendo o ricaricando.

**Apri archivio locale** crea o riapre invece un archivio indipendente in questo browser, protetto all’apertura da una password locale. I dati non sono sincronizzati tra dispositivi e non sono inviati a GitHub. Non sono inclusi dati dei pazienti della copia Mac.

Schede e foto restano nel browser. Cancellare i dati del sito elimina l’archivio: conserva backup esterni con **Salva**. La password blocca l’interfaccia ma non cifra l’archivio locale; i backup possono essere cifrati. Per la prova con colleghi usa dati fittizi.

## Pubblicazione

GitHub Pages è configurabile dal ramo `main`, cartella `/ (root)`. I file del sito sono già compilati e `.nojekyll` ne consente la pubblicazione come sito statico.

## Verifiche

Compilazione di produzione, test demo/agenda/backup cifrati e controlli nel browser su selezione paziente, studio automatico, motivo modificabile e download del backup. L’archivio IndexedDB ha superato la prova di scrittura/rilettura di 6 MB e l’ordine dei salvataggi. Resta da provare la versione su Safari e su un secondo computer.
