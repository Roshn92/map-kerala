# 🗺️ Interactive Region Map

This project is an **interactive map web app** built with HTML, CSS, and JavaScript.  
It allows users to click on regions of a map to mark where they’ve *lived*, *visited*, *stayed*, etc., and automatically calculate a score based on points assigned to each category.

---

## 🚀 Features

- Click regions to **cycle through statuses** (e.g. Lived Here → Stayed Here → …)
- Each status has its own **color and point value**
- **Live score counter**
- **Export / Import** your data as JSON
- Works entirely offline (pure HTML, CSS, JS — no backend)

---

## 🧩 Files

| File | Description |
|------|--------------|
| `index.html` | Main web app (interactive map and logic) |
| `map.png` | The map image used for the visualization |

---

## 🛠️ How to Use

1. Clone or download this repository  
2. Open `index.html` in any web browser  
3. Click on any map region to change its color and status  
4. Use the **Export JSON** button to save your progress  
5. Use the **Import JSON** button to load your saved progress

---

## 🌐 Host on GitHub Pages

You can publish this map online easily:

1. Go to your repo’s **Settings → Pages**  
2. Under **Source**, select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
3. Click **Save**  
4. After a few moments, your map will be live at  
   `https://<your-username>.github.io/<repo-name>/`

---

## 🧠 Customizing the Map

- Edit the `regions` array inside `index.html` to define polygons that match your map layout.
- Each polygon defines a clickable region using coordinate points (`x1,y1,x2,y2,...`).
- The color and score logic are handled automatically by the script.

---

## 🖋️ Credits

Created using plain HTML, CSS, and JavaScript.  
Inspired by the **US Level Map** project by [tenpages](https://tenpages.github.io/us-level/us.html).

---

⭐ **Tip:** Fork and personalize this project for your own world, country, or city map!
