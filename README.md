# DevFlow | Modern Portfolio

A high-performance, responsive single-page portfolio built to showcase modern web development practices. This project (Task 5) focuses on clean UI, optimized asset loading, and dynamic content rendering using Vanilla JavaScript.

## 🚀 Key Features

* **Dynamic Rendering**: Projects are managed via a JavaScript array and injected into the DOM, allowing for easy updates without touching the HTML structure.
* **Performance First**: 
    * **Lazy-Loaded Images**: Uses the native `loading="lazy"` attribute to reduce initial bandwidth.
    * **Optimized Assets**: Integrated with Unsplash source parameters for fast, responsive image delivery.
* **Modern CSS Architecture**: 
    * **CSS Variables**: Centralized color palette for easy branding changes.
    * **CSS Grid & Flexbox**: A hybrid layout approach for maximum responsiveness.
    * **Sticky Navigation**: Smooth, persistent header for better UX.
* **Functional Contact Form**: Includes JavaScript-driven validation and submission handling.

---

## 🛠️ Technology Stack

| Feature | Technology |
| :--- | :--- |
| **Markup** | HTML5 (Semantic) |
| **Styling** | CSS3 (Grid, Flexbox, Variables) |
| **Logic** | JavaScript (ES6+) |
| **Assets** | Unsplash Image API |

---

## 📁 File Structure

The project is contained within a single optimized file for ease of portability:

- **`index.html`**: Contains the semantic structure.
- **`<style>`**: Custom CSS including mobile-first media queries.
- **`<script>`**: Dynamic project rendering engine and form event listeners.

---

## ⚙️ How to Customize

1.  **Change Branding**: Update the `--primary` hex code in the `:root` CSS selector to match your personal brand.
2.  **Add Projects**: Locate the `projectData` array in the JavaScript section. Add a new object with a `title`, `desc`, and `img` URL:
    ```javascript
    {
        title: "Your Project Name",
        desc: "A brief description of what you built.",
        img: "your-image-url.jpg"
    }
    ```
3.  **Update Logo**: Search for the class `.logo` in the HTML and change "DevFlow" to your name.

---

## 📱 Responsiveness
The layout is designed to be "Fluid-First":
- **Desktop**: 3-column project grid with hover animations.
- **Tablet**: 2-column project grid.
- **Mobile**: Single-column stack with an optimized touch-friendly contact form.

---

## ⚖️ License
This project is open-source and available under the **MIT License**.
