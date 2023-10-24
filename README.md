# CIRCOLO DI LETTURA
## CHE COSA È? 
Questo sito è dedicato alla condivisione di opinioni su libri e di booktrailer. Può essere facilmente modificato seguendo il seguente Tutorial
## CONFIGURAZIONE DEL SITO "CIRCOLO DI LETTURA"
1) Crea o utilizza un account GMAIL per tutte le operazioni

### CONFIGURAZIONE DEL "DATABASE"
2) Vai su "https://sheetlabs.com/" e premi `"Sign Up"`
3) Compila i campi richiesti:

- Forename = NOME
- Surname = COGNOME
- Email = L'EMAIL DELL'ACCOUNT SCELTO
- Password = SCEGLI UNA PASSWORD
-  Confirm Password = RISCRIVI LA PASSWORD PRECENDENTE

⚠️ SEGNA I DATI Email E Password CHE HAI INSERITO ⚠️

- Organisation name = INVENTA UN NOME PER L'API, CONSIGLIO "CIRCOLO DI LETTURA", NON SARA' VISIBILE A NESSUNO
- Organisation code = AUTOCOMPILATO CON LE PRIME 4 LETTERE DEL NOME
- Plan = SCEGLI "Free - 5 APIs, 5 users, 10,000 queries per month"
- Premi Create Account

4) Ti ritroverai due pulsanti, premi il secondo, quello con su scritto `"Import a table from Google Sheets"`
5) Vai all'indirizzo "https://docs.google.com/spreadsheets" con il tuo account Google e, sotto `"Crea un nuovo foglio di lavoro" `premi `"Vuoto"`
- In alto a sinistra nominalo al posto di `"Foglio di lavoro senza nome"` ` "Circolo di lettura"` con il nome della tua classe
- Nel foglio di lavoro poi vai nella barra delle operazioni premendo `"Strumenti"` e poi `"Crea un nuovo modulo"`
- In basso a destra dove c'è scritto `"Foglio1"` premi tasto destro e poi `"Elimina"`, apparirà un avviso, premi `OK`
- Apparirà in basso a sinistra una nuova scheda Chiamata `"Risposte del modulo 1"` con, nella prima colonna : 
| Informazioni cronologiche | Domanda senza titolo |
| ------------------------- | -------------------- |
- Premi nella barra in alto `"Strumenti"`, poi `"Gestisci Modulo"` e infine `"Modifica Modulo"`
⚠️ DA ORA IN POI DEVI DARE LE ESATTE DENOMINAZIONI A TUTTE LE DOMANDE, ALTRIMENTI IL SITO NON FUNZIONERA' ⚠️
 - aggiungi la prima domanda con titolo `"Chi"` di tipo "Testo risposta breve"
 - aggiungi la seconda domanda con titolo `"Titolo"` di tipo "Testo risposta breve"
 - aggiungi la terza domanda con titolo `"Descrizione"` di tipo "Testo risposta breve"
 - aggiungi la quarta domanda con titolo `"Commento"` di tipo "Testo risposta breve"
 - aggiungi la quinta domanda con titolo `"Valutazione"` di tipo "Scala lineare" Da 1 a 5
 - aggiungi la sesta domanda con titolo `"Copertina"` di tipo "Caricamento di file" con "Consenti solo tipi di file specifici" su "Immagine", "Numero massimo di file" su "1" e "Dimensioni massime del file" su "1GB"
 - Vai nelle impostazioni in alto a destra, scendi fino alla voce `"Dimensioni totale massime per tutti i file caricati"` e scegli `"10GB"`
 - Dato che siamo nelle impostazioni consiglio di spuntare `"Consenti modifica risposte"` su `Vero`, `"Raccogli indirizzi email"` su `"Inserimento da parte dell'intervistato" o "Verificati"` e, aprendo la scheda `"Presentazione"` di spuntare `"Mostra link per inviare un'altra risposta"` su `vero` e di modificare `"Messaggio di conferma"` su qualcosa del genere : 
 `Il tuo libro è stato aggiunto con successo!
Potrebbe non essere immediatamente presente sul sito, in caso di errori contattare...`
 - Ritornando su `"Domande"` aggiungi la settima domanda con titolo `"Booktrailer"` di tipo "Caricamento di file" con "Consenti solo tipi di file specifici" su "Documento" e "Video" e "Presentazione", "Numero massimo di file" su "1" e "Dimensioni massime del file" su "1GB"
 - aggiungi l'ottava domanda con titolo `"Generi"` di tipo "Caselle di controllo" aggiungendo i generi che ti vengono in mente preceduti da un # come:
`	#biografia
	#storico
	#giallo
	#thriller
	#avventura
	#fantascienza
	#distopia
	#fantasy
	#horror
	#youngadult
	#formazione
	#rosa
	#umoristico
	#filosofico	`

- Aggiungi la prima domanda con titolo `"Commenti"` di tipo "Scelta multipla" con unica scelta `"{"comments":[]}"`

- A questo punto premi `"Invia"` in alto a destra, poi la seconda icona rappresentante il collegamento, spunta la casella `"Abbrevia URL"` e premi `"Copia"`

- Appuntati questo link del tipo "https://forms.gle/..."

6) Una volta fatto ciò ritorna nel foglio di lavoro legato al form e premi `"Condividi"`, mettendo come `"Accesso"` `"Chiunque abbia il link"` e premi `"Fine"`
7) Ritorna nella finestra di Sheetlabs che era rimasta con un bottone `"Sign in with Google"`, Premilo e scegli l'account con cui hai creato il foglio e il modulo, poi premi `"Consenti"`
8) Fatto ciò individua il foglio che avevi nominato prima `"Circolo di lettura" con il nome della tua classe` dalla lista e premi il pulsante blu a fianco `"Import"`, ci metterà un pò a caricare e ti ritroverai alcune impostazioni. Modifica `"Reload data automatically"` a `"Yes, whenever the content changes, and also once per hour"`. In fine premi `"Create data table"`

9) Una volta fatto ciò premi il pulsante `"Create an API this Data Table"`. Comparirà una scheda da modificare:

- `API name` = "Circolo di lettura" con il nome della tua classe
- Apri la scheda `"GET requests outputs"` e metti `"Include the unique Sheetlabs record ID in API responses, in a field named __id"` a vero
- Apri la scheda `"Writing data to your API (POST, PUT, PATCH and DELETE requests)"` e spunta il valore `"Allow records to be amended, via PATCH requests"`
- Nella parte `"Permissions"` cambia a `"Public: Allow completely public/anonymous access to the API (no authentication at all)"`
- Premi il tasto verde `"Create API"`
- Uscirà una schermata del tipo:
`API created successfully
Your API is live at https://sheetlabs.com/.../....`

`Documentation can be accessed at https://sheetlabs.com/#/services/doc/..../..... . You can share this documentation link with your users.`

`You may now wish to create users to allow people to access your new API.`

⚠️Copia il valore "https://sheetlabs.com/.../...." e appuntalo insime all'altro link ⚠️

10) Nel tuo Account google andando a "https://drive.google.com/drive" carica lo sfondo come nell'esempio e condividila a `"Chiunque abbia il link"` e copia il link. Il link è del tipo "https://drive.google.com/file/d/**********************************/view?usp=sharing". Copia il campo `**********************************` e appuntalo con gli altri link.

`L'IMMAGINE DI SFONDO: consiglio una immagine che sia ripetuta, anche detto "PATTERN" in modo che non si noti il distacco tra una immagine e la sua copia`

### FILE DEGLI APPUNTI
Il file degli appunti dovrebbe contenere i seguenti link del tipo:
- https://forms.gle/... ,
- https://sheetlabs.com/.../.... ,
- "**********************************"

### CONFIGURAZIONE DEL FILE
 - Apri il file `index.html` con notepad o con qualunque altro editor di testo
 - Vai dalla 49esima riga alla 51esima e modifica i valori esempio con quelli segnati
 - Salva il file
 - Il valore `CANADD` indica se chi vede il sito può vedere il link per aggiungere una scheda,

`🎉 CONGRATULAZIONI, IL FILE E' PRONTO PER L'UTILIZZO! 🎉`

### CARICAMENTO ONLINE	
- Apri con il tuo account Google https://sites.google.com/u
- Crea un nuovo sito vuoto
- Alla destra in alto premi `Pagine`,`+`, `Incorporazione della pagina intera`
- Accanto all' "Untiled Page" premi i tre puntini, `imposta come Home Page`
- Accanto all'"Home page" premi i tre puntini, `Elimina`
- Troverai una pagina con due bottoni, premi `Aggiungi incorporamento`, `Incorpora Codice`
- Copia il contenuto del file HTML con notepad con il comando `CTRL + A, CTRL + C`
- Incolla il contenuto del file in google site nella finestra aperta e premi `Avanti` e poi `Inserisci`
- Premi in alto a destra il pulsante blu `Publica`, scegli un indirizzo web come `"circolodilettura" + Nome della scuola + Classe`
- Spunta `Richiedi ai motori di ricerca pubblici di non mostrare il mio sito` e Premi `Publica`
A questo punto il tuo sito sarà online all'indirizzo che puoi copiare con la terza icona da sinistra in google sites e premendo `Copia Link`
# IL TUO SITO È PRONTO !
