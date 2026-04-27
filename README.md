# Termomecanica AEP

This repository contains a comprehensive technical documentation web application for Termomecanica AEP with SAP integration capabilities.  

## Setup Instructions

### Prerequisites
- Node.js and npm
- Docker
- PostgreSQL

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/pcaputo-cpu/Termomecanica-AEP.git
   cd Termomecanica-AEP
   ```
2. Install dependencies for frontend:
   ```bash
   cd frontend
   npm install
   ```
3. Install dependencies for backend:
   ```bash
   cd backend
   npm install
   ```
4. Set up environment variables by copying `.env.example` to `.env` and adjusting as necessary.
5. Start the application using Docker:
   ```bash
   docker-compose up
   ```

## Structure
- /frontend: Next.js application
- /backend: Express API
- /database: SQL schemas
- /docker: Docker files

## License
This project is licensed under the MIT License.