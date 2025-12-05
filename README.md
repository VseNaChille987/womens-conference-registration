# Church Women's Conference Registration

This project hosts the registration form for the Church Women's Conference.

## Features
- Handles registrations and questions.
- Sends HTML email confirmation for registrations.
- Works on localhost, GitHub Pages, or any HTTPS host.
- Uses fetch with text/plain to avoid CORS issues.

## Setup
1. Create a new Google Spreadsheet.
2. Set up two sheets: 'Registrations' and 'Questions'.
3. Open Google Apps Script, paste the provided Code.gs, replace 'YOUR_SPREADSHEET_ID' with your spreadsheet ID.
4. Deploy the script as a web app (Anyone, even anonymous).
5. Update SCRIPT_URL in index.html with your web app URL.
6. Upload this project to GitHub or serve locally.
