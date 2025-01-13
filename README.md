# Project: Figma Web Design Implementation

This project involves converting a Figma design into a fully functional and responsive web page. The design adheres to modern standards and incorporates mobile responsiveness, hover interactions, and optimized font usage.

## Figma File Access

1. Create a Figma account if you don’t have one.
2. Open the provided Figma project link.
3. Click **"Duplicate to your Drafts"** to access all design details.
4. If you can’t access the file directly, refer to the Figma file provided.

## Fonts Used

Ensure you have the following fonts installed:
- [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
- [Spin Cycle OT](<provide-download-link-if-available>)

If these fonts are unavailable on your computer, download and install them before proceeding.

## Key Design Guidelines

### Responsive Design
- The web page must switch to the mobile version when the screen width is **480px or less**.

### Interactions
- **Links (hover/active):** Use the color `#FF6565`.
- **Buttons (hover/active):** Apply `opacity: 0.9`.

### Layout
- **Max width of content:** `1000px`, centered on the page.

### Design Rounding
- Some Figma values may be in float (e.g., 14.75px). Feel free to round them appropriately for implementation.

## Folder Structure

Organize your project with the following structure:

```
project-directory/
├── index.html      # Main HTML file
├── css/
│   ├── styles.css  # Main stylesheet
│   └── reset.css   # CSS reset (optional)
├── js/
│   └── script.js   # JavaScript file (if needed)
├── assets/
│   ├── images/     # Image assets
│   └── fonts/      # Custom fonts
└── README.md       # Project documentation
```

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project folder:
   ```bash
   cd project-directory
   ```

3. Open `index.html` in your browser to view the web page.

## Technologies Used

- **HTML5:** Semantic structure and layout.
- **CSS3:** Styling and responsive design.
- **JavaScript (Optional):** For dynamic interactions (if needed).

## Implementation Notes

### Responsive Design
Use media queries to handle screen size adjustments:
```css
@media screen and (max-width: 480px) {
  /* Mobile-specific styles */
}
```

### Centering Content
Ensure the maximum width of the content is centered:
```css
.container {
  max-width: 1000px;
  margin: 0 auto;
}
```

### Interactions
Define hover and active states:
```css
/* Links */
a:hover, a:active {
  color: #FF6565;
}

/* Buttons */
button:hover, button:active {
  opacity: 0.9;
}
```

## Contributions

Feel free to fork this project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the [MIT License](LICENSE).

---
