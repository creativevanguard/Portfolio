# Dhanu — Portfolio

A one-page animated portfolio, hosted free on GitHub Pages and edited through Pages CMS.

- **Live site:** https://creativevanguard.github.io/Portfolio/
- **Edit content:** https://app.pagescms.org

## Editing your content (no code)

1. Go to **app.pagescms.org** and sign in with GitHub (creativevanguard).
2. Install the Pages CMS GitHub App when asked, and give it access to the **Portfolio** repository.
3. Open **Portfolio** and choose **Portfolio content**.
4. Edit anything (name, headline, photos, About text, contact links or projects), then press **Save**.
5. The live site updates by itself, usually within 1–2 minutes. Refresh the page to see it.

### Adding a project
Projects → **Add an entry** → fill in the title, subtitle, year and category, upload a **cover image** (landscape, around 1800 × 1200) and optional gallery images → Save.
Drag projects to change their order. Categories decide the filter buttons on the Portfolio page.

### Photos
- **Home page photo:** a wide, landscape photo of you. If this is left empty, the illustrated room is shown.
- **Portrait (About page):** a head-and-shoulders photo with your face centred. It's turned into the moving particle portrait.

Uploaded images are stored in the `images/` folder.

## Files
| File | What it is |
|---|---|
| `index.html` | The website: design, animations and code |
| `content/site.json` | All your text, projects and image paths (this is what the CMS edits) |
| `images/` | Uploaded photos and project images |
| `.pages.yml` | Tells Pages CMS what fields to show |

## Contact form
The "write a letter" contact page opens the visitor's email app with the letter already written and addressed to the email you set. It can be connected to a form service later so letters arrive straight in your inbox.
