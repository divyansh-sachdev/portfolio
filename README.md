# Portfolio

Source for [divyansh-sachdev.github.io/portfolio](https://divyansh-sachdev.github.io/portfolio/) — the personal site for Divyansh Sachdev (AI + Robotics engineer, Founder @ Shunya, Frontend Engineer @ Paysecure).

Single-page static site: competition record, tech stack, AI/hardware project grid, publications, experience timeline and contact.

## Structure

| Path | Purpose |
| :--- | :--- |
| `index.html` | The entire site — markup, styles and JS in one file |
| `assets/` | Images |

## Local development

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080>. No build step or dependencies.

## Deployment

Served directly via GitHub Pages from the `main` branch root. Any push to `main` updates the live
site automatically.
