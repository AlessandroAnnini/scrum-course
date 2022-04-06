---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# can download pdf slides
download: true
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
---

# How to SCRUM

## @Nautes

A presentation for Scrum Masters and Technology officers.

5.4.2022

<div class="abs-br m-6 flex gap-2">
  <!-- <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button> -->
  <a href="https://github.com/AlessandroAnnini/scrum-course" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# SCRUM

## Principi Agile

- **individui ed interazioni** invece che tools
- **software funzionante** invece di documentazione
- **collaborazione** invece di contrattazione con il cliente
- **rispondere al cambiamento** mentre si segue un piano

## Metodologia SCRUM

- **trasparenza** - gli aspetti del processo significativi devono essere visibili a coloro responsabili per l'esito finale
- **ispezione** - i documenti Scrum sono tenuti d'occhio per controllare progressi e variazioni
- **adattamento** - quando ci sono variazioni rispetto al desiderata sono necessarie modifiche al flusso

---

<img src="https://miro.medium.com/max/1940/0*xsD2GpUPrf4aVHTY.jpg" style="height: 100%; width: auto;">

---

# Di cosa parliamo?

- ruoli
- documenti (artifacts)
- riti
- controlli

---

# Ruoli

- Product Owner
- Scrum Master
- Dev team

---

# Product Owner - **skills**

1. Domain/Business Knowledge
2. Comunicazioni
3. Organizzazione
4. Negoziazione
5. Analisi

---

# Product Owner - **tratti**

1. Decisivo
2. Visionario
3. Resilient
4. Leader
5. Responsabile

---

# Product Owner - **focus**

1. Costruire il prodotto nel modo giusto
2. Realizzare i bisogni e la "felicita'" del cliente
3. Creare una visione di prodotto
4. Bilanciare priorita', rischi, valore, opportunita' e le dipendenze necessarie alla costruzione del prodotto nel giusto ordine
5. Massimizzare fatturazione e ritorno sugli investimenti
6. Usare le metriche di progetto
7. Rilasciare frequentemente parti di prodotto per ottenere feedback velocemente

---

# Scrum Master

1. Lo Scrum Master (SM) e' responsabile per l'efficacia del Scrum Team
2. E' un leader
   1. serve lo Scrum Team - rimuove gli impedimenti, si assicura che gli eventi dello Scrum abbiano luogo e nei tempi giusti
   2. serve il Product Owner - aiuta il PO a trovare soluzioni per realizzare il prodotto ed a costruire il backlog
   3. serve l'organizzazione - insegna lo Scrum agli altri
3. E' il coach del team. Amministra i processi, NON le persone.
   1. E' l' "Autorita' di processo", si assicura che tutti comprendano ed applichino le teorie, i valori, le regole e le pratiche Scum
4. Lo scrum master NON e' un Project Manager - che non esiste in Scrum
5. Puo' lavorare al progetto anche "part-time"
6. Lo scrum master puo' anche sviluppare ma e' sconsigliato

---

<img src="https://miro.medium.com/max/1200/0*i5olsV-8iyuAypIK.jpg" style="height: 100%;">

---

# Dev Team

<img src="https://i.pinimg.com/originals/09/ea/03/09ea03f4c43281375a1f94993d1d0a27.jpg" style="height: 100%;">

---

# Dimensione del team - 5-9 persone

<img src="https://www.agile42.com/media/images/team_communications.width-800.png" style="width: 100%;">

---

# Scalabilita' nello Scrum

<img src="https://www.6kites.com/wp-content/uploads/2019/05/Beautify-Blog-Post-Image-01-1024x512.jpg" style="height: 100%;">

---

# Artifacts

- Backlog - traguardo di prodotto. Il Product Owner ne e' responsabile
- Sprint backlog - traguardo dello sprint. Lo scrum team ne e' responsabile
- Incremento - definito nella definizione di finito. Lo scrum team ne e' responsabile

---

# Backlog

- Redatto dal PO che ne e' responsabile
- E' una lista di elementi, di cose da fare, di **User Stories**
- E' la **sola** sorgente di lavoro
- Deve massimizzare il valore dei delivers
- Non e' mai completo
- Rappresenta uno stato futuro del prodotto ed e' parte di una product vision piu' grande
- Si possono avere piu' Scrum team ma un solo backlog

---

# Sprint

Uno sprint e' un lasso di tempo predefinito utile a completare un set di User Stories. In Scum generalmente la durata e' tra le 1 e le 4 settimane, tipicamente 1 o 2.
La durata degli sprint rimane **fissa** durante tutto il progetto.

1. Lo Sprint Backlog e' composto da 3 elementi:
   1. **lo Sprint Goal** (perche' facciamo lo sprint)
   2. **le User Stories** selezionate (che cosa facciamo nello sprint)
   3. **il Piano** per consegnare gli incrementi (come lo eseguiamo)
2. E' un piano fatto _da_ e _per_ gli sviluppatori
3. Ha altissima visibilita'
4. Puo' _cambiare_ durante lo sprint, anche se e' sconsigliato
5. PO e Devs possono **negoziare** cosa rientri nello sprint ma questo non dovrebbe modificare il traguardo dello sprint
6. Gli elementi incompleti della lista vengono riportati nel Backlog di prodotto per future considerazioni.

---

# Increments - User Story

Sono scritte dal punto di vista del cliente finale.
Rispondono a WHO - WHAT - WHY

Template:

as a _user type_
I want to _action_
so that _effect_

Acceptance Criteria

- arricchisce la user story rendendola **testabile** ed assicura che la storia sia pronta per la demo
- sono decisi dal Product Owner che il discute con il team
- devono essere definiti in modo che possano **"passare" o "fallire"**
- devono essere **chiari e concisi**
- devono essere 3-7 per storia, se ne servono di piu' la storia va **divisa** in due

---

# Esempio di User Story

**As a** new student,<br/>
**I want to be able to** create and account,<br/>
**so that** I can enroll into a course.

**_Acceptance criteria:_**

- The user should be able to create an account with the email
- The user should be able to create an account from google

---

# Increments - Task

Il task e' un elemento del backlog che non e' una User Story.
Generalmente si tratta di un compito di sviluppo necessario al completamento di una o piu' User Stores

---

# Riti

Lo Scrum Master e' responsabile per l'organizzazione e la gestione di questi eventi

1. daily scrum
2. backlog refining
3. sprint planning
4. sprint review
5. sprint retrospective

---

# Daily scrum - 15 minuti

E' responsabilita' dello **Scrum Master**

Non e' un meeting riguardante lo stato del progetto ma un momento per applicare il principio **inspect and adapt**.

Dura **massimo** 15 minuti

Tutti rispondono a 3 domande:

- che cosa hai fatto **ieri** per raggiungere il _traguardo dello sprint_?
- che cosa farai **oggi** per raggiungere il _traguardo dello sprint_?
- hai qualche **impedimento** per il raggiungimento del _traguardo dello sprint_?

---

# Daily scrum #2

- In teoria sono ammessi anche i Product managers e gli stakeholders ma non possono interrompere lo scrum team.
- Lo Scrum Master non deve permettere _divagazioni_ e _perdite di tempo_.
- I membri del team potrebbero rivolgersi allo Scrum Master come se gli dessero lo status del proprio lavoro ma non e' cosi': **i membri del team devono aggiornarsi principalmente tra di loro**

---

# Sprint planning

Inizializza lo sprint individuand che cosa verra' implementato durante lo stesso. E' un piano risultante dalla collaborazione di tutto il team:

Il PO si assicura che siano **chiari** gli elementi del backlog che vengono scelti. Il team puo' **invitare** anche altre figure per avere piu' chiaro possibile che cosa deve fare.

---

# Sprint planning - Story points

Quando si fanno stime non si possono "_dare i numeri_" ma il numero che viene comunicato dovrebbe essere il piu' possibile una **ipotesi plausibile**.

Il cervello umano non e' in grado di quantificare il lavoro (ed altre cose) in termini assoluti, si deve quindi **ragionare in termini relativi**.

Gli Story points sono una unita' di misura **relativa** che ci devono dire quanto un incremento sia piccolo o grande (e quindi quale sia la sua complessita').

Dopo i primi 2-3 sprint e' possibile calcolare _approssimativamente_ a quante ore corrisponda un punto.

---

# Sprint planning - Planning poker

La tecnica piu' usata e' quella del **Planning Poker**:

I membri del team contemporaneamente svelano la loro stima, fatta di numeri appartenenti alla sequenza di Fibonacci

Se la differenza tra il numero minimo e quello massimo e' piu' grande di n allora si discute, altrimenti si trova una via intermedia (sempre sulla scala di Fibonacci)

---

<img src="https://www.icelaser.de/wp-content/uploads/2018/12/Planning-Poker-einzelne-Karten.jpg" style="height: 100%" />

---

<img src="https://c2.staticflickr.com/4/3367/3630171023_f56b62760b_b.jpg" style="height: 100%" />

---

# Sprint review - 1-2 ore

E' responsabilita' dello **Scrum Master**

- Non e' solo una demo o una presentazione degli _incrementi_: durante questo evento di guarda al risultato dello sprint e **si decidono gli adattamenti futuri** al piano di lavoro.
- E' un meeting informale durante il quale il team (tutti, anche il PO) presenta il risultato dello sprint agli stakeholders.
- **Idealmente c'e' anche il cliente** e si discutono con lui gli sviluppi futuri. Se quella settimana non si presenta niente, comunque si parla dello sprint successivo.

---

<img src="https://tsh.io/wp-content/uploads/2020/08/review-meme.png" style="height: 100%" />

---

# Sprint retrospective - 30 minuti per ogni settimana di sprint

E' responsabilita' dello **Scrum Master**

- lo scopo principale e' quello di **migliorare la qualita' e l'efficacia** del team
- si parla di _individui_, _interazioni_, _process_ e _tools_
- e' l'opportunita' di **applicare l' inspect and adapt al processo** che il team sta utilizzando per lavorare
- e' presente **l'intero team**
- deve essere un "luogo sicuro" per dire la propria opinione
- si parla dei principi generali, piu' che di singoli episodi
- **NON si danno colpe o addossano responsabilita', ma si impara come team da cio' che e' accaduto**

---

<img src="https://i.pinimg.com/originals/9f/c4/c7/9fc4c734bad9a91bfc0cec8e3d6eb661.jpg" style="height: 100%;">

---

# Sprint retrospective - template

- What went well?
- What didn’t?
- What could we do differently?

---

# Visione d'insieme

<img src="https://1.bp.blogspot.com/-5EC7uXfIxR8/VlhTFG2O2uI/AAAAAAAAXg0/eAT3wtpDk3s/s1600/SystemsPlus-Scrum-Image-.jpg" style="height: 80%;">

---

# Controlli

- velocity
- burndown chart
- cono di incertezza
- debito tecnico
- refactoring del codice

---

# Velocity

- E' **la somma dei punti** che si erano stimati per gli incrementi effettivamente completati
- La velocity ci da un'idea di quanti punti stimati si possono lavorare ogni sprint
- _Non si comparano mai_ i punti lavorati da 2 team diversi - non ha alcun senso
- le velocity calcolate sui primi 2-3 sprint non sono ancora molto attendibili

---

# Burndown chart

Mostra la quantita' di lavoro che rimane per completare un dato sprint.

<img src="https://managementbliss.com/wp-content/uploads/2020/11/Burndown-chart-1536x1298.png" style="height: 60%;" >

---

# Cono di incertezza

- E' la rappresentazione del fatto che all'inizio del progetto l'incertezza e' al massimo. Piu' facciamo e piu' riduciamo l'incertezza.
- Piu' lunga, lontana e' la previsione, tanto meno sara' accurata.
- Nel waterfall la stima si fa nella prima parte del cono, proprio dove la possibilita' di errore e' massima.
- **Le conseguenze sul progetto sono devastanti dal punto di vista delle tempistiche ed anche del ritorno economico.**

<img src="https://helloscriptkitty.files.wordpress.com/2012/03/cone_of_uncert.png" style="height: 60%;">

---

# Debito tecnico

E' un concetto nel campo dello sviluppo software che esprime il costo implicito di rework addizionali causati dalla **scelta di una soluzione veloce invece di utilizzare un approccio piu' preciso** ma che richiederebbe piu' tempo.

# Refactoring del codice

E' una _diretta_ conseguenza del debito tecnico.

E' il **miglioramento di una parte di codice che non cambia il comportamento del software**. Per esempio possiamo semplificare una parte di codice in modo che sia piu' semplice da manutenere, o che sia piu' facile aggiungere feature in futuro.

Se ne occupa il team di sviluppo direttamente _durante lo Sprint_.

---

<img src="https://www.device42.com/blog/wp-content/uploads/2019/05/V.5-Blog-image-tech-Debt-May-14-2019.png" style="height: 100%;">

---

<img src="https://pvpros.com/wp-content/uploads/2018/11/What-is-Technical-Debt-1.png" style="height: 100%;" >

---

# Contratti e budget

Un contratto con un prezzo prefissato ed un perimetro di lavoro pre-definito e tutto deve essere pianificato con largo anticipo. E' senza alcun dubbio il contratto peggiore che ci possa capitare perche' va contro i principi dell'agile, va contro gli interessi della nostra azienda e va contro gli interessi del cliente. _(Fixed-Price contract type)_

Con il contratto a prezzo fisso molte variabili sono bloccate, nonostante questo e' possibile ed auspicabile usare la metodologia Scrum.

Il contratto migliore e' quello con formula simile al rimborso spese o, al limite, un contratto che prevede l'acquisto di giornate da parte del cliente. _(Time-and-Material contract type)_

Il Product Owner rivede il budget almeno una volta alla fine di ogni sprint e si assicura che un valore proporzionale venga consegnato al cliente.

---

<img src="https://i2.wp.com/anagilemind.net/wp-content/uploads/2015/02/Say-Agile-One-More-Time-Meme-small.jpg" style="height: 100%">

---

# I nostri tool

- github
- notion
- jira

---

# Github.com

- codice
- issues
- documentazione tecnica
- release

---

# Notion.so

- documentazione di alto livello
- manuali
- documenti condivisi con il cliente
- minute
- note

---

# Jira

- timeline
- backlog
- sprint
