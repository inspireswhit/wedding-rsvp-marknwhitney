# Wedding Date Reservation Form
### July 14, 2026

A custom RSVP form that collects responses directly into a Google Sheet.

## Setup

1. Open `index.html` and find this line near the bottom:
   ```
   const SHEETS_ENDPOINT = '...';
   ```
   Replace the URL with your Google Apps Script Web App URL if needed.

2. Enable GitHub Pages:
   - Go to repository **Settings → Pages**
   - Set branch to **main**
   - Click **Save**

3. Your form will be live at:
   ```
   https://yourusername.github.io/wedding-rsvp
   ```

## Updating the Form

To make changes, simply upload a new `index.html` to this repository and GitHub Pages will update automatically within a minute.

## Google Apps Script

If you ever need to redeploy your Apps Script, use **Deploy → Manage deployments → Edit → New version** to keep the same URL.
