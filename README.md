# CSS Button Styling

This repository contains a simple, modern button with smooth hover effects implemented using CSS and HTML.

## Global Styles
- **Reset Styles:** Removes default margin and padding from all elements.
- **Box Sizing:** Uses `border-box` for consistent element sizing.

## Body Styling
- The body is set to `display: flex;` to center content both vertically and horizontally.
- It takes up the full viewport height (`100vh`).
- The background color is set to black (`#000`).

## Button Styling (`.submit-btn`)
- **Background:** Dark grayish-blue (`#1e272e`).
- **Text Color:** Light blue (`#4bcffa`).
- **Border:** None for a clean look.
- **Padding:** `15px 30px` for a comfortable size.
- **Font Size:** `18px` with `uppercase` text transformation.
- **Cursor:** Changes to a pointer when hovered.
- **Rounded Corners:** `border-radius: 5px;` for smooth edges.
- **Letter Spacing:** `2px` for a stylish effect.
- **Font Weight:** Bold for better readability.
- **Transitions:**
  - **Box Shadow & Transform:** Smooth animation effects on hover.

## Possible Enhancements
- Add a hover effect for interactivity:
  ```css
  .submit-btn:hover {
    box-shadow: 0 0 15px rgba(75, 207, 250, 0.8);
    transform: scale(1.05);
  }
  ```

## Setup Instructions
To clone the project or download the archive, use the following command:
```bash
git clone https://github.com/mihaiapostol14/submit-button.git
```

## Usage Examples
1. Open the `index.html` file in a web browser to see the button in action.
2. Modify the CSS file to customize the button's appearance further.

## Contribution Guidelines
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.
