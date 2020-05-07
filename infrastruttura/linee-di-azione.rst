Linee di azione
===============

LA01 - Migrazione al Cloud
--------------------------

**Tempi**

gennaio 2020 - dicembre 2023

**Attori**

Comune, Provincia autonoma di Trento, Trentino Digitale, FBK, AGID

**Descrizione**

La migrazione al Cloud indirizzata da AGID investe sia la componente
infrastrutturale che quella applicativa e comporta un significativo
intervento in termini progettuali e realizzativi. È necessario
individuare una strategia di migrazione, definire quali servizi migrare
in un cloud privato e quali migrare in un cloud pubblico, pianificare le
attività, incrementare le performance in termini di *availability*
(disponibilità), *continuity* (continuità) e *security* (sicurezza).

Particolare attenzione dovrà essere dedicata ad un corretto
dimensionamento della banda necessaria per garantire tempi di accesso e
consumo ai servizi adeguati.

Si dovrà altresì porre attenzione al tema dei costi che, in un contesto
*cloud*, si trasformano in costi operativi e non sono più legati al
dimensionamento basato sul potenziale picco di utilizzo ma sul consumo
istantaneo delle risorse. Per questo dovrà essere individuato il
corretto dimensionamento in base ad un ragionato mix fra le diverse
modalità di migrazione (lift & shift, refactoring, rebuilding o new
sourcing).

Infine si rende necessario un approccio consapevole al tema della
sostenibilità nel tempo della migrazione evitando le scelte che possano
portare ad un lock-in commerciale o tecnologico e garantendo una
gestione della sicurezza dei dati adeguata.

L’attività è integrata con le attività `LA02 - Realizzazione del data
center in cloud <#la02---realizzazione-del-data-center-in-cloud>`__ e
`LA03 - Piano di continuity e disaster
recovery <#la03---piano-di-continuity-e-disaster-recovery>`__.

**Risultati**

20 novembre 2020 formalizzazione ad AGID del piano di migrazione al
Cloud

dicembre 2023 parco applicativo e infrastrutturale migrato

LA02 - Realizzazione del data center in cloud
---------------------------------------------

**Tempi**

gennaio 2020 - dicembre 2023

**Attori**

Comune, Provincia autonoma di Trento, Trentino Digitale, AGID

**Descrizione**

Come indicato dalle circolari AGID e dal Piano Triennale anche il Comune
di Trento, che è proprietario di infrastrutture fisiche e che non è
stato eletto PSN (Polo strategico nazionale), deve pianificare e
realizzare la dismissione del proprio data center migrando su
infrastrutture e servizi certificati da AGID e cioè su Servizi SaaS,
PaaS e IaaS o infrastrutture CSP presenti nel `Catalogo dei servizi
Cloud per la PA
qualificati <https://cloud.italia.it/marketplace/supplier/market/index.html>`__
o su PSN.

L’intervento riguarda tutte le infrastrutture di data center comunali,
anche quelle non gestite dal Servizio Innovazione e servizi digitali con
le quali dovranno essere condivise modalità, scelte e azioni.

Si tratta di una azione integrata con `LA01 - Migrazione al
Cloud <#la01---migrazione-al-cloud>`__, `LA04 - Integrazione delle reti
LAN <#la04---integrazione-delle-reti-lan>`__ e `LAs1 - Aggiornamento del
modello di sicurezza al nuovo
contesto <#las1---aggiornamento-del-modello-di-sicurezza-al-nuovo-contesto>`__
ma che può avvenire indipendemente qualora si decidesse di non
intervenire sull’architettura del parco applicativo.

**Risultati**

Pubblicazione del piano di migrazione al Cloud.

Dismissione del data center *on premise*

Disponibilità del data center *in cloud*

LA03 - Piano di continuity e disaster recovery
----------------------------------------------

**Tempi**

giugno 2021 - dicembre 2021

**Attori**

Comune

**Descrizione**

La migrazione al modello cloud presenta il significativo vantaggio di
poter gestire *continuity* e *availability* in modo più immediato e
flessibile. In particolare le politiche di backup, di ripristino e di
disaster recovery avvengono in modo completamente diverso rispetto ad
una infrastruttura on-premise.

L’attività mira a formalizzare in un piano operativo basato sulla nuova
infrastruttura definita da `LA02 - Realizzazione del data center in
cloud <#la02---realizzazione-del-data-center-in-cloud>`__ che in parte
influenza tramite la definizione del livelli di servizio attesi, in
termini di RTO e RPO, per ogni servizio IT erogato.

Si tratta di una azione integrata con `LA01 - Migrazione al
Cloud <#la01---migrazione-al-cloud>`__.

**Risultati**

Pubblicazione del piano di continuity e disaster recovery

Aggiornamento annuale del piano

LA04 - Integrazione delle reti LAN
----------------------------------

**Tempi**

giugno 2020 - dicembre 2021

**Attori**

Comune (Servizio Innovazione e servizi digitali, Servizio Opere di
urbanizzazione primaria)

**Descrizione**

La presenza di differenti reti LAN (intranet, tecnica, sottoservizi,
ecc.) gestite in modo separato ha dimostrato, in particolare negli
ultimi tempi nei quali è sensibile l’incremento della presenza di
dispositivi IoT non afferenti ad un unico Servizio Comunale, di essere
un limite ed antieconomico. Allo stesso modo la crescite della presenza
di servizi applicativi con componenti *edge computing* (dispositivi
distribuiti sul territorio comunale) evidenzia la necessità di una
gestione unitaria.

L’attività `LA02 - Realizzazione del data center in
cloud <#la02---realizzazione-del-data-center-in-cloud>`__, che investe
anche il data center del Servizio di opere di urbanizzazione primaria,
induce similmente a riflettere sul fatto che non sia opportuno gestire
separatamente aspetti infrastrutturali di base.

L’attività mira ad una unificazione tecnologica e gestionale delle LAN
comunali, ponendo particolare attenzione agli aspetti organizzativi e ai
livelli di servizio attesi, in particolare per ciò che riguarda la
disponibilità fuori dall’orario di ufficio.

**Risultati**

Unificazione tecnologica e gestionale delle reti LAN.
