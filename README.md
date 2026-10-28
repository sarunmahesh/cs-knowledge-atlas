# CS Knowledge Atlas — V3

Public, evidence-led Customer Success and CX Enablement research workspace. No Atlas login, paid cloud AI, or API keys required to browse the site or download reusable agent instructions.

## Main features
- Responsive, accessible navigation between Overview, Research Library, Knowledge Explorer, Agent Studio, Expert Network, Contribution Workspace and Evidence Standards.
- Combined source filters, keyword search, sort, reset and original publisher links.
- Interactive department explorer and information handoff descriptions.
- Five portable AI research agent instruction packs generated locally in the browser for ChatGPT, Claude and universal Markdown use.
- Institution-level source registry, clearly distinguished from verified individual SME profiles.
- Local JSON contribution schema validation, template download and voluntary GitHub issue submission.
- Editorial policy and GitHub issue forms for source suggestions and research contributions.

## Deploy
Upload all files and folders to the root of the existing `sarunmahesh/cs-knowledge-atlas` repository, keeping `index.html`, `app.js`, `styles.css`, and `resources.json` at root. Under Settings → Pages use **Deploy from a branch**, `main`, `/(root)`.

Local test: run `python3 -m http.server 8000` in the project directory and open http://localhost:8000/ . Browsers intentionally block JSON fetching from `file://`.

## Editorial boundaries
The starter research records are not all fully reviewed. This edition does **not** run AI research or automatically receive ChatGPT/Claude conversation content. The agent downloads are instruction files, not executable models. A passing local JSON check is not verification. Issue-form submissions need the contributor's existing GitHub account and human editorial review.

## Updating content
- `resources.json`: original-source reference catalogue.
- `data/ecosystem.json`: department descriptions, institution channels and downloadable agent definitions.
- `docs/EDITORIAL.md`: editorial standards.
- `.github/ISSUE_TEMPLATE`: issue intake.

## Future development
Add peer-reviewed research review dossiers, explicit claim–source graph, downloadable validated datasets, scheduled expert-publication monitoring, and an optional read-only AI connector. All such additions require evidence and security review.
