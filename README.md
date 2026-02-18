# Nigeria Incident Map

Interactive Nigeria incident mapping system for ENI/NAOC operational intelligence.

## Features

- Interactive Nigeria map with state boundaries
- ENI sites and infrastructure markers
- Incident placement and management
- Customizable legend with categories
- CSV and SVG export functionality
- Local storage persistence
- Responsive design

## Deployment

### Vercel Deployment

1. **Install Vercel CLI**
   ```bash
   npm i -g vercel
   ```

2. **Login to Vercel**
   ```bash
   vercel login
   ```

3. **Deploy from project directory**
   ```bash
   cd c:/Dev/node-projects/map-projects
   vercel --prod
   ```

4. **Follow the prompts:**
   - Set up and deploy `nigeria-incident-map`
   - Link to existing Vercel account or create new
   - Confirm deployment settings

### Alternative: Vercel Web Interface

1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Connect your GitHub repository or upload files
4. Vercel will automatically detect the static HTML
5. Deploy!

## Files Structure

```
nigeria-incident-map/
├── nigeria_map copy.html    # Main application
├── index.html              # Redirect to main app
├── vercel.json            # Vercel configuration
├── package.json            # Project metadata
├── data/                  # GeoJSON data
│   └── nigeria-states.geojson
└── images/                # Assets
    └── eni-logo.png
```

## Configuration

- **vercel.json**: Routes and build configuration
- **package.json**: Project metadata
- **index.html**: Redirect to main HTML file

The application is a static HTML file with no build process required.
