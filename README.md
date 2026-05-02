# Kcal-Macro-counter
ETHIO•KCAL is a client‑side Ethiopian nutrition analysis tool featuring a search engine, comparison module, and dynamic plate builder. The app is optimized for speed, modularity, and a cinematic Dark Premium UI.
ETHIO•KCAL — Developer Documentation
ETHIO•KCAL is a client‑side Ethiopian nutrition analysis tool featuring a search engine, comparison module, and dynamic plate builder. The app is optimized for speed, modularity, and a cinematic Dark Premium UI.

⚙️ Architecture Overview
ETHIO•KCAL is a fully static web application:

Code
/root
│── index.html          # Main UI + layout structure
│── style.css           # Dark Premium theme, responsive grid, animations
│── script.js           # Core logic (search, compare, plate builder)
│── foods.json          # Nutrition dataset for Ethiopian dishes
└── assets/             # (Optional) images, icons, OG cards, favicon
🧠 Core Modules
1. Search Engine
Filters dishes by name

Returns macro + micronutrient profile

Uses in‑memory JSON for instant lookup

2. Comparison Engine
Side‑by‑side macro comparison

Highlights stronger nutritional values

Auto‑sorts categories

3. Plate Builder
Add/remove dishes

Portion multipliers (0.5x, 1x, 1.5x, etc.)

Real‑time macro totals

Daily calorie progress bar

Export plate as image

4. Health Score Algorithm
Weighted scoring across macros + micros

Outputs a 0–100 rating

🛠️ Tech Stack
Layer	Technology
UI	HTML5, CSS3 (Dark Premium + Ethiopian Gold theme)
Logic	Vanilla JavaScript
Data	JSON dataset
Hosting	GitHub Pages

🚀 Local Development
bash
git clone https://github.com/yourusername/ethiokcal.git
cd ethiokcal
open index.html
No build tools required.

🧩 Extending the App
Add a new dish
Open foods.json

Add a new object with:

name

calories

protein

fat

carbs

fiber

iron

calcium

healthScore

Add new UI components
Add markup in index.html

Style in style.css

Add logic in script.js

Add new analytics
Extend the comparison engine

Add new scoring logic

Update plate builder totals

📌 Roadmap
User accounts + cloud sync

Custom daily goals

Offline mode

AI‑powered meal suggestions

Mobile app version

📜 License
MIT License.
