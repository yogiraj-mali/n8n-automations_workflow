# n8n Automation 1: Form to Google Sheets & Gmail

An automated workflow built in **n8n** (`My workflow 2`) to practice node configuration, data flow, and workflow settings.

## Workflow Flow
1. **On form submission (`MY FIRST FORM`)** — Triggers when a user submits the form.
2. **Append row in sheet (`append: sheet`)** — Appends the submitted form data as a new row in Google Sheets.
3. **Send a message (`send: message`)** — Sends a notification email via Gmail.

## How to Use
1. Open your n8n instance.
2. Go to **Menu (`...`) > Import from File** (or paste the JSON).
3. Select the exported `.json` file from this repository.
4. Connect your own **Google Sheets** and **Gmail** credentials and test with **Execute**.
