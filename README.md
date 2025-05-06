# 📘 Limpide Letture – Guida all’Uso
## 🧠 Una risorsa di Fondazione ASPHI Onlus per rendere i testi più accessibili

### 🔍 Cos’è Limpide Letture?

**Limpide Letture** è una web app pensata per facilitare la comprensione dei testi scritti, soprattutto per:
- persone con disabilità cognitive o linguistiche,
- studenti con basso livello di italiano (es. livello A1),
- persone sorde con difficoltà nella lingua scritta.

La app evidenzia le **parole difficili**, propone **spiegazioni semplici** e genera anche una **versione semplificata dell’intero testo** usando l’intelligenza artificiale GPT.

---

## ⚙️ Come si usa – Passaggi principali

### 1. 🗝 Inserisci la tua API key OpenAI

Per usare l’IA (GPT), devi ottenere una chiave API da OpenAI:

#### ▶ Come fare:
1. Vai su [https://platform.openai.com/signup](https://platform.openai.com/signup) e crea un account.
2. Accedi a [https://platform.openai.com/api-keys](https://platform.openai.com/api-keys).
3. Clicca su **“Create new secret key”** e copia la chiave.
4. Incollala nel campo **"Inserisci la tua API Key GPT OpenAI"** nella web app.

#### 💸 Costi (orientativi):
- Il modello utilizzato è **GPT-4 Turbo** (come su ChatGPT Plus).
- Costo indicativo: **0,01 $ ogni 750 parole** (input + output).
- Puoi tenere sotto controllo i costi su:  
  [https://platform.openai.com/account/usage](https://platform.openai.com/account/usage)
- Puoi anche impostare un **limite massimo mensile**:  
  [https://platform.openai.com/account/billing/limits](https://platform.openai.com/account/billing/limits)

---

### 2. 📄 Inserisci il testo

Scrivi o incolla il testo da analizzare nel campo **“Inserisci il testo”**.

---

### 3. 📁 Carica o aggiungi parole conosciute

Puoi:

- **Aggiungere manualmente** parole che non devono essere considerate difficili.
- **Caricare un file `.txt`** con l’elenco delle parole da considerare già conosciute (una per riga).

#### 🧾 Suggerimento:
Hai a disposizione (se lo desideri) un file `.txt` con **tutti i lemmi del vocabolario fondamentale di Tullio De Mauro**, che rappresenta circa **2000 parole** di uso più frequente e comprensibile in italiano.  
Puoi usarlo come base per escludere automaticamente molte parole comuni dalla semplificazione.

---

### 4. 👁 Lettura Guidata

Clicca su **“Lettura Guidata”** per:
- analizzare il testo,
- evidenziare le parole potenzialmente difficili,
- ottenere, al clic, una **spiegazione semplificata generata da GPT**.

> Cliccando su “Prompt per Lettura Guidata” puoi **modificare** il prompt usato da GPT per spiegare le parole.

---

### 5. 🖱 Spiega selezioni evidenziate

Puoi **selezionare manualmente** una parola o frase nel testo e cliccare su **“Spiega selezione evidenziata”** per ottenere una spiegazione personalizzata.

---

### 6. 🪄 Semplifica tutto il testo

Clicca su **“Semplifica Testo”** per ottenere una **riscrittura più facile** dell’intero brano, pensata per un lettore con livello A1.

> Puoi modificare anche il **prompt per la semplificazione** cliccando su “Prompt per Semplificazione Testo”.

---

### 7. 🧾 Esporta in PDF

Clicca su **“Esporta PDF”** per scaricare un file che contiene:
- il testo originale,
- le spiegazioni delle parole difficili,
- eventuali spiegazioni delle selezioni evidenziate.

---

## 🛠 Altre funzionalità utili

- Le parole vengono “semplificate” usando anche un’analisi **morfologica** (es. “camminando” → “cammin”).
- Puoi **salvare e ricaricare** automaticamente l’elenco dei tuoi lemmi conosciuti (usando `localStorage`).
- Il sistema **ricorda la tua API key e i prompt personalizzati** (sempre in locale sul browser).

---

## 🔐 Privacy e sicurezza

👉 La tua **API Key** resta salvata **solo nel tuo browser**, non viene mai condivisa con server esterni. Tutte le richieste vanno **direttamente ai server di OpenAI** tramite HTTPS.

---

## 📬 Contatti

Per supporto tecnico o educativo:  
📧 info@asphi.it  
🌍 [https://www.asphi.it](https://www.asphi.it)
