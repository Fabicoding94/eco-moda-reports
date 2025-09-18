# Eco-Moda Reports

Eco Moda Reports – README

Progetto demo full-stack con Spring Boot (backend) e Angular (frontend) per la consultazione e il download di report di sostenibilità.
Non è previsto alcun database.

⚙️ Backend (Spring Boot)
Avvio

Posizionarsi nella cartella backend/.

Eseguire la build:

mvn clean install


Avviare l’applicazione:

Metodo A: dalla classe principale
src/main/java/com/fabiolabarone/myreportdownloader/MyReportDownloaderApplication.java → clic sul triangolo verde in IDE.

Metodo B: con Maven

mvn spring-boot:run


Metodo C: configurazione Run/Debug (vedi immagine 1 allegata).

L’API sarà disponibile su http://localhost:8080.

🎨 Frontend (Angular)
Avvio

Posizionarsi nella cartella frontend/.

Installare le dipendenze:

npm install


Avviare il server di sviluppo:

ng serve -o


L’app sarà disponibile su http://localhost:4200.

🔗 Flusso di lavoro

Avviare prima il backend (Spring Boot).

Una volta che Angular ha fatto lo start, aprire http://localhost:4200.

L’interfaccia comunicherà con il backend per recuperare i report JSON e scaricare i PDF.

📦 Note

Non è richiesto alcun database: i dati sono gestiti tramite file JSON normalizzati.

Tecnologie usate:

Backend → Spring Boot, Java 17

Frontend → Angular, TypeScript, Bootstrap

Ambiente di sviluppo consigliato: IntelliJ IDEA / VS Code + Node.js LTS.

