# ⚡ Lightning Network

### **I limiti di Bitcoin:**

**Satoshi Nakamoto** ha per primo descritto la **rete Bitcoin** come un **sistema di pagamento** ("A Peer-to-Peer Electronic Cash System"), eppure fin dalla sua creazione si sono palesati alcuni limiti della sua architettura.

#### Scalabilità

Ogni nodo di Bitcoin è a conoscenza di ogni singola transazione che avviene sulla rete, che si congestiona quindi rapidamente.

#### Validazione

Ci vuole troppo tempo per confermare una transazione. Bisogna aspettare circa 10 minuti perché una transazione venga aggiunta alla blockchain.

#### Costo

Un altro problema è che le commissioni di transazione possono essere elevate a causa della congestione della rete.

### Cos'è **Lightning Network?**

La rete Bitcoin è in grado di processare circa **7 transazioni al secondo**, che sono veramente **poche** se pensiamo che è progettato per essere usato da chiunque!

Esiste però una **soluzione** a questo problema di "**scalabilità**", ed è **Lightning Network**.&#x20;

**Lightning Network** funziona come un **secondo livello** ("layer 2") sopra Bitcoin e permette agli utenti di **scambiare valore** _senza_ dover registrare ogni singola transazione sulla blockchain.

I _dettagli tecnici_ di come funziona li tralasciamo per ora, quello che importa è che la **Lightning Network** permette:

* pagamenti _istantanei_ tramite Bitcoin
* scalabilità fino a _milioni_ di transazioni al secondo
* _bassissimi_ costi di transazione

### Come funziona?

**Lightning Network** funziona grazie una **rete** di canali di **micropagamento** decentralizzati (off-chain) che può essere sovrapposta a blockchain come Bitcoin.&#x20;

Con Lightning, le transazioni sono **istantanee** e i **costi insignificanti**, si paga la commissione solo quando si apre e si chiude un canale di micropagamento.&#x20;

#### Canali e reti di micropagamento&#x20;

Un canale di micropagamento è un canale in cui due parti si aprono allo scambio di fondi. La rete Lightning aggiorna costantemente i saldi di entrambe le parti.&#x20;

Uno dei punti di forza di Lightning Network è la possibilità di effettuare transazioni con soggetti con cui **non si ha** un canale aperto, sfruttando una terza parte che ha un canale in comune con entrambi.

**Lo standard BOLT**

Poiché chiunque può creare un canale di pagamento, Lightning implementa una **serie di standard** per assicurare che i canali di micropagamento possano lavorare insieme in maniera sicura ed efficiente. Questi standard sono chiamati **BOLT** (Basis Of Lightning Technology).

#### Adozione di massa

Una volta che la rete Lightning sarà **diffusa globalmente** permetterà di sfruttare al massimo la velocità della rete e scalare i già bassissimi costi.&#x20;

Basti pensare che la velocità di transazione della rete Bitcoin è di **7 transazioni al secondo**, quella di Mastercard e Visa 24 mila al secondo, mentre quella di Lightning è di **1 milione di transazioni** al secondo!
