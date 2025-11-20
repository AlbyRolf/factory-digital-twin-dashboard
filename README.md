# 🏭 Industrial Digital Twin Simulator

Simulazione real-time di una linea di produzione industriale.  
Costruito con **Next.js**, **TailwindCSS**, **Prisma** e **MongoDB**, questo progetto dimostra come realizzare un **digital twin** moderno per macchinari industriali: monitoraggio, telemetria, stato macchine, warning/errori, eventi e grafici dinamici.

---

## ✨ Caratteristiche principali

- **Dashboard Industrial 4.0** con stato di tutte le macchine  
- **Simulazione telemetria real-time** (temperatura, carico, energia, vibrazioni…)  
- **Sistema di allarmi e log eventi** come un impianto reale  
- **Machine Detail Page** con grafici (storico, trends, alert)  
- **UI moderna** con Next.js App Router + Tailwind  
- **Database NoSQL (MongoDB)** tramite Prisma ORM  
- **Architettura scalabile e modulare**, estendibile con WebSocket/MQTT  
- **Simulatore interno** dei dati per mostrare dinamiche Industry 4.0  

---

## 🛠️ Tech Stack

| Tecnologia | Descrizione |
|-----------|-------------|
| **Next.js 14+** | App Router, Server Components, API Routes |
| **Tailwind CSS** | UI moderna, responsive, veloce |
| **Prisma ORM** | Data modeling con MongoDB |
| **MongoDB Atlas** | Database NoSQL scalabile |
| **Recharts / d3.js** | Grafici interattivi real-time |
| **TypeScript** | Tipizzazione avanzata |
| **Simulatore IoT custom** | Dati generati in tempo reale |

---

## 🚀 Funzionalità principali

### 🔧 Digital Twin delle macchine
Ogni macchina industriale include:
- Nome, codice, stato
- Temperatura, carico, energia
- Allarmi e messaggi
- Storico eventi
- Grafici performance

### 🧠 Simulazione real-time
Ogni 2–3 secondi una API aggiorna:
- temperatura (± variazioni random)  
- carico (± variazioni random)  
- stato dinamico (OK/WARNING/ERROR)  
- generazione eventi automatici  

### 📡 Vista linea di produzione
Dashboard con:
- cards macchina
- colori stato *(verde/giallo/rosso)*  
- statistiche generali  
- dettaglio macchina on click  

### ⚙️ Architettura pulita e modulare
- `/app` per routing moderno  
- `/components` per UI riutilizzabile  
- `/lib/db` per connessione Prisma  
- `/api/machines/live` per simulazione telemetria  

---

## 📂 Struttura del progetto

