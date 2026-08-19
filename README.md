# Happy Birthday Website 🎉

A beautifully designed, interactive static website created to celebrate a special birthday. The site features smooth animations, elegant custom typography, and a responsive layout that creates a memorable experience.

## 🛠️ How It Was Created (Workflow)

This project is built as a pure, lightweight frontend application without the need for complex frameworks or build tools.

*   **Structure:** Standard HTML5 (`index.html`) is used for the semantic layout and content structuring.
*   **Styling:** Pure CSS3 (`style.css`) handles all visual aspects. It utilizes Flexbox and CSS Grid for positioning, and CSS keyframes for delightful micro-animations and transitions.
*   **Typography & Icons:** 
    *   Integrates multiple elegant Google Fonts (like *Dancing Script*, *Poppins*, *Titan One*, etc.) for a festive, handwriting-style aesthetic.
    *   Uses FontAwesome via CDN for scalable vector icons.
*   **Interactivity:** A small snippet of jQuery is included to help handle any simple interactions or transitions smoothly.

## 🚀 How to Run the Website

Since this is a static website, you do not need to install complex dependencies like Node.js packages (`npm install`).

**Option 1: Quickest Way**
Simply navigate to the project folder and double-click the `index.html` file. It will instantly open and run perfectly in your default web browser (Chrome, Edge, Safari, etc.).

**Option 2: Using a Local Server (Recommended for development)**
If you are making changes and want to serve the site locally, you can use a basic HTTP server. Open your terminal in the project directory and run:

```bash
# If you have Node.js installed:
npx serve

# OR, if you have Python installed:
python -m http.server
```
Then, open the provided `localhost` link in your browser.

## ✏️ How to Customize

You can easily repurpose this template for anyone:
1.  **Text:** Open `index.html` in any code editor (like VS Code) and search for placeholder texts or names to replace them with your own custom messages.
2.  **Images:** Navigate to the `images/` folder and replace the existing placeholder photos with the birthday person's photos. Keep the file names the same, or update the `src` attribute paths in `index.html` to point to your new image files.
3.  **Colors/Fonts:** Tweak variables or specific classes in `style.css` if you wish to change the color theme or font sizing.
