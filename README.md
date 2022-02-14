# BusinessProcessModeling_project

## Introduzione
Leggere attentamente il testo del progetto e consegnare una breve relazione
(max. 7 pagine di testo, figure escluse) in formato elettronico che
illustri le soluzioni proposte e le analisi condotte.
Progettare le reti a partire da modelli più astratti (EPC, BPMN), utilizzando
le tecniche di trasformazione viste nel corso indicando quali tecniche
sono state impiegate e perch´e.
Nel presentare una workflow net, illustrarne le caratteristiche (invarianti,
s-components, se `e free-choice, se `e well-handled, se `e safe,...) e descrivere
le caratteristiche del grafo di raggiungibilit`a (quanti vertici, quanti archi, se
contiene cicli,...).
Per lo sviluppo di workflow module, verificare preventivamente che togliendo
le piazze di input / output dell’interfaccia (e gli archi incidenti su
esse) la rete sia sound.
Qualora non sia possibile progettare processi sound, chiarirne i motivi e
studiarne le proprietà di weak soundness.
Se ritenuto utile, compilare la checklist di analisi disponibile sul canale
Teams del corso per ogni rete analizzata.
Spedire al docente la versione elettronica della relazione in formato .pdf,
i file .pnml di tutte le reti analizzate, i file .bpmn di tutti i diagrammi BPMN
progettati e, opzionalmente, le checklist di analisi. Le checklist (Microsoft
Forms) possono essere compilate e inviate direttamente online, oppure in
formato .pdf.

## Scuola di recitazione

Si consideri lo scenario di una scuola di recitazione che debba gestire le
richieste degli allievi. L’allievo contatta la scuola e riceve una lista dei corsi
disponibili. L’allievo sceglie il corso e viene messo in contatto con un maestro.
Il maestro propone una data e luogo per la prima lezione e l’allievo
può accettare, o proporre data e luogo diversi e così via fino a quando l’appuntamento
viene fissato. Prima di ogni incontro l’allievo riceve un testo da
preparare. Durante l’incontro l’allievo esegue una serie di prove proposte dal
maestro e ogni prova non eseguita correttamente viene ripetuta. Al termine
di ogni incontro, dopo aver effettuato il pagamento elettronico alla scuola,
l’allievo e il maestro possono accordarsi per un nuovo appuntamento (col
procedimento descritto sopra), oppure l’allievo può decidere di concludere il
corso. Se il corso viene terminato, il cliente informa la scuola e il processo si
conclude.
Progettare opportuni processi che rispecchino fedelmente lo scenario sopra
descritto e siano compatibili.
Modificare i processi in modo che al termine del corso l’allievo possa
scegliere se iniziare un nuovo percorso di apprendimento.
