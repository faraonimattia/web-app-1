# Progetto Maven HelloWeb

## Obiettivo
Il progetto HelloWeb è una semplice applicazione web sviluppata con Maven. Seguendo le prime tre lezioni della guida, il progetto consiste nella creazione di una pagina principale `index.jsp` che visualizza un messaggio di benvenuto con la data corrente e un link alla pagina `author.jsp`. La pagina `author.jsp` contiene le informazioni sull'autore, come il nome, il cognome e la classe. Inoltre, è stata implementata un'API REST che restituisce un dato JSON quando si visita l'endpoint `/api/test/eleonora`.

## Funzionalità

1. **Pagina principale (index.jsp)**:
   - Il messaggio di benvenuto visualizzato nella home page include la data corrente e un link alla pagina dell'autore.
   - Esempio del messaggio visualizzato:
     ```
     Benvenuto Utente Curioso, questo è la mia prima JSP. Oggi è il giorno <data>
     Autore: [link]
     ```
   - Dove `<data>` rappresenta la data corrente e `[link]` è un collegamento alla pagina `author.jsp` che mostra le informazioni sull'autore.

2. **Pagina dell'autore (author.jsp)**:
   - La pagina `author.jsp` visualizza il nome, il cognome e la classe dell'autore.
   - Autore: Mattia Faraoni
   - Classe: 5AI Informatica

3. **API REST**:
   - È stata creata un'API REST con l'endpoint `/api/test/eleonora`. Questo servizio risponde con un dato JSON quando viene interrogato.
   - URL dell'API: `/api/test/eleonora`

## Componenti utilizzati

1. **JSP (JavaServer Pages)**:
   - Le pagine `index.jsp` e `author.jsp` sono state utilizzate per visualizzare il contenuto dinamico (la data corrente e le informazioni sull'autore).
   - L'uso di JSP consente di creare facilmente contenuti web dinamici in Java.

2. **Maven**:
   - Il progetto è stato creato utilizzando **Maven** come sistema di build. Maven è stato utilizzato per gestire le dipendenze del progetto, compilare il codice e creare il pacchetto WAR (Web Application Archive).

3. **JAX-RS (Java API for RESTful Web Services)**:
   - L'API REST è stata implementata utilizzando **JAX-RS**, che fornisce un modo semplice e diretto per creare servizi RESTful in Java.

4. **Git**:
   - Il codice sorgente del progetto è stato gestito tramite **Git**, con il repository caricato su **GitHub**. Questo permette di tenere traccia delle modifiche nel tempo e di lavorare in modo collaborativo.

## Come eseguire il progetto

1. **Clonare il progetto**:
   Clona il repository GitHub utilizzando il comando:
   ```bash
   git clone https://github.com/faraonimattia/web-app-1.git
