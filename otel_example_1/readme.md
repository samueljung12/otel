# Otel SDK instrumented on application

## Couple of pre-requisites before starting up docker compose:
- Replace your API key inside of `otel-collector/.env.local` file
- Replace your applicationID and clientToken inside of `frontend/src/app.js` file

Command to start: `docker-compose up --build`

Command to stop: `docker-compose down`
