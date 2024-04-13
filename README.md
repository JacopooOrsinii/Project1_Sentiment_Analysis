# Sentiment_Analysis

L'analisi del sentimento rappresenta una tecnica nell'ambito del natural language processing (NLP) che consiste nel determinare e comprendere le opinioni, le emozioni e le attitudini espressi in un dato testuale. Questa tecnica può avere delle applicationi utili per le aziende, come il social media monitoring o il customer feedback analysis.

## Struttura del progetto
1. Preprocessing: in questa fase i dati testuali vengono processati, in modo da poter essere analizzati successivamente e poter essere sottoposti ad algoritmi di Machine Learning
2. Assegnazione degli score di gradimento: viene implementato un sistema di assegnazione di score di gradimento del prodotto o servizio recensito attraverso il Sentiment Intensity Analyzer (SIA)
3. Clustering delle recensioni: si vuole implementare una distinzione tra i prodotti/servizi oggetto della recensione. In particolare, si vuole distinguere tra recensioni che hanno ad oggetto un bar/ristorante e recensioni che non hanno come oggetto un bar/ristorante
4. Creazione della colonna will_recommend: una volta distinti i clenti dei bar/ristoranti, si vuole calcolare quanti di loro, in seguito ad un'esperienza positiva del servizio, saranno inclini a consigliarlo ai propri conoscenti

## Obiettivi raggiunti
Si evidenziano principalmente 2 obiettivi raggiunti da questa ricerca:
1. Segmentazione della clientela: è stato possibile suddividere i clienti in gruppi a seconda dei prodotti/servizi oggetto delle recensioni grazie alle parole utilizzate in queste ultime; questa caratteristica può essere utile per le aziende nella fase di profilazione della clientela
2. Comprendere meglio la qualità del servizio: grazie alla divisone tra clienti che raccoanderanno il servizio e clienti che non raccomanderano il servizio, è stato possibile stabilire una prima mappature della percezione, da parte dei clienti, del servizio offerto dall'aziend. Inoltre, è stato possibile stabilire che le parole più importanti nelle recesioni negative, sono: place, food e service. Queste informazioni possono aiutare molto le imprese nel miglioramento del proprio servizio
