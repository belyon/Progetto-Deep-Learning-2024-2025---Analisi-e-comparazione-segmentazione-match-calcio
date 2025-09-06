<h1><b>Progetto Deep-Learning-2024-2025 - Analisi-e-comparazione-segmentazione-dominio calcio</b>b></h1><br>
<h2>Studenti: Riccardo Spano (449367) - Alessio Prete (533010) </h2>


<h3> Informazioni </h3>
L'obiettivo principale di questo progetto è stato condurre un'analisi comparativa 
delle prestazioni di tre moderne architetture di deep learning <b>YOLOv8</b>, <b>Segment Anything (SAM) (1 e 2 video nativo)</b> e <b>Mask2Former</b> applicate al task di segmentazione di scene di partite di calcio
La sperimentazione è consistita nel testare i modelli pre-addestrati su:<br>
<br>-	O fotogrammi estratti da una breve clip
<br>-	O direttamente su video nel caso di SAM 2
<br><br>
SENZA effettuare un fine-tuning iniziale e quindi in modalità zero-shot. Questo approccio consiste nell'applicare un modello, già pre-addestrato su un dataset vasto e generico, a un compito specifico - in questo caso, la segmentazione di scene calcistiche - senza effettuare alcuna fase di ulteriore addestramento e di fine-tuning sui dati del nuovo dominio.
L'analisi ha avuto lo scopo di determinare quale architettura si sia comportata più efficacemente nella segmentazione dell'intera scena composta di giocatori, arbitri e altri oggetti presenti sul campo come bandierine, reti e telecamere, con un'attenzione particolare all'identificazione di pannelli pubblicitari.






