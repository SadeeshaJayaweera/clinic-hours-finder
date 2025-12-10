<div style="font-family: Arial, sans-serif; line-height: 1.6;">

    <!-- HEADER -->
    <h1 align="center" style="font-size: 40px; margin-bottom: 10px;">
        🏥 Clinic Hours Finder Pro
    </h1>

    <p align="center" style="font-size: 18px;">
        <strong>Extract opening hours from any clinic — using three powerful scraping methods.</strong><br>
        Smart fallback system → 3 attempts per method → Maximum success rate.
    </p>

    <div align="center" style="margin-top: 15px;">
        <img src="https://raw.githubusercontent.com/SadeeshaJayaweera/clinic-hours-finder/main/screenshots/app-preview.png"
             alt="App Preview" width="80%" style="border-radius: 10px; box-shadow: 0 0 8px rgba(0,0,0,0.2);">
    </div>

    <br><br>

    <!-- QUICK START -->
    <h2>🚀 Start Now</h2>
    <p>Choose from 3 powerful scraping modes — each performing 3 automated fallback attempts.</p>

    <table style="width: 100%; border-collapse: collapse;">
        <tr>
            <td style="width: 33%; vertical-align: top; padding: 10px; border: 1px solid #ddd;">
                <h3>🌐 Basic Scraper – <span style="color: green;">FREE</span></h3>
                <ul>
                    <li>✓ Attempt 1: Google Search</li>
                    <li>✓ Attempt 2: Google Maps</li>
                    <li>✓ Attempt 3: Official Website</li>
                </ul>
            </td>

            <td style="width: 33%; vertical-align: top; padding: 10px; border: 1px solid #ddd;">
                <h3>🔑 SerpAPI – <span style="color: orange;">RECOMMENDED</span></h3>
                <ul>
                    <li>✓ Attempt 1: Google Search API</li>
                    <li>✓ Attempt 2: Google Maps API</li>
                    <li>✓ Attempt 3: Direct Search (JSON fallback)</li>
                </ul>
            </td>

            <td style="width: 33%; vertical-align: top; padding: 10px; border: 1px solid #ddd;">
                <h3>🗺️ Google Places – <span style="color: blue;">PREMIUM</span></h3>
                <ul>
                    <li>✓ Attempt 1: Full Search</li>
                    <li>✓ Attempt 2: Name Only Search</li>
                    <li>✓ Attempt 3: Text Search</li>
                </ul>
            </td>
        </tr>
    </table>

    <br><br>

    <!-- FEATURES -->
    <h2>✨ Features</h2>

    <ul>
        <li>✔ Three extraction modes (Basic, SerpAPI, Google Places)</li>
        <li>✔ Automatic fallback system (9 attempts total)</li>
        <li>✔ Clean UI + real-time status updates</li>
        <li>✔ CSV import for batch clinic lists</li>
        <li>✔ JSON output for integrations</li>
        <li>✔ Built-in error handling + rate-limit protection</li>
        <li>✔ Proxy switching for Basic scraper</li>
    </ul>

    <br>

    <!-- HOW IT WORKS -->
    <h2>🔧 How It Works</h2>

    <ol>
        <li>Upload CSV containing clinic names + locations.</li>
        <li>Choose scraping mode.</li>
        <li>App performs 3 attempts per method.</li>
        <li>Hours are extracted & formatted into JSON.</li>
        <li>Export or download the final dataset.</li>
    </ol>

    <br>

    <!-- SCREENSHOTS -->
    <h2>🖼️ Screenshots</h2>

    <div>
        <h3>Landing Page</h3>
        <img src="https://raw.githubusercontent.com/SadeeshaJayaweera/clinic-hours-finder/main/screenshots/landing.png"
             alt="Landing Screenshot" width="100%" style="border-radius: 10px;">

        <h3>Main Dashboard</h3>
        <img src="https://raw.githubusercontent.com/SadeeshaJayaweera/clinic-hours-finder/main/screenshots/dashboard.png"
             alt="Dashboard Screenshot" width="100%" style="border-radius: 10px;">

        <h3>Extraction Output</h3>
        <img src="https://raw.githubusercontent.com/SadeeshaJayaweera/clinic-hours-finder/main/screenshots/output.png"
             alt="Output Screenshot" width="100%" style="border-radius: 10px;">
    </div>

    <br><br>

    <!-- SETUP -->
    <h2>⚙️ Installation & Setup</h2>

```bash
git clone https://github.com/SadeeshaJayaweera/clinic-hours-finder
cd clinic-hours-finder
npm install
npm start

<p><strong>Optional:</strong> Add your API keys to <code>.env</code></p>

SERPAPI_KEY=your_key_here
GOOGLE_PLACES_KEY=your_key_here
<br>

<!-- CSV STRUCTURE -->
<h2>📄 CSV Structure</h2>

<br>

<!-- OUTPUT FORMAT -->
<h2>📦 Output Example (JSON)</h2>

{
  "clinic": "ABC Dental Clinic",
  "monday": "8:00 AM – 5:00 PM",
  "tuesday": "8:00 AM – 5:00 PM",
  "wednesday": "8:00 AM – 5:00 PM"
}

<br>

<!-- CONTRIBUTING -->
<h2>🤝 Contributing</h2>
<p>Pull requests are welcome!</p>

<!-- FOOTER -->
<hr>
<p align="center">Built with ❤️ by <strong>Sadeesha Jayaweera</strong></p>


