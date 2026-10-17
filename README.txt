VUKRAX Transport — Telegram Mini App starter

index.html — responsive order form in Russian/Serbian/English.
Features: pickup, intermediate stops, destination, date/time, cargo, dimensions, weight, loading/unloading, contact details, route distance estimate via public Nominatim/OSRM, Telegram.WebApp.sendData() JSON payload.

Important:
- The existing Telegram bot must be updated to receive and validate WebAppData. This front end alone does not modify bot.py.
- The selected photo is not uploaded yet. A backend/bot file-upload flow is needed.
- The page shows route distance, not a price. Authoritative price should be calculated by the bot/backend using current settings.
- Public Nominatim/OSRM endpoints have usage limits and are not a production guarantee.
- Never put the Telegram bot token in this HTML.
- Deploy index.html to HTTPS (for example GitHub Pages), then configure the bot's Web App button to use that URL.
- Keep settings.json and applications.csv unchanged until the backend integration is tested.
