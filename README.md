# Starium Rafa Quality Control Tool 🏭

A specialized utility application built for the Quality Control (QC) team at Starium Rafa Detergent Manufacturing. This tool streamlines the process of verifying detergent powder densities and determining machine silo compatibility on the factory floor.

## 🎯 Key Features

### 1. Level 9 Silo Densities (Machine Lookup)
- **Smart Lookup:** Takes powder weight input and calculates density.
- **Machine Compatibility:** Automatically filters and displays which of the 30+ packaging machines (Lines 1A - 3B) can accept the current powder batch based on specific gram settings (22g, 45g, 85g, 125g, 850g).
- **Interactive Interface:** Clickable machine buttons display detailed configuration data (Line Number, Gramage, Allowed Density Range).

### 2. BOT (Base of Tower) Densities
- **Quality Assurance:** Instantly validates if powder coming from the tower meets the required specifications.
- **Visual Alerts:**
  - 🟢 **Green:** Density OK.
  - 🔴 **Pulsing Red:** Density Too Low (< 0.250) or Too High (> 0.270).

### 3. User Experience (UX)
- **Single-File Architecture:** The entire app lives in one `index.html` file. No servers, installations, or internet connection required.
- **Factory-First Design:** High-contrast Dark Mode designed to reduce eye strain for factory workers.
- **Responsive:** Works seamlessly on desktop computers, manufacturing control panels, and mobile tablets.

## 🛠️ Tech Stack
- **HTML5:** Semantic structure.
- **CSS3:** Custom animations, Flexbox/Grid layouts, and responsive design variables.
- **Vanilla JavaScript:** Fast, lightweight logic with embedded CSV data parsing (no external dependencies).

## 🚀 How to Use
1. Download the `starium_qc_tool.html` file.
2. Double-click to open it in any modern web browser (Chrome, Edge, Firefox).
3. Select your mode (Level 9 or BOT) and enter a weight value to get instant results.

---
*© 2026 Dammie Optimus Solutions*
