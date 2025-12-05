
# Geo-location Bot 

A lightweight chat bot built with **Node.js** and **Express** that can detect and display user geolocation. The project is containerized with Docker for easy deployment and portability.

 Features
- **Geolocation detection**: The bot retrieves and shows user coordinates or location details.
- **API integration**: Uses external services to fetch geolocation data.
- **Docker support**: Includes `Dockerfile` and `docker-compose.yml` for quick setup.
- **Configurable**: Environment variables and API keys (`mykey.txt`) for flexible configuration.
- **Extensible**: Easy to add new commands and features.

 Project Structure
- `Dockerfile` / `docker-compose.yml` → containerization and deployment.
- `src/` → bot source code.
- `package.json` → dependencies and scripts.
- `node_modules/` → auto‑installed dependencies (excluded from GitHub).
- `mykey.txt` → API keys (do not commit to public repos).

 Installation & Run
```bash
# Clone the repository
git clone [https://github.com/trafficit/geo-location-bot.git]
cd <repo>

# Install dependencies
npm install

# Run locally
npm start

# Or run with Docker
docker-compose up -d

p.s. The program shows the location to search for intruders who steal other people's accounts in telegram and ask friends (who are in the phone book) for money. Works with nodejes
