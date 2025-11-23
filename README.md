# PUBG Pro Stats Analyzer

A lightweight, browser-based tool to visualize PlayerUnknown's Battlegrounds (PUBG) match statistics. This tool allows you to parse raw JSON data, fetch match history via the PUBG API, and view detailed player stats in a sortable, interactive table.

## 🚀 Features

*   **Player Search:** Find players by nickname and retrieve their recent match history.
*   **Match Visualizer:** View detailed statistics for every player in a specific match (Kills, Damage, Distance, Revives, etc.).
*   **Data Sorting:** Click any column header to sort stats (Ascending/Descending).
*   **Dual Input Methods:** 
    *   Fetch directly via PUBG API (requires API Key).
    *   Upload local `.json` telemetry/match files.
*   **Responsive UI:** Dark-themed, sticky headers for easy reading of large datasets.

## 🛠️ Installation & Usage

Since this is a client-side application (HTML/JS), you don't need to install Node.js or Python.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/frontez/pubgstats.git
    ```
2.  **Open the file:**
    Simply double-click `PUBG Stats.html` (or `index.html`) to open it in your web browser.

## 🔑 API Key Configuration

To use the **Player Search** and **URL Fetch** features, you need a PUBG API Key.

1.  Go to the [PUBG Developer Portal](https://developer.pubg.com/).
2.  Register and create an App to get your **Bearer Token** (API Key).
3.  Paste the key into the "Bearer API Key" field in the tool.

## ⚠️ Important Note on CORS

The PUBG API blocks requests coming directly from a browser (Cross-Origin Resource Sharing). 

If you are running this file locally (e.g., `file:///C:/...`), **the API requests will likely fail** unless you:
1.  Install a "Allow CORS" extension for your browser (for testing purposes).
2.  **OR** host this behind a simple proxy server.

*Note: The "Upload JSON File" feature works perfectly without an API key or CORS extensions.*

## 📸 Screenshots



## 📄 License

This project is open-source and available under the MIT License.
