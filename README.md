# Creatine Monohydrate Dose Guide

Static educational site for discussing common creatine monohydrate dosing ranges in a muscle-preservation context.

Live entry point: `index.html`.

## Project purpose
This project provides a polished, plain-language educational calculator for common creatine monohydrate dosing frameworks:
- simple maintenance (3–5 g/day)
- weight-based estimate (0.1 g/kg/day)
- optional loading estimate (0.3 g/kg/day for 5–7 days), then maintenance

Core framing in the site:
- creatine is an add-on, not the foundation
- resistance training is the primary muscle-preservation signal
- protein supports the training response
- creatine does not replace lifting, protein, hydration, adequate intake, or clinician-guided care

## Educational-only disclaimer
This site is for education only and is not individualized medical advice. It does not diagnose, treat, or determine an “optimal” dose for any individual.

## Calculator options
1. **Simple maintenance**
   - Presents common maintenance range: 3–5 g/day.
   - Notes timing usually matters less than consistency.

2. **Weight-based estimate**
   - Accepts body weight in lb or kg.
   - Converts and displays kg value.
   - Calculates 0.1 g/kg/day.
   - Includes practical context that many adults use 3–5 g/day.

3. **Optional loading**
   - Accepts body weight in lb or kg.
   - Calculates 0.3 g/kg/day.
   - Presents split dosing over 5–7 days, then 3–5 g/day maintenance.
   - Notes loading is optional and may increase GI symptoms or short-term water-weight change.

## Local preview
Because this is a static site, you can preview in several ways.

### Option A: open directly
Open `index.html` in a browser.

### Option B: run a local static server
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

## Deployment

### GitHub Pages
1. Push this repository to GitHub.
2. In **Settings → Pages**, set:
   - Source: **Deploy from a branch**
   - Branch: `main` (or preferred branch), folder `/ (root)`
3. Save and wait for deployment.

### Netlify
This repo includes `netlify.toml` for static hosting.
- Build command: *(leave blank)*
- Publish directory: `.`

## Limitations
- Educational calculator only; no personalization beyond simple arithmetic.
- No clinical screening logic beyond visible caution prompts.
- No claims of individualized efficacy or safety.

## Source/citation notes
- References are listed on-page and retained from the prior version.
- Language is intentionally conservative to avoid overclaiming unsupported outcomes.
- If reference scope is expanded in future, verify article alignment first.

## License
MIT License. See [LICENSE](LICENSE).
