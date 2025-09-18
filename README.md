# Eco-Moda Reports  README


# 🌱 Eco-Moda Reports

Progetto demo full-stack con **Spring Boot (backend)** e **Angular (frontend)** per la consultazione e il download di report di sostenibilità.
Non è previsto alcun database: i dati sono gestiti tramite file JSON normalizzati.

---

## 🚀 Quick Start

```bash
# Backend
cd backend
mvn clean install
mvn spring-boot:run   # oppure avvia MyReportDownloaderApplication da IDE

# Frontend
cd frontend
npm install
ng serve -o
```

* API → [http://localhost:8080](http://localhost:8080)
* App Angular → [http://localhost:4200](http://localhost:4200)

---

## ⚙️ Backend (Spring Boot)

1. Posizionarsi in `backend/`
2. Build con Maven:

   ```bash
   mvn clean install
   ```
3. Avvio:

   * **IDE**: eseguire la classe
     `com.fabiolabarone.myreportdownloader.MyReportDownloaderApplication`
   * **CLI**:

     ```bash
     mvn spring-boot:run
     ```
   * **Configurazione Run/Debug**: vedi immagine allegata

---

## 🎨 Frontend (Angular)

1. Posizionarsi in `frontend/`
2. Installare dipendenze:

   ```bash
   npm install
   ```
3. Avviare server di sviluppo:

   ```bash
   ng serve -o
   ```
4. L’app sarà disponibile su [http://localhost:4200](http://localhost:4200)

---

## 🔗 Flusso di lavoro

1. Avviare **prima il backend** (Spring Boot)
2. Quando Angular ha completato lo start, aprire l’app su `http://localhost:4200`
3. L’interfaccia comunica con il backend per elencare i report e scaricare i PDF

---

## 📦 Tecnologie

* **Backend** → Spring Boot, Java 17
* **Frontend** → Angular, TypeScript, Bootstrap
* **Ambiente di sviluppo consigliato** → IntelliJ IDEA / VS Code, Node.js LTS




