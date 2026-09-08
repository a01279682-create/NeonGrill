Files added on branch enhance/interactive-site:

script.js — menu data, rendering, filters, cart interactivity, localStorage persistence
assets/logo.svg — placeholder logo so the page renders with an image
index.html — small accessibility additions and wiring to script.js
style.css — design tokens + styles (existing in repo)
Preview locally:

git clone https://github.com/a01279682-create/NeonGrill.git
cd NeonGrill
git fetch origin
git checkout enhance/interactive-site
python -m http.server 8000
Open http://localhost:8000/index.html
