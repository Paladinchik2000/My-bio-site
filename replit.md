# Portfolio Website - Nikita Paladi

## Overview
A static HTML portfolio and CV website for Nikita Paladi (Paladinchik). Features a modern, techno-inspired design with sections for About, Skills, Tech Stack, CV, Projects, Gallery, and Contacts.

## Project Structure
```
.
├── index.html          # Main portfolio page (single-page app)
├── files/              # Downloadable files
│   └── Nikita_Paladi_CV.pdf
├── images/             # Image assets
│   ├── gallery-tirebuddy1.png
│   └── gallery-tirebuddy2.png
├── favicon-*.png       # Favicon files
├── apple-touch-icon.png
└── android-chrome-*.png
```

## Running the Project
The website is served as static files using Python's built-in HTTP server on port 5000.

**Development:** Run the "Portfolio Website" workflow which executes:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured for static deployment. The entire root directory (`.`) is served as static files.

## Technologies Used
- HTML5
- CSS3 (with CSS custom properties/variables)
- Vanilla JavaScript
- Google Fonts (Orbitron, Inter)
