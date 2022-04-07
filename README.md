Lo scopo del progetto è estrapolare informazioni, relative alle lecture notes, da un sito in cui sono presenti i corsi del MIT.
Le informazioni che dovevamo raccogliere, e in seguito riportare in un csv, sono le seguenti: il titolo, la descrizione, il link, i file pdf (qualora ce ne siano) 
la durata del corso e la difficoltà, in base a quest'ultima dire il range di età e il grado di istruzione.
È stata creata una classe che possa contenere le informazioni e con un metodo stamparle.
Il programma è, inoltre, strutturato su diverse funzioni, ognuna ha uno specifico compito come ad esempio la funzione che stampa nel file le informazioni di ogni attributo, la funzione che fa web scraping,
infine l'ultima funzione "getCoursePDF" va a ricercare il pdf nel sito e lo salva sul drive di un account google, e crea un oggetto che va a stampare tutte le informazioni raccolte.
Per quanto riguarda le librerie abbiamo usato request, fondamentale per madare richieste ai siti web, bs4 e selenium per estrapolare il codice html dal sito, math per esegurie operazioni matematiche in alcuni punti del codice, pdfilereader per leggere i file pdf.
Infine tramite git e github è stata creata una cartella condivisa in cui all'interno si trovano 4 branch, uno denominato "v1" contenente il programma prima che il sito venisse aggiornato,
"scroller" che contiene il codice che permette di scorrere la pagina come un utente normale, "datacollector" con il codice che colleziona le informazioni del sito 
e infine "master" con la versione finale del codice. In quest'ultimo è stata eseguita una procedura di merging da scroller e datacollector.