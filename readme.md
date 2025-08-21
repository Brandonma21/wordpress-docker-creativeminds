# CreativeMinds

A Dockerized WordPress environment.

## Usage
1. Copy `.env.example` to `.env` and fill in your own credentials:
    - cp .env.example .env

2. Start the environment: 
    - docker compose up -d

3. Open [http://localhost:8000](http://localhost:8000) in your browser.

## Notes
- WordPress runs on port `8000` by default.
- Database and WordPress data are persisted in Docker volumes.