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
## How It Works

1. **Form Submission (`On form submission` — `MY FIRST FORM`)**
   - When a user fills and submits `MY FIRST FORM`, this trigger node starts the workflow.
   - All data entered in the form fields is collected and passed forward to the next step.

2. **Append Row to Google Sheets (`Append row in sheet` — `append: sheet`)**
   - Takes the form data received from the previous node.
   - Adds a new row into the connected Google Sheet so every submission is recorded neatly.

3. **Send Notification via Gmail (`Send a message` — `send: message`)**
   - Runs after the row is added to Google Sheets.
   - Sends an email message/notification via Gmail using details from the workflow.




