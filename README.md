# Growmodo Real Estate – Custom WordPress Theme

A custom WordPress theme developed for the Growmodo technical challenge.  
The project includes a dynamic homepage, custom post types, ACF fields, responsive layouts, and a properties carousel powered by Swiper.js.

---

## 🚀 Features

- Custom WordPress Theme (no starter theme)
- Custom Post Type: **Properties**
- Dynamic sections connected to ACF fields
- Fully responsive layout (mobile-first)
- Featured Properties carousel with Swiper.js
- Custom navigation menus (Header + Footer)
- Figma design faithfully implemented
- Clean, organized file structure

---

## 📂 Theme Structure

```
/growmodo-theme
│── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
│── templates/
│── functions.php
│── style.css
│── index.php
│── single-property.php
│── archive-property.php
```

---

## 🧩 Plugins Used

- **Advanced Custom Fields (ACF)** – Field groups for property details
- **Swiper.js** – Carousel for Featured Properties

---

## ⚙️ Installation

1. Download or clone this repository into your `wp-content/themes/` directory:
   ```
   git clone https://github.com/your-repo-url/growmodo-theme.git
   ```

2. Activate the theme in **WordPress Dashboard → Appearance → Themes**.

3. Install required plugins:
   - ACF (free)

4. Go to **Custom Fields → Field Groups**  
   The "Property Info" field group loads automatically (registered via PHP).

5. Start creating properties under **Properties → Add New**.

---

## ▶️ Demo

If hosted publicly, add the URL here:

**Live Demo:** _coming soon_

If local, include instructions to run via LocalWP, XAMPP, or Docker.

---

## 🛠️ Development Notes

- Built from scratch without a theme builder.
- CSS is minimal and modular.
- ACF fields registered programmatically in `functions.php`.
- Swiper initialized with breakpoints for responsive behavior.
- Theme optimized for speed and clean code.

---

## ✍️ Author

Developed as part of the Growmodo Technical Trial.  
Created by **[Your Name]**.

