# Cursor Clone

A responsive landing page clone of [Cursor](https://cursor.com), built as part of the WebDev Cohort 2026 assignment. This project recreates the modern design and layout of the Cursor AI code editor website.

## 📋 Features

- **Responsive Design**: Mobile-friendly layout that adapts to all screen sizes
- **Modern UI**: Clean, minimalist design with dark theme
- **Interactive Elements**: Hover effects, smooth transitions, and dynamic sections
- **Multiple Sections**:
  - Hero section with call-to-action
  - Logo garden (trusted companies)
  - Feature showcase sections with alternating layouts
  - Team testimonials grid (3-column layout)
  - Frontier features grid
  - Changelog section with recent updates
  - Highlights feed
  - Team recruitment section

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Flexbox, CSS Grid, custom properties, and media queries
- **Assets**: SVG logos and PNG images from Cursor brand assets

## 📁 Project Structure

```
Cursor Clone/
├── index.html                 # Main HTML file
├── style.css                  # Global styles and responsive design
├── README.md                  # This file
└── cursor-brand-assets/       # Brand assets (logos, images)
    ├── General Logos/
    ├── Logo Garden/
    ├── Review-avatars/
    └── [images and SVGs]
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required

### Installation

1. **Clone or download the project**:
   ```bash
   git clone <repository-url>
   cd "Cursor Clone"
   ```

2. **Open in browser**:
   - Double-click `index.html` to open in your default browser
   - Or right-click and select "Open with" → choose your browser
   - Or use a local server (see below)

### Using a Local Server (Recommended)

To avoid CORS issues and for better development experience:

**Using Python (3.x)**:
```bash
python -m http.server 8000
```

**Using Node.js (http-server)**:
```bash
npx http-server
```

**Using Live Server (VS Code Extension)**:
- Install the "Live Server" extension in VS Code
- Right-click `index.html` and select "Open with Live Server"

Then visit `http://localhost:8000` (or the port shown) in your browser.

## 📱 Responsive Breakpoints

The design includes responsive adjustments for:
- **Desktop**: 1200px and above (full layout)
- **Tablet**: 768px - 1199px (adjusted spacing and grid layouts)
- **Mobile**: Below 768px (stacked layouts, single-column grids)

## 🎨 Customization

### Colors
Primary colors are defined in the CSS:
- **Background**: `#14120B` (dark)
- **Card Background**: `#1B1913` (slightly lighter)
- **Text**: `#EDECEC` (off-white)
- **Accent**: `rgb(96.08% 30.58% 0% / 0.75)` (orange)

To change colors, update the hex values in `style.css`.

### Images & Assets
Replace images in the `cursor-brand-assets/` folder:
- Update `src` attributes in `index.html` to point to your new images
- Maintain aspect ratios for consistency

### Content
Edit text directly in `index.html`:
- Section headings
- Feature descriptions
- Testimonial text
- Changelog entries

## 🔧 Key CSS Classes & IDs

### Main Sections
- `.main-section-container` - Feature showcase sections
- `.grid-review` - Testimonials grid
- `.fronteir-grid` - Frontier features (1x3 grid)
- `.changelog` - Changelog section
- `.highlights-section` - Recent highlights feed

### Components
- `.grid-item` - Testimonial card
- `.fronteir-grid-item` - Frontier feature card
- `.highlight-card` - Highlight/update card
- `.changelog-card` - Changelog entry

## 📝 Notes on Development

- **Fixed Header**: Navigation stays at top while scrolling
- **Flexbox & Grid**: Modern CSS layout techniques for responsive design
- **Object-fit**: Images scale proportionally within containers
- **Z-index Management**: Proper layering of overlapping elements

## 🐛 Known Considerations

- Some spacing adjustments may be needed based on actual content length
- Image aspect ratios should be maintained for optimal display
- Favicon is currently set to Cursor's cube logo

## 📄 License

This is a clone created for educational purposes as part of the WebDev Cohort 2026 assignment.

## 🚢 Deployment

### Deploy to GitHub Pages

1. Create a GitHub repository
2. Push all files to the `main` branch
3. Go to Settings → Pages
4. Set source to `main` branch
5. Your site will be live at `https://<username>.github.io/<repo-name>`

### Deploy to Netlify

1. Connect your GitHub repository
2. Set build command: (leave empty - static site)
3. Set publish directory: `/` (root)
4. Deploy

### Deploy to Vercel

1. Import your GitHub repository
2. Vercel auto-detects the static site
3. Click "Deploy"

## 📞 Support

For questions or issues, refer to the code comments in `index.html` and `style.css` or review the course materials from WebDev Cohort 2026.

---

**Happy Coding!** 🎉
