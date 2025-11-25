# Ruchi Duggal - Technical Writer Portfolio

A modern, responsive portfolio website showcasing professional experience, achievements, and skills as a Senior Technical Writer.

## Features

- 🎨 Modern, clean design with smooth animations
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading with optimized performance
- 🎯 Easy navigation with smooth scrolling
- ♿ Accessible and SEO-friendly

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript
- Google Fonts (Inter)

## Getting Started

### Local Development

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd portfolio
   ```

2. Open `index.html` in your web browser, or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

## Deploying to GitHub Pages

### Method 1: Using GitHub's Web Interface

1. **Create a new repository** on GitHub (e.g., `portfolio` or `ruchi-duggal-portfolio`)

2. **Upload your files** to the repository:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md` (optional)

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on **Settings**
   - Scroll down to **Pages** section (in the left sidebar)
   - Under **Source**, select **Deploy from a branch**
   - Choose **main** (or **master**) branch
   - Select **/ (root)** folder
   - Click **Save**

4. **Access your site**:
   - Your portfolio will be available at: `https://<your-username>.github.io/<repository-name>`
   - It may take a few minutes for the site to be live

### Method 2: Using Git Command Line

1. **Initialize Git repository** (if not already done):
   ```bash
   git init
   ```

2. **Add all files**:
   ```bash
   git add .
   ```

3. **Commit your files**:
   ```bash
   git commit -m "Initial portfolio commit"
   ```

4. **Add your GitHub repository as remote**:
   ```bash
   git remote add origin https://github.com/<your-username>/<repository-name>.git
   ```

5. **Push to GitHub**:
   ```bash
   git branch -M main
   git push -u origin main
   ```

6. **Enable GitHub Pages** (follow steps 3-4 from Method 1)

## Customization

### Update Personal Information

1. **Contact Information**: Edit the contact section in `index.html` (around line 280)
2. **Social Links**: Update LinkedIn and other social media links
3. **Content**: Modify any section in `index.html` to reflect your latest information

### Change Colors

Edit the CSS variables in `styles.css` (at the top of the file):

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --primary-dark: #1e40af;        /* Darker shade */
    --secondary-color: #64748b;     /* Secondary color */
    --text-color: #1e293b;          /* Main text color */
    --text-light: #64748b;          /* Light text color */
    --bg-color: #ffffff;            /* Background color */
    --bg-alt: #f8fafc;              /* Alternate background */
}
```

### Update Hero Section

Modify the hero section gradient in `styles.css`:

```css
.hero {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

## File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This portfolio is open source and available for personal use.

## Contact

- **Email**: ruchi13duggal@gmail.com
- **Phone**: +1 (925) 819 7621
- **LinkedIn**: [linkedin.com/in/ruchi-duggal-446ba0101](https://www.linkedin.com/in/ruchi-duggal-446ba0101)
- **Location**: Fremont, CA

---

**Note**: Remember to update your contact information and any other personal details before deploying!

