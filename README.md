# app-legal

Privacy policies, terms, and support pages for Donovan Hiland's mobile apps.
GitHub Pages serves this repo at https://legal.donovanhiland.com.

## Layout

One folder per app. Each folder has `privacy.html`, `terms.html`, and `support.html`.
Pages load `/style.css`. List each app in `index.html`.

| App | Privacy | Terms | Support |
|---|---|---|---|
| Plain Macros | `/plain-macros/privacy` | `/plain-macros/terms` | `/plain-macros/support` |

## Add an app

1. Copy `plain-macros/` to `<app-slug>/`.
2. Change the app name, the data list, the services, and the contact email.
3. Add the app to `index.html` and to the table above.

Keep each privacy page true to what the app collects. Update it, and its date,
when the app starts to collect new data or uses a new service.
