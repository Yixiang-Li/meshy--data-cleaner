Meshy Review Data Cleaner (Team Edition)

Automated data processing & AI analysis tool for Meshy user reviews.

This tool is designed to streamline the workflow of processing user reviews exported from platforms like G2. It cleans the data, formats it into a standardized structure, and uses Google Gemini AI to analyze user intent and generate strategic insights.


✨ Key Features 

⚡ Zero Installation: Single HTML file application. Runs entirely in your browser. No Python or server setup required.

🧹 Smart Data Cleaning: Automatically maps headers, fixes date formats, and structures raw Excel/CSV exports.

🤖 AI-Powered Categorization:

Uses Gemini AI to analyze review content (Likes, Dislikes, Benefits) and categorize users into specific segments (e.g., 3d-printing, game-development, education).

Includes a Local Keyword Fallback mode for fast, offline analysis.

📊 Deep Insight Reports: Generates professional analysis reports on user personas, pain points, and strategic suggestions with one click.

📧 Smart Reply Assistant: Automatically drafts empathetic and professional email replies to specific user reviews.

🌍 Encoding Fix: Built-in support for both UTF-8 and GBK encodings to prevent garbled text (Chinese characters) in CSV files.

🚀 How to Use 

1. Upload Data

Click the upload area to select your raw .xlsx or .csv file (exported from G2 or other review platforms).

Tip: If the preview text looks like messy codes (乱码), switch the encoding dropdown to "Chinese (GBK)".

2. Configure AI (Recommended)

To unlock the full power of the tool:

Check the "Enable Gemini AI" box.

Enter your Google Gemini API Key.

Note: The key is safely stored in your browser's local storage, so you don't need to enter it every time.

3. Process & Analyze

Click "Start Processing". The tool will:

Format dates and columns.

Analyze user intent ("Used For" column).

Generate a clean preview table.

4. Export & Report

Export: Click "Download Excel" to get the final cleaned file.

Report: Click "✨ Generate Deep Insight Report" for a summary.

Reply: Click the "✨ Reply" button on any row to draft an email response.

🔒 Data Privacy & Security

Client-Side Processing: All data processing happens locally in your browser. Your Excel files are never uploaded to our servers.

API Usage: If AI features are enabled, only the text content of reviews is sent to Google Gemini for analysis.

Key Storage: Your API Key is stored locally on your device (localStorage) and is never shared.

🛠 Tech Stack

HTML5 / Tailwind CSS

React.js (via CDN)

SheetJS (xlsx) for Excel processing

Google Gemini API
