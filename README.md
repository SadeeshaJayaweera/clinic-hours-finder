🏥 Clinic Hours Finder Pro

Extract Clinic Opening Hours With 3 Powerful Intelligent Methods

Each method uses 3 automatic fallback attempts to guarantee the highest success rate when fetching clinic opening hours from the web.

<p align="center"> <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" /> <img src="https://img.shields.io/badge/Node.js-Supported-blue?style=for-the-badge" /> <img src="https://img.shields.io/badge/Scraping-Clinic%20Hours-orange?style=for-the-badge" /> <img src="https://img.shields.io/badge/Mode-3%20Engines-purple?style=for-the-badge" /> </p>
🚀 Start Now

This tool intelligently pulls clinic opening hours using three different scraping/lookup engines, each with three internal strategies.

Maximum accuracy.
Maximum automation.
Minimum manual effort.

🔥 3 Methods × 3 Attempts Each = 9 Chances to Get the Correct Hours
🌐 1. Basic Scraper (FREE)

No API required — scrape using standard search techniques.

Attempt	Description
Attempt 1	Google Search scraping
Attempt 2	Google Maps scraping
Attempt 3	Extract from Official Website
🔑 2. SerpAPI (RECOMMENDED)

Most accurate method — ideal for large datasets (up to thousands of clinics).

Attempt	Description
Attempt 1	Google Search API
Attempt 2	Google Maps API
Attempt 3	Direct structured search
🗺️ 3. Google Places (PREMIUM)

Perfect when you need real-time verified opening hours.

Attempt	Description
Attempt 1	Full Place Search (name + address + keywords)
Attempt 2	Name-only fuzzy search
Attempt 3	Text-Search fallback
📂 How It Works
Clinic Hours Finder Pro
│
├── 3 engines (Basic, SerpAPI, Google Places)
│      └── each engine tries 3 intelligent fallbacks
│
├── Input: CSV file with clinic names
├── Output: JSON with opening hours Mon–Sun
└── Automatic retries + error handling

🛠️ Installation
git clone https://github.com/SadeeshaJayaweera/clinic-hours-finder
cd clinic-hours-finder
npm install

▶️ Usage
Basic Mode (Free — no API keys required)
node app.js --mode=basic --input=clinics.csv --output=result.json

SerpAPI Mode
SERPAPI_KEY=your_key node app.js --mode=serpapi --input=clinics.csv --output=result.json

Google Places Mode
GOOGLE_API_KEY=your_key node app.js --mode=places --input=clinics.csv --output=result.json

📤 Input CSV Format
clinic_name,address
Happy Dental Clinic,Colombo
Sunshine Medical Center,Kandy

📥 Output Example
{
  "clinic": "Happy Dental Clinic",
  "address": "Colombo",
  "hours": {
    "monday": "9:00 AM – 6:00 PM",
    "tuesday": "9:00 AM – 6:00 PM",
    "wednesday": "9:00 AM – 6:00 PM",
    ...
  },
  "source": "SerpAPI → Google Maps API"
}

💡 Why Clinic Hours Finder Pro?

✔ 3 engines with 3 fallback strategies each

✔ Avoid failed lookups

✔ Designed for scale (1–2000+ clinics)

✔ Smart error handling

✔ Accurate hours from verified sources

✔ Perfect for health-tech, apps, directories, delivery services, and more

🤝 Contributions Welcome

Feel free to open issues or submit pull requests to enhance accuracy, add UI, integrate Firebase, or expand scraping logic.

📜 License

MIT — Free to use, modify, and distribute.
