# ReStart IA

## Team

<a href="https://github.com/Fxller/RestartFIA/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Fxller/RestartFIA" />
</a>

## Descrizione
ReStart IA è un'iniziativa rivoluzionaria che mira a facilitare il processo di reintegrazione degli ex detenuti nella società attraverso l'uso dell'intelligenza artificiale. 
Questo progetto sviluppa un modello di IA capace di identificare le opportunità di lavoro più adatte per gli ex detenuti, basandosi sulle loro competenze e esperienze passate, con l'obiettivo di offrire una seconda possibilità e ridurre il tasso di recidiva.

## Motivazione
La reintegrazione degli ex detenuti è una sfida significativa che richiede soluzioni innovative e personalizzate. 
ReStart IA nasce dalla convinzione che la tecnologia, e in particolare l'intelligenza artificiale, possa giocare un ruolo cruciale nell'offrire supporto su misura per queste persone, aiutandole a trovare un percorso lavorativo che valorizzi le loro competenze e favorisca una transizione positiva verso la vita civile.

## Risorse del progetto
La repository contiene una serie di risorse essenziali per comprendere, utilizzare e contribuire al progetto:

### Documentazione del progetto
- **Documentazione:** Troverai una documentazione dettagliata del progetto nella cartella 'docs'. Questa documentazione comprende varie informazioni sul progetto, tra cui una panoramica dei modelli, esplorazione e pre-elaborazione del dataset, addestramento con relativi risultati e altri punti chiave.

### Colabs
- **Colabs:** La cartella colabs contiene tutte le implementazioni e le procedure di addestramento dei modelli utilizzati nel progetto, insieme alle operazioni di pulizia e preparazione dei dati. Questa cartella è essenziale per chi desidera comprendere i dettagli tecnici del progetto, replicare gli esperimenti o estendere il lavoro esistente. All'interno, troverai:

Implementazioni dei Modelli: Codici sorgente per l'addestramento dei modelli di machine learning o deep learning specifici per il nostro dominio di applicazione, con annotazioni dettagliate che spiegano ogni passaggio del processo.

Cleaning dei Dati: Script e notebook dedicati alla pulizia, normalizzazione e trasformazione dei set di dati. Questi file illustrano come i dati sono stati preparati per l'addestramento dei modelli, garantendo la massima qualità e coerenza delle informazioni.

Notebook Interattivi: Per una maggiore comprensibilità e interazione, i modelli sono stati implementati in notebook interattivi. Questi permettono di visualizzare in modo più diretto l'impatto delle varie fasi di addestramento e pulizia sui dati e sui risultati finali. 

### Dataset
- **Dataset principale:** La cartella 'dataset' contiene il dataset utilizzato per allenare i modelli di intelligenza artificiale. Questo dataset include vari attributi relativi agli ex detenuti, tra cui le competenze pregresse e, in due dei modelli, una colonna denominata Skills che rappresenta le abilità acquisite.

### Modelli di Machine Learning
- **Modelli con Skills:** Nella cartella 'models_skills', troverai i due modelli di intelligenza artificiale che sono stati allenati utilizzando il dataset con una colonna aggiuntiva Skills. Questi modelli sono ottimizzati per valutare le competenze e le abilità degli individui al fine di suggerire il lavoro più appropriato.
- **Modello senza Skills:** La cartella 'models_no_skills' contiene i due modelli allenati sul dataset senza la colonna Skills. Questi modelli servono a dimostrare l'impatto dell'inclusione delle skills nel processo decisionale del sistema di intelligenza artificiale.

## Come provare l'applicazione
Essendo questo progetto integrato con l'esame di Ingegneria del Software, l'applicazione mobile per provare il modello con relativa guida d'installazione sono presenti su [ReStart](https://www.github.com/rebeccadimatteo/ReStart).


