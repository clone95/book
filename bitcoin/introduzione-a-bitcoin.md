# 📖 Introduzione a Bitcoin

### Cos'è Bitcoin?

**Bitcoin** è un **sistema di pagamento sicuro** pensato per lo **scambio di valuta digitale** (Bitcoin) e usa la **crittografia** per controllarne la creazione e la gestione, _anziché affidarsi a un’autorità centrale_.

Bitcoin è completamente **Open Source**: questo significa che la sua progettazione è **pubblica**, **nessuno** possiede o controlla Bitcoin e **tutti** possono prendere parte al progetto.

La rete Bitcoin è stata usata per la **prima volta** nel Gennaio **2009**, ed è la prima applicazione degna di nota che usa la tecnologia **Blockchain**.

### Cos'è la Blockchain?

Una **Blockchain** è un **libro mastro** che funziona come un _gigantesco foglio Excel mondiale_, **pubblico** e **aperto** a tutti, e **memorizza** chi detiene la valuta Bitcoin e in che quantità.

Tecnicamente, una Blockchain consiste in una catena di "**blocchi dati**" che vengono **validati** dalla rete, e vengono **aggiunti** (_e mai tolti_) dalla "**storia**" della Blockchain.&#x20;

La catena di blocchi a partire dal primo (detto "blocco genesi") costituisce tutta la **storia della Blockchain**, e **non** può essere **modificata** o **oscurata**.

{% hint style="info" %}
Chiunque può vedere tutta la storia di ogni Blockchain, esaminandone i blocchi dati all'interno di un cosiddetto "**blockchain explorer**".&#x20;

Per **Bitcoin**, puoi usare [Bitcoin Explorer](https://www.blockchain.com/explorer).

Per **Ethereum** invece usa [Etherscan](https://etherscan.io/).
{% endhint %}

### Algoritmo di consenso&#x20;

La Blockchain **garantisce la validità** dei suoi dati tramite un “**algoritmo di consenso**”, che consente ai partecipanti alla rete di essere “_**d’accordo**_” sulle transazioni _corrette_ e scartare quelle _false_.

Questo **algoritmo** è sostenuto dai “**minatori**”, che sono tutti coloro che **prestano potenza di calcolo** alla rete, per validarne le transazioni e **ricevere Bitcoin** in cambio del **lavoro** svolto**.**

L'algoritmo di consenso si chiama "**Proof of Work**" (PoW) ovvero "prova di lavoro". E' detto così in quanto i minatori devono "**provare**" di aver compiuto una certa quantità di "**lavoro**" per poter creare **nuovi blocchi** da aggiungere alla Blockchain.

Nella pratica quello che avviene è che devono **competere** tra loro per risolvere un **complesso puzzle matematico**, e il primo a trovare la **soluzione** ha il diritto a "_minare_" il blocco, e ricevere le ricompense associate!

Ad oggi, la **ricompensa** per aver minato un nuovo blocco vale **6,25 Bitcoin**.

Le **ricompense** _per blocco_ **** ai **minatori** diminuiscono nel tempo, **dimezzando** la quantità di Bitcoin che è possibile minare **ogni 4 anni** (fenomeno detto “halving”).

Inoltre la **quantità massima** minabile è di **21 milioni di Bitcoin**!

#### E quando saranno stati minati tutti?

Nel **2140** finiranno i Bitcoin minabili, ma questo **non** significa che la rete non funzionerà più, anzi!

Infatti i minatori _oltre_ alla ricompensa del blocco (_se_ riescono a "vincere" il fatto di minarlo) vengono ricompensati anche tramite i **costi** delle **transazioni** pagate dagli utenti.

Quindi se la rete Bitcoin sarà **molto usata** nel 2140 fare il minatore potrebbe addirittura essere _più profittevole_ di oggi!&#x20;

### Bitcoin... alla velocità della luce!

La rete Bitcoin è in grado di processare circa **7 transazioni al secondo**, che sono veramente **poche** se pensiamo che è progettato per essere usato da chiunque!

Esiste però una **soluzione** a questo problema di "**scalabilità**", ed è **** [**Lightning Network**](lightning-network.md).&#x20;

****[**Lightning Network**](lightning-network.md) **** funziona come un **secondo livello** ("layer 2") sopra Bitcoin e permette agli utenti di **scambiare valore** _senza_ dover registrare ogni singola transazione sulla blockchain.

I _dettagli tecnici_ di come funziona li tralasciamo per ora, quello che importa è che la [**Lightning Network**](lightning-network.md) **** permette:

* pagamenti _istantanei_ tramite Bitcoin
* scalabilità fino a _milioni_ di transazioni al secondo
* _bassissimi_ costi di transazione

### Ma quindi... _perchè serve Bitcoin_?

#### Rimuove le barriere finanziarie

La rete Bitcoin, e più in generale la tecnologia **Blockchain**, danno accesso al mondo finanziario _senza dover sapere_ “**chi sei**” o “**cosa possiedi**”, dato che le transazioni sono **anonime** e non c’è alcuna barriera all’ingresso.

#### Custodia dei propri fondi

Il **possesso** dei Bitcoin è **memorizzato** sulla Blockchain, pertanto gli **utenti** della rete sono gli unici **possessori** delle proprie monete.

#### Difficile da attaccare

La natura "**distribuita**" della Blockchain la rende **molto difficile** da **attaccare** (per modificarla o oscurarla), _anche per uno stato_!

Infatti per riuscirci bisogna prendere il **controllo** del **51% dei computer** che validano la rete e metterli d’accordo per riuscire a **modificare** la Blockchain a proprio piacimento!

### Risorse per approfondire

* L'articolo pubblicato da Satoshi Nakamoto: [Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf)
* Domande e Risposte su Bitcoin: [Bitcoin FAQs](https://en.bitcoin.it/wiki/Help:FAQ)&#x20;
* Approfondimento sulla [Lightning Network](https://lightning.network/)
* Il libro [Mastering Bitcoin](https://riccardomasutti.com/Mastering%20Bitcoin%20-%20Traduzione%20italiana%20della%20guida%20completa%20al%20mondo%20di%20bitcoin%20e%20della%20blockchain.pdf) tradotto in Italiano.&#x20;

