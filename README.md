# tuuam
TUUAM (The Ultimate Urban Art Manager) a AI based LoRa Trainingsmanger

### 📂 Project Structure

```text
tuuam-project/
├── tuuam-backend/          # Spring Boot Orchestrator (Java 21)
│   ├── src/main/java/com/tuuam/
│   │   ├── controller/     # REST API Layer
│   │   ├── service/        # Business Logic & Spring AI Integration
│   │   ├── repository/     # Database Access (Spring Data JPA)
│   │   ├── model/          # Domain Entities (INGRID Ontology)
│   │   └── dto/            # Data Transfer Objects
├── tuuam-frontend/         # React Web Interface (Vite, Tailwind, Zustand)
├── docker/                 # Persistent database storage (ignored by git)
└── docker-compose.yml      # Infrastructure (PostgreSQL & pgAdmin)
