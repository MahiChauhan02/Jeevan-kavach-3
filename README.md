# Jeevan Kavach — Flask Website

A local prototype for medicine routine tracking, built with Flask and SQLite.

## Run on macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -r requirements.txt
python3 app.py
```

Open `http://127.0.0.1:5000` in your browser. Keep the terminal running while you use the site.

## Included

- Dashboard, medicine cabinet (add/edit/delete), dose history and CSV export
- Taken/Missed tracking, stock count, low-stock information and follow-up alerts
- Updated teal/green healthcare theme and responsive layout
- Elder-friendly mode with larger text and controls (setting is saved in the browser)
- Language selector with interface labels translated for English, Hindi, Punjabi, Bengali, Tamil, Telugu, Marathi, Gujarati and Urdu. Some detailed page content remains in English in this prototype.
- Smart Care Tools page with browser voice test, packaging-photo preview, reminder-permission control, missed-dose follow-up and report shortcuts
- Browser reminder check while the dashboard is open and notification permission has been granted

## Important limitations

- Browser reminders are not guaranteed alarms and do not run after the browser/page is closed. Reliable background/mobile notifications need a proper push-notification service or native app integration.
- The packaging-photo feature only previews an image; it does not identify a medicine. Do not rely on a photo or this prototype to identify pills.
- AI risk and pattern-clustering pages are explanatory prototypes/links to recorded data, not validated clinical prediction models. Do not use them for diagnosis or treatment decisions.
- No authentication or production security hardening is included. Do not expose this prototype publicly with real patient information without security, privacy, and clinical review.
- Data is stored in `jeevan_kavach.db` inside the project folder. Back it up before replacing project files.
