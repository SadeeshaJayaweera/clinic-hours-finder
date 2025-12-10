<div align="center">

<h1>🏥 <strong>Clinic Hours Finder Pro</strong></h1>
<h3>Extract Clinic Opening Hours With 3 Intelligent, Auto-Fallback Methods</h3>

<br>

<a href="#start-now">
  <img src="https://img.shields.io/badge/Click_To_Start-Clinic%20Hours%20Finder%20Pro-blue?style=for-the-badge" />
</a>

<br><br>

<img src="https://img.shields.io/badge/3_Methods-9_Total_Attempts-success?style=for-the-badge">
<img src="https://img.shields.io/badge/Accuracy-High-green?style=for-the-badge">
<img src="https://img.shields.io/badge/Scraping-Automated-orange?style=for-the-badge">

</div>

---

<style>
/* Highlight boxes */
.feature-box {
  padding: 15px;
  border-radius: 12px;
  margin-bottom: 15px;
  border: 1px solid #d1d1d1;
}

.method-title {
  font-size: 22px;
  font-weight: bold;
}

.attempt-list li {
  margin-bottom: 6px;
}

.start-button {
  background: #007bff;
  color: white !important;
  padding: 12px 22px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
}

.start-button:hover {
  background: #0056d6;
}
</style>

---

<div id="start-now"></div>

# 🚀 Start Now
Click any method to expand:

---

<details>
<summary><h2>🌐 Basic Scraper (FREE)</h2></summary>
<div class="feature-box">

<p class="method-title">Free mode – No API required</p>

<ul class="attempt-list">
  <li>✓ <strong>Attempt 1:</strong> Google Search scraping</li>
  <li>✓ <strong>Attempt 2:</strong> Google Maps scraping</li>
  <li>✓ <strong>Attempt 3:</strong> Official Website extraction</li>
</ul>

</div>
</details>

---

<details>
<summary><h2>🔑 SerpAPI (RECOMMENDED)</h2></summary>
<div class="feature-box">

<p class="method-title">Highest accuracy using SerpAPI</p>

<ul class="attempt-list">
  <li>✓ <strong>Attempt 1:</strong> Google Search API</li>
  <li>✓ <strong>Attempt 2:</strong> Google Maps API</li>
  <li>✓ <strong>Attempt 3:</strong> Direct structured search</li>
</ul>

</div>
</details>

---

<details>
<summary><h2>🗺️ Google Places (PREMIUM)</h2></summary>
<div class="feature-box">

<p class="method-title">Real-time business info from Google</p>

<ul class="attempt-list">
  <li>✓ <strong>Attempt 1:</strong> Full Search (name + address)</li>
  <li>✓ <strong>Attempt 2:</strong> Name-only fuzzy search</li>
  <li>✓ <strong>Attempt 3:</strong> Text-search fallback</li>
</ul>

</div>
</details>

---

# 🖼️ Screenshots

<div align="center">

<img src="https://raw.githubusercontent.com/SadeeshaJayaweera/clinic-hours-finder/main/screenshots/screen1.png" width="80%" alt="Screenshot 1">

<br><br>

<img src="https://raw.githubusercontent.com/SadeeshaJayaweera/clinic-hours-finder/main/screenshots/screen2.png" width="80%" alt="Screenshot 2">

<br><br>

<img src="https://raw.githubusercontent.com/SadeeshaJayaweera/clinic-hours-finder/main/screenshots/screen3.png" width="80%" alt="Screenshot 3">

</div>

---

# 📂 How It Works

```text
Clinic Hours Finder Pro
│
├── 3 engines (Basic, SerpAPI, Google Places)
│      └── each engine attempts 3 fallback strategies
│
├── Input: CSV file with clinic names
└── Output: JSON with accurate opening hours
🛠️ Installation
git clone https://github.com/SadeeshaJayaweera/clinic-hours-finder
cd clinic-hours-finder
npm install

▶️ Usage
Basic Mode (Free)
node app.js --mode=basic --input=clinics.csv --output=result.json

SerpAPI Mode
SERPAPI_KEY=your_key node app.js --mode=serpapi --input=clinics.csv --output=result.json

Google Places Mode
GOOGLE_API_KEY=your_key node app.js --mode=places --input=clinics.csv --output=result.json

📥 Output Example
{
  "clinic": "Happy Dental Clinic",
  "address": "Colombo",
  "hours": {
    "monday": "9:00 AM – 6:00 PM",
    "tuesday": "9:00 AM – 6:00 PM"
  },
  "source": "SerpAPI → Google Maps API"
}

🤝 Contributing

PRs & feature suggestions are welcome!

📜 License

MIT License — free for personal & commercial use.

<div align="center"><h3>Made with ❤️ by Sadeesha</h3></div> ```
