# AWCProject
University Project of the 'Web and Cloud Applications' course 

# Premessa e Requisiti
Il progetto si poneva l'obiettivo di sviluppare l'applicazione web "Album delle figurine dei Super Eroi", un sito di gestione delle figurine virtuali di super eroi. Viene richiesto di implementare un album elettronico di figurine con l'acquisto di pacchetti, e di creare una sorta di piattafoma che permetta lo scambio di doppioni tra i giocatori.

Tre macro-scenari principali:
- gestione del profilo utente: acquisizione dei dati principali, fase di registrazione e login, modifica o eliminazione del profilo.
- acquisto di pacchetti di figurine (pagamento fittizio): acquisto di crediti, acquisto figurine casuali, caricamento dei dati relativi ai super eroi vinti (series, events, comics). 
- gestione dello scambio di figurine: proposta e accettazione di scambi disponibili

# Acquisizione e gestione dei dati
Le informazioni riguardanti i super eroi sono stati acquisiti tramite le API REST del portale <link> https://developer.marvel.com/docs </link>

I dati degli utenti sono stati provvisoriamente salvati in un web storage, come richiesto nelle specifiche del progetto, e resi disponibili in formato JSON.

Per questo progetto sono stati usati i seguenti linguaggi: HTML5, CSS3, Javascript, JSON, e l'utilizzo del framework Bootstrap
