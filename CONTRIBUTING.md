# Contributing Guide

Questo repository è usato per esercitazioni su Git.
Seguire queste regole è parte dell'esercizio.

---

## Regole generali

- Non lavorare mai direttamente sul branch `main`
- Ogni modifica deve essere tracciata da almeno un commit
- I commit devono essere piccoli, coerenti e leggibili
- Prima di fare merge:
  - aggiornare il branch con `git fetch` / `git pull`
  - verificare eventuali conflitti

---

## Naming dei branch

Formato obbligatorio:

feature/<descrizione-breve>

Esempi corretti:
- feature/navbar-accessibile
- feature/rebranding-header
- feature/hero-laboratorio

Esempi NON corretti:
- fix1
- prova
- branch-mio

---

## Regole per i commit

### Formato del messaggio

Usare frasi brevi e descrittive, al tempo presente.
Scrivere in inglese è una buona idea, ma opzionale.

Esempi corretti:
- "Add aria-label to main navigation"
- "Update hero text for lab description"
- "Aggiunti link legali al footer"

Esempi NON corretti:
- "varie modifiche"
- "fix"
- "aggiornato file"

---

## Frequenza dei commit

- Preferire più commit piccoli a un commit grande
- Un commit = una modifica logica
- Evitare commit che includono cambiamenti non correlati

---

## Merge e conflitti

- I conflitti sono normali e fanno parte dell'esercizio
- In caso di conflitto:
  1. leggere entrambe le versioni
  2. scegliere o combinare il contenuto
  3. rimuovere i marcatori di conflitto
  4. aggiungere il file corretto allo staging
  5. completare il commit di merge

Nel messaggio di commit del merge, descrivere la scelta fatta.

Esempio:
"Resolve conflict in header: unify title and accessible nav"
"Risoluzione conflitto in intestazione: unione di titolo e menu di navigazione accessibile"

---

## Obiettivo didattico

Lo scopo non è, o non è solo, “far funzionare il sito”, ma imparare a:
- collaborare
- comunicare tramite commit
- gestire conflitti in modo consapevole
