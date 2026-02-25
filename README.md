# tuuam
TUUAM (The Ultimate Urban Art Manager) a AI based LoRa Trainingsmanger

#Project Structure:
tuuam-project/
├── tuuam-backend/          # Spring Boot 3.x (Java 21)
│   ├── src/main/java/com/tuuam/
│   │   ├── controller/     # REST Endpoints (z.B. Caption-Test) [cite: 109]
│   │   ├── service/        # Spring AI Logik (ChatClient) [cite: 81]
│   │   ├── model/          # JPA Entities (INGRID-Ontologie) [cite: 35]
│   │   └── dto/            # Data Transfer Objects
├── tuuam-frontend/         # React (Vite + Tailwind + Zustand)
└── docker-compose.yml      # PostgreSQL & PGAdmin
