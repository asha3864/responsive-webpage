# Responsive Webpage

This project is a simple responsive webpage that features a fixed navbar, a collapsible left menu, a main content area, a right panel, and a footer. The layout dynamically adjusts based on screen size to ensure a user-friendly experience across devices.

## Features

1. **Fixed Navbar**
   - The navigation bar remains at the top of the page when scrolling.

2. **Responsive Layout**
   - Includes three main sections:
     - Left menu (collapsible)
     - Main content area
     - Right-side panel
   - Adjusts to different screen sizes using CSS media queries and JavaScript scaling.

3. **Collapsible Left Menu**
   - The left menu can be toggled open and closed using a button.

4. **Dynamic Page Scaling**
   - The page content scales dynamically based on the screen width:
     - 50% width for screens ≤ 600px.
     - 75% width for screens between 600px and 700px.
     - 80% width for screens between 700px and 767px.
     - 90% width for screens between 992px and 1600px.

## Technologies Used

- **HTML**: Structure of the webpage.
- **CSS**: Styling for layout and responsiveness.
- **JavaScript**: Interactivity and dynamic scaling logic.

## Usage

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   ```

2. **Open in Browser**
   Open the `index.html` file in any modern web browser.

## File Structure

```
project-directory/
├── index.html       # Main HTML file
├── style.css        # CSS for styling (inline in this project)
└── script.js        # JavaScript for interactivity (inline in this project)
```

## Functionality Details

### Navbar
- The navbar is fixed at the top of the page and remains visible during scrolling.

### Collapsible Left Menu
- Clicking the "Toggle Menu" button collapses or expands the left menu.

### Dynamic Scaling
- JavaScript dynamically scales the webpage based on screen size to provide an optimal viewing experience.
- The `adjustPageWidth` function listens to the `resize` event and applies appropriate scaling.

### Footer
- The footer is fixed at the bottom of the page and contains placeholder text.

## Future Enhancements

1. Add animations for the collapsible menu.
2. Implement additional sections or features, such as a contact form.
3. Optimize for accessibility (e.g., ARIA attributes).

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute this project as needed.
