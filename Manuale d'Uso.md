# 🦺 Gestione DPI - Manuale d'Uso

## 📋 Introduzione
**Gestione DPI** è un sistema web per la gestione dei Dispositivi di Protezione Individuale in azienda. Il sistema permette di registrare consegne, gestire lavoratori e DPI, e generare report stampabili.

![Dashboard](https://via.placeholder.com/800x400/667eea/ffffff?text=Dashboard+Gestione+DPI)

## 🔐 Accesso al Sistema
1. **Login con Google**: Accedi con il tuo account Google istituzionale
2. **Autorizzazione**: Solo utenti autorizzati possono accedere ai dati
3. **Sicurezza**: I dati sono protetti su server Firebase

![Login](https://via.placeholder.com/400x300/764ba2/ffffff?text=Schermata+Login)

## 🏠 Dashboard Principale
La dashboard fornisce una panoramica completa:
- **Lavoratori Attivi**: Numero totale di lavoratori registrati
- **DPI in Stock**: Dispositivi disponibili in magazzino
- **Consegne Totali**: Storico completo delle consegne
- **Scadenze Prossime**: DPI in scadenza nei prossimi 30 giorni

## 👥 Gestione Lavoratori
### Aggiungere un Lavoratore
1. Vai alla sezione "Lavoratori"
2. Compila i campi: Nome, Cognome, Matricola
3. Opzionale: Reparto e Mansione
4. Clicca "Aggiungi Lavoratore"

![Gestione Lavoratori](https://via.placeholder.com/800x400/3498db/ffffff?text=Gestione+Lavoratori)

### Modificare/Eliminare
- **Modifica**: Clicca il pulsante ✏️ sulla riga del lavoratore
- **Elimina**: Clicca il pulsante 🗑️ (conferma richiesta)

## 🦺 Gestione DPI
### Registrare un Nuovo DPI
1. Sezione "DPI" → "Aggiungi DPI"
2. **Campi obbligatori**:
   - Nome DPI (es: "Scarpe Antinfortunistiche")
   - Codice SAP univoco
   - Categoria (Testa, Occhi, Mani, etc.)
3. **Campi opzionali**:
   - Scadenza in mesi
   - Note aggiuntive

![Gestione DPI](https://via.placeholder.com/800x400/27ae60/ffffff?text=Gestione+DPI)

## 🚚 Consegna DPI
### Procedura di Consegna
1. **Seleziona Lavoratore**: Cerca per nome, cognome o matricola
2. **Scegli DPI**: Seleziona dal menù a tendina
3. **Dettagli Consegna**:
   - Quantità
   - Data di consegna
   - Motivo (Primo Prelievo/Danneggiato/Scaduto)
4. **Firme Digitali**:
   - Firma del Preposto
   - Firma del Lavoratore

![Consegna DPI](https://via.placeholder.com/800x400/e74c3c/ffffff?text=Procedura+Consegna)

### Firme Digitali
- **Disegna** direttamente sull'area della firma
- **Cancella** con il pulsante dedicato
- **Salvataggio** automatico come immagine

## 🖨️ Stampa e Report
### Generare Report
1. Vai alla sezione "Stampa"
2. **Filtra per**:
   - Singolo lavoratore o tutte le consegne
   - Intervallo di date
3. **Carica Consegne**: Visualizza anteprima
4. **Stampa PDF**: Genera documento professionale

![Stampa](https://via.placeholder.com/800x400/f39c12/ffffff?text=Stampa+Consegne)

### Caratteristiche PDF
- Logo aziendale personalizzabile
- Tabella con tutte le informazioni
- Firme digitali incluse
- Numerazione pagine

## ⚙️ Impostazioni
### Personalizzazione
- **Nome Azienda**: Visualizzato sui report
- **Logo Aziendale**: Usato nelle stampe PDF
- **Tema**: Modalità chiara/scura
- **URL Documentazione**: Link alla guida

### Backup e Sicurezza
- **Esporta Dati**: Backup completo
- **Importa Dati**: Ripristino configurazione
- **Cancella Dati**: Reset completo (conferma)

## 🔄 Migrazione Dati
### Migrazione Automatica
Il sistema include uno strumento di migrazione per:
- Convertire vecchi ID DPI in codici SAP
- Uniformare i formati dei dati
- Correggere inconsistenze

### Utilizzo
1. Vai in "Stampa"
2. Clicca "Migra Consegne Vecchie"
3. Attendi il completamento
4. Verifica i risultati

## 🐛 Risoluzione Problemi
### Problemi Comuni
1. **Firme non salvate**: Ricontrollare che siano state apposte
2. **DPI non visualizzati**: Verificare il codice SAP
3. **Login fallito**: Controllare connessione internet

### Debug Integrato
Usa il pulsante "Debug Dati" per:
- Visualizzare lo stato dei dati
- Identificare problemi
- Verificare collegamenti

## 📱 Utilizzo Mobile
Il sistema è completamente responsive:
- **Tablet**: Layout ottimizzato
- **Smartphone**: Navigazione semplificata
- **Touch**: Firme ottimizzate per touchscreen

## 🔒 Sicurezza e Privacy
- **Dati crittografati** su Firebase
- **Accesso protetto** da autenticazione Google
- **Backup automatici** su cloud
- **Privacy** conforme al GDPR

---

*Ultimo aggiornamento: ${new Date().toLocaleDateString('it-IT')}*
