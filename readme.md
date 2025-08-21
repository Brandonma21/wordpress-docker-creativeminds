# CreativeMinds

A Dockerized WordPress environment.

## Usage
1. Copy `.env.example` to `.env` and fill in your own credentials:
    ```bash
    cp .env.example .env
    ```

2. Start the environment: 
    ```bash
    docker compose up -d
    ```

3. Open [http://localhost:8080](http://localhost:8080) in your browser.

## Notes
- WordPress runs on port `8080` by default.
- Database and WordPress data are persisted in Docker volumes.
- Do **not** commit your `.env` file to GitHub.
