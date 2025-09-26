# WED5112_Part-2

# Ocean Delights - Seafood Restaurant Website

## Project Overview
This project is a simple **2-page seafood restaurant website** created using **HTML and CSS**.  
It demonstrates basic web development concepts such as navigation, images, lists, and styling.

The website contains:
- **index.html**: A food menu with categorized items (Appetizers, Main Dishes, Beverages).
- **gallery.html**: A gallery showcasing seafood dish images.
- **style.css**: A stylesheet that controls the look and feel of both pages.
- **images/**: A folder containing the logo and dish images.

---

## How the Website Was Created

1. **HTML Structure**
   - The project includes two pages (`index.html` and `gallery.html`).
   - Each page has a **header** with a logo and navigation links, a **main** section for content, and a **footer**.
   - The menu (`index.html`) uses HTML lists (`<ul>` and `<li>`) to organize food items into categories.
   - The gallery (`gallery.html`) uses the `<img>` tag to display seafood images inside a grid layout.

2. **Images**
   - All images (logo, dishes) are stored in the `images/` folder.
   - Example: `images/logo.png`, `images/Garlic-Butter-Shrimp-recipe.jpg`

3. **Navigation**
   - Both pages include a navigation bar (`<nav>`) that links to **Menu** and **Gallery**.
   - This allows users to move between pages easily.

---

## How the Styling Works

All styles are defined in **style.css**, which is linked in the `<head>` section of both HTML pages.

```html
<link rel="stylesheet" href="style.css">
```

### Main Styling Features

1. **Global Styles**
   - Sets a light blue background (`#e6f7ff`) for the entire site.
   - Uses a clean sans-serif font (`Arial, sans-serif`).

2. **Header**
   - Contains the logo and website title.
   - Uses a blue background (`#0077b6`) with white text.
   - Navigation links are aligned to the right with hover underline effects.

3. **Main Content**
   - Content is centered (`max-width: 900px; margin: auto;`).
   - White background boxes with rounded corners and subtle shadows improve readability.
   - Section headings (`<h2>`) have bottom borders for separation.

4. **Lists**
   - Food menu items use standard bullet points (`disc`) with padding for neat alignment.

5. **Gallery**
   - Images are displayed in a **responsive grid layout** using CSS Grid.
   - Each image is resized with `object-fit: cover` to keep proportions without distortion.
   - Rounded corners add a polished look.

6. **Footer**
   - Simple blue footer with centered white text.

---

## Folder Structure

```
OceanDelights/
│
├── index.html        # Food menu page
├── gallery.html      # Gallery page with images
├── style.css         # Stylesheet for both pages
├── images/           # Logo + food images
│   ├── logo.png
│   ├── Garlic-Butter-Shrimp-recipe.jpg
│   ├── Grilled-Salmon.jpg
│   ├── Crab-Cakes.jpg
│   └── Seafood-Platter.jpg
└── README.md         # Documentation
```

---

## How to Use
1. Download and extract the project folder.
2. Open `index.html` in your browser to view the menu page.
3. Use the navigation bar to switch between **Menu** and **Gallery**.

---

## Customization
- **Colors**: Modify `style.css` to change background or text colors.
- **Menu Items**: Edit `index.html` to add or remove dishes.
- **Gallery**: Add new images to the `images/` folder and update `gallery.html`.
