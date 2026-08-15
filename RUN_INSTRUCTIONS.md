# How to Run the Portfolio Locally

## Project Overview
This is a static HTML/CSS/JavaScript portfolio website Of Taimoor Asif Personal Portfolio.

## Methods to Run the Portfolio

### Method 1: Using Node.js Server (Recommended)
1. **Navigate to the project directory:**
   ```bash
   cd "c:/Users/Asif/OneDrive/المستندات/taimoor-asif/personal-portfolio-main"
   ```

2. **Start the Node.js server:**
   ```bash
   node server.js
   ```

3. **Open your browser and go to:**
   ```
   http://localhost:8080
   ```

4. **To stop the server:** Press `Ctrl+C` in the terminal

### Method 2: Using Python Server (if Python is available)
1. **Navigate to the project directory:**
   ```bash
   cd "c:/Users/Asif/OneDrive/المستندات/taimoor-asif/personal-portfolio-main"
   ```

2. **Start Python HTTP server:**
   ```bash
   python -m http.server 8080
   ```
   (or `python3 -m http.server 8080` on some systems)

3. **Open your browser and go to:**
   ```
   http://localhost:8080
   ```

### Method 3: Direct File Access (Simplest)
1. **Simply open the index.html file directly in your browser:**
   - Navigate to: `c:/Users/Asif/OneDrive/المستندات/taimoor-asif/personal-portfolio-main/`
   - Double-click on `index.html`
   - Or drag `index.html` into your browser window

## Project Structure
```
personal-portfolio-main/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css      # Main stylesheet
│   │   └── swiper-bundle.min.css  # Swiper CSS
│   ├── js/
│   │   └── main.js         # JavaScript functionality
│   ├── img/                # Images and assets
│   ├── favicons/           # Website icons
│   └── pdf/                # PDF files (resume, etc.)
├── server.js               # Node.js server file
└── README.md               # This file
```

## Dependencies
This is a static website with minimal dependencies:
- **Boxicons**: Icon library (loaded via CDN)
- **Swiper.js**: Slider/carousel library (local file)
- **Custom CSS**: Custom styling
- **Vanilla JavaScript**: No framework dependencies

## Customization Tips
1. **Edit personal information** in `index.html`
2. **Modify styles** in `assets/css/styles.css`
3. **Update images** in the `assets/img/` folder
4. **Add projects** by editing the portfolio section in `index.html`

## Browser Compatibility
This portfolio works on all modern browsers:
- Chrome/Chromium
- Firefox
- Safari
- Edge
- Mobile browsers

## Troubleshooting
- **If images don't load**: Check that all image paths in the HTML are correct
- **If styles don't apply**: Ensure the CSS files are linked properly
- **If JavaScript doesn't work**: Check the browser console for errors

## Current Running Status
✅ **Server is currently running at:** `http://localhost:8080`
✅ **Browser preview available at:** `http://127.0.0.1:51938`

The portfolio is fully functional and ready to use!
