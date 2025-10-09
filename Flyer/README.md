# Delta Flyer Refit Website

This is the website for the Delta Flyer Refit 3D printer project, designed by Rolohaun and Kanrog, with a building kit by LDO.

## Deployment to GitHub Pages

To deploy this website to `https://kanrog.github.io/Flyer`, follow these steps:

### Option 1: Using GitHub Web Interface

1. Go to your GitHub repository: `https://github.com/Kanrog/Delta-Flyer-Refit`
2. Create a new branch called `gh-pages`
3. Upload all files from this `Flyer` folder to the `gh-pages` branch
4. Go to Settings > Pages
5. Under "Source", select the `gh-pages` branch
6. Save the settings
7. Your site will be available at `https://kanrog.github.io/Flyer`

### Option 2: Using Git Command Line

```bash
# Navigate to your Delta-Flyer-Refit repository
cd Delta-Flyer-Refit

# Create and switch to gh-pages branch
git checkout --orphan gh-pages

# Remove all existing files
git rm -rf .

# Copy all files from the Flyer folder
cp -r /path/to/Flyer/* .

# Add all files
git add .

# Commit
git commit -m "Deploy Delta Flyer Refit website"

# Push to GitHub
git push origin gh-pages

# Enable GitHub Pages in repository settings
# Go to Settings > Pages > Source > Select gh-pages branch
```

### Option 3: Create a New Repository

1. Create a new repository called `Flyer` on GitHub
2. Upload all files from this folder
3. Enable GitHub Pages in Settings > Pages
4. Select the main branch as source
5. Your site will be available at `https://kanrog.github.io/Flyer`

## File Structure

```
Flyer/
├── index.html              # Main HTML file
├── style.css               # Stylesheet with green, blue, and purple theme
├── assets/
│   ├── images/            # All logos and images
│   │   ├── LDO.PNG
│   │   ├── rolohaun.png
│   │   ├── Kanrog_LOGO_wtext.png
│   │   ├── Delta_Flyer_Logo.png
│   │   └── Delta_Flyer_Refit_Full_Assembly_11.png
│   └── pdfs/              # All PDF documents
│       ├── Delta_Flyer_Refit_Wiring_Diagram.pdf
│       ├── LDO_DZ01_Delta_Flyer_klipper_tutorial_Public.pdf
│       └── bigtreetech-beta.github.io.pdf
└── README.md              # This file
```

## Features

- **Responsive Design**: Works on all devices
- **Color Scheme**: Green (#3f7268), Blue (#446696), and Purple (#9b59b6)
- **Logo Hierarchy**: LDO logo at top, Rolohaun and Kanrog logos below
- **Interactive Elements**: All images and PDFs are clickable and open in new tabs
- **Modern Styling**: Gradient effects, hover animations, and smooth transitions

## Credits

- **Design**: Rolohaun & Kanrog
- **Kit Manufacturer**: LDO
- **Website Template**: Based on Kanrog Creations website

## License

All content related to the Delta Flyer Refit project is subject to the original project's licensing terms.