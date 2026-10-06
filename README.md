# kindergarten-practice
K3-learning and practice. Includes English, mathematics, Chinese, vocabulary, and sentence practice.

Run locally in a browser:
- Open `index.html` directly in the browser, or
- Start a local static server: `python -m http.server 8000` and visit `http://localhost:8000`

The page includes a built-in quiz fallback so it still works when opened from a local file, while the JSON file remains available for the servered version.

The month selector loads the September or October assessment bank from `quiz-data.json`. Keep `quiz-data-embedded.js` in sync when updating the banks so the local-file fallback works. Study progress, mistakes, and storybook unlocks are stored separately under `september_kindergarten_study_data` and `october_kindergarten_study_data`.
