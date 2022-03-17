# Progetto javascript con firebase

Questo progetto svolge operazione di CRUD utilizzando un account google con firebase. Segui gli step successivi per utilizzarlo.

## Aggiungere autenticazione

* Crea un progetto sull'account firebase, ed entraci 
* Inserisci un provider di autenticazione anonimo (senza email o password)

![autenticazione](/screen/auth.png)

* Clicca sul tasto **Aggiungi un'app per iniziare** (su quello web), in modo da recuperare le credenziali che ti servono

![configurazione](/screen/app-config.png)

* Dai un nome all'app e la registri
* Inserisci il contenuto della costante **firebaseConfig**, nella variabile **config** che trovi in **app.js** di questo progetto


## Importa il database

* Sulla console di firebase, clicca a sinistra su **Realtime database**
* Clicca sui tre puntini a destra e importa il file **data-model.json**

![database](/screen/database.png)

# Utilizzo

* Apri **index.html**
* Ci sono icone per cancellare i dati esistenti, o aggiungere

![home](/screen/home.png)

* Se si clicca su un nome, a destra appare il dettaglio

![dettagli](/screen/detail.png)
