# Invitationix RSVP

Shows the Smart RSVP page at https://rsvp.invitationix.online without the Google Apps Script banner.

- `/<event-code>` opens the RSVP page
- `/<event-code>?view=table` opens Find my table
- `/<event-code>?view=dashboard&key=...` opens the couple dashboard

To point it at a new Apps Script deployment, change `WEB_APP_URL` in both `index.html` and `404.html`.
