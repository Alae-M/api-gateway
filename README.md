# API Gateway

This component routes requests to the appropriate microservices (ledenservice, teamservice, wedstrijdservice).

## Functionality
- Routes API requests to respective microservices.
- Provides authentication and security for endpoints.

## Endpoints
- Routes to:
  - `/leden` → Ledenservice
  - `/teams` → Teamservice
  - `/wedstrijden` → Wedstrijdservice

## Run Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Alae-M/api-gateway.git
