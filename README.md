# Personal Academic Website

Welcome! This is a clean, professional personal website template designed for PhD students and early-career researchers.

## Features

- **Responsive Design**: Works beautifully on desktop, tablet, and mobile devices
- **Professional Layout**: Organized sections for About, Research, CV, and Contact
- **Easy to Customize**: Simple HTML and CSS structure for quick personalization
- **No Dependencies**: Pure HTML/CSS — no frameworks required
- **GitHub Pages Ready**: Deploy directly from this repository

## Getting Started

### 1. Clone or Download
This repository is already set up to work with GitHub Pages at `https://u-li-li.github.io/`

### 2. Customize Your Information

Edit `index.html` and update:
- Replace "Lingyuan" with your name (in the title, navbar, and footer)
- Update the hero section tagline
- Customize the "About Me" section with your bio
- Add your research interests in the Research section
- Add your education and experience in the CV section
- Update contact links (email, GitHub, LinkedIn, Twitter/X)

### 3. Add Your CV

Place your CV PDF file in the root directory as `cv.pdf`. The download link in the CV section will automatically work.

### 4. Personalize the Styling

Edit `styles.css` to customize:
- Colors: Modify the `:root` CSS variables at the top
- Fonts: Update the `font-family` declarations
- Spacing and layout: Adjust padding and margins as needed

### 5. Deploy to GitHub Pages

1. Make sure your repository is named `yourusername.github.io`
2. Commit and push your changes to the `main` branch
3. Your site will be live at `https://yourusername.github.io/`

GitHub Pages will automatically serve the `index.html` file.

## Customization Examples

### Change the Color Scheme

In `styles.css`, update the CSS variables:
```css
:root {
    --primary-color: #2c3e50;      /* Main dark color */
    --secondary-color: #3498db;    /* Accent blue */
    --accent-color: #e74c3c;       /* Not currently used, add as needed */
    --light-bg: #ecf0f1;           /* Light background */
}
```

### Add More Research Interests

Duplicate the `.interest-card` div in the Research section:
```html
<div class="interest-card">
    <h3>Your Interest</h3>
    <p>Description of your research interest.</p>
</div>
```

### Add Social Media Links

Update the contact links in the Contact section with your profiles:
```html
<a href="https://twitter.com/yourhandle" class="contact-link" target="_blank">🐦 Twitter</a>
```

## File Structure

```
├── index.html          # Main website file
├── styles.css          # Styling
├── cv.pdf             # Your CV (add this file)
└── README.md          # This file
```

## Tips

- Keep the About and Contact sections concise but engaging
- Consider adding a photo later (you can update `styles.css` to include one)
- Update your research interests as your focus evolves
- Add publication links once you have them
- Ensure all external links (email, social media) are correctly formatted

## Support

For GitHub Pages issues, visit: https://docs.github.com/en/pages

For more inspiration, check out other academic websites to see what resonates with you!

---

**Happy researching!** 🎓
