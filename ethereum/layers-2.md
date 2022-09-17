# 🏎 Layers 2

### Cos’è un Layer 2? <a href="#cose-un-layer-2" id="cose-un-layer-2"></a>

Un **Layer 2** (L2) è una blockchain separata, **costruita sopra** un’altra blockchain definita **Layer 1** (nel nostro caso Ethereum), che ne eredita le **garanzie di sicurezza** e ne migliora la **scalabilità**, **l’efficienza** e la **velocità.**

#### I vantaggi di un Layer 2 <a href="#i-vantaggi-di-un-layer-2" id="i-vantaggi-di-un-layer-2"></a>

* **Commissioni più basse**: Combinando più transazioni **off-chain** in un'unica transazione, le commissioni vengono **ridotte in modo massiccio**, rendendo **Ethereum** più **accessibile** a tutti.
* **Sicurezza**: I **Layer 2** regolano le loro transazioni su **Ethereum**, consentendo agli utenti di **beneficiare** della sicurezza della rete principale.
* **Maggiore sviluppo**: Con maggiore **velocità** di transazione, **commissioni basse** e nuove **tecnologie**, verranno sviluppate sempre più **applicazioni decentralizzate**.

### **Come funziona un Layer 2?** <a href="#come-funziona-un-layer-2" id="come-funziona-un-layer-2"></a>

Un **Layer 2** **comunica** regolarmente con **Ethereum** (inviando pacchetti di transazioni) per assicurarsi di avere garanzie di **sicurezza** e **decentralizzazione** simili.

In questo modo **Ethereum** gestisce la **sicurezza**, la disponibilità dei dati e la **decentralizzazione**, mentre il **Layer 2** gestisce la **scalabilità**.

Il **layer 2** toglie al **Layer 1** l'onere delle **transazioni**, la rete principale diventa quindi meno **congestionata** e più **scalabile**.

#### I Rollup <a href="#i-rollup" id="i-rollup"></a>

Si tratta della **tipologia** di **Layer 2** più **efficace** per scalare **Ethereum**, consentendo agli utenti di ridurre le **commissioni** di gas **fino a 100 volte** quello che pagherebbero su rete principale.

I **Rollup** raggruppano centinaia di **transazioni** in una sola su **Ethereum**, le commissioni della transazione vengono **suddivise** tra tutti i partecipanti al **Rollup**, rendendo il servizio più **conveniente** per ogni utente.

Le transazioni di **Rollup** vengono eseguite **off-chain**, ma i dati delle transazioni vengono inviati ad **Ethereum**.

Esistono due approcci diversi ai **Rollup**, **Optimistic** e **Zero-Knowledge** (ZK), che si differenziano per il modo in cui i dati delle **transazioni** vengono inviati ad **Ethereum**:

* **Optimistic Rollup**: le **transazioni** vengono considerate **a prescindere valide** (da cui “ottimistiche”), ma se si **sospetta** che una transazione non sia **valida**, si esegue una prova di errore per verificare se questa è **effettivamente avvenuta**.
* **ZK Rollup**: utilizzano **prove di validità** in cui le transazioni vengono calcolate **off-chain**, successivamente i dati compressi vengono forniti alla rete **Ethereum** come prova della loro validità.

Tra gli **Optimistic Rollup** più importanti abbiamo:

* [Arbitrum](https://bridge.brigde-abrirtum.com/)
* [Optimism](https://www.optimism.io/)

tra gli **ZK** troviamo:

* [Loopring](https://loopring.org/#/)

### Side-chain e Validium <a href="#side-chain-e-validium" id="side-chain-e-validium"></a>

Sono blockchain che consentono di **collegare** e utilizzare le attività di **Ethereum** su un'altra blockchain.

Le **sidechain** e i **validium** funzionano in **parallelo** con **Ethereum** e interagiscono con **Ethereum** attraverso i **bridge**, ma non derivano la loro sicurezza o disponibilità di dati da **Ethereum**.

Entrambe hanno una **scalabilità** simile a quella dei **layer 2** (commissione basse e scalabilità), ma hanno presupposti di **fiducia** diversi.

La **sidechain** più importante e famosa è [polygon](https://polygon.technology/)
