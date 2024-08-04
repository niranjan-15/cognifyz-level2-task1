# cognifyz-level2-task1

# Bulma Card Component

## Overview
This README provides instructions and information about using and customizing the card component in Bulma, a modern CSS framework based on Flexbox. Bulma's card component is a flexible and extensible container for various types of content such as text, images, and media. It is designed to be simple, responsive, and easy to customize.

## Features
- **Responsive Design:** Adapts to different screen sizes (desktop, tablet, mobile).
- **Modular Structure:** Allows for flexible content arrangement.
- **Customizable:** Easy to style and modify using Bulma's classes and your own CSS.
- **Lightweight:** Minimal additional CSS needed beyond Bulma.

## Technologies Used
- **Bulma CSS Framework:** For styling and responsive layout.
- **HTML5:** For structuring the card component.
- **CSS3:** For additional custom styling.

## File Structure
```
bulma-card/
├── index.html       # Main HTML file
├── styles/
│   └── custom.css   # Custom CSS file
└── images/          # Folder for images used in the card
```

## Getting Started
Follow these steps to set up and customize your Bulma card component.

### Prerequisites
- A code editor (e.g., VS Code, Sublime Text).
- A web browser for testing (e.g., Chrome, Firefox).
- Basic knowledge of HTML and CSS.

### Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/bulma-card.git
   cd bulma-card
   ```

2. **Open the Project:**
   Open the project folder in your preferred code editor.

3. **Include Bulma:**
   Make sure Bulma is included in your project. You can use a CDN in the `index.html` file:
   ```html
   <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.3/css/bulma.min.css">
   ```

### Usage
1. **Basic Card Structure:**
   - Open `index.html` and use the following structure to create a basic card:
   ```html
   <div class="card">
     <div class="card-image">
       <figure class="image is-4by3">
         <img src="images/sample.jpg" alt="Placeholder image">
       </figure>
     </div>
     <div class="card-content">
       <div class="media">
         <div class="media-left">
           <figure class="image is-48x48">
             <img src="images/avatar.png" alt="Placeholder image">
           </figure>
         </div>
         <div class="media-content">
           <p class="title is-4">John Doe</p>
           <p class="subtitle is-6">@johndoe</p>
         </div>
       </div>
       <div class="content">
         Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.
         <a href="#">@bulmaio</a>. <a href="#">#css</a> <a href="#">#responsive</a>
         <br>
         <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
       </div>
     </div>
   </div>
   ```

2. **Customizing Styles:**
   - Open `styles/custom.css` to add any custom styles for your card component. You can override Bulma's default classes or add new styles as needed.

### Customization
1. **Changing Card Layout:**
   - Modify the structure in `index.html` to change the layout of the card (e.g., add/remove elements, rearrange sections).

2. **Styling with Bulma Classes:**
   - Use Bulma's utility classes to quickly change styles (e.g., `is-primary` for primary color, `has-text-centered` for centered text).

3. **Adding Interactivity:**
   - Include JavaScript if needed to add interactivity to your card component (e.g., toggling content, handling form submissions).

### Deploying
1. **Open in Browser:**
   - Open `index.html` in your web browser to view the card component.

2. **Deploy:**
   - Upload the contents of the `bulma-card` folder to your web server or use a service like GitHub Pages, Netlify, or Vercel for deployment.

## Contributing
Contributions are welcome! If you have suggestions for improvements or find any issues, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
For any questions or inquiries, please contact niranjankumar0986@gmail.com.

---

This README file provides a comprehensive guide to setting up and customizing a Bulma card component. Happy coding!
