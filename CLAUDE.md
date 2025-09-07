# Vibe Coding - Anthropic Futures Forum Demo

## Project Overview

This is a demo station for the **Anthropic Futures Forum** event, showcasing the theme "Everyone is a Developer - create a game or an app with Claude". The project contains a collection of 31 interactive web applications including games, utilities, and creative tools.

## Brand Styling Guide

### Typography

The project uses Anthropic's official brand fonts:

- **Event/Anthropic Headings**: Styrene A Medium
  - Letter spacing: -3% (tight)
  - Line height: 110% minimum
  
- **Claude/Category Headings**: Copernicus Book  
  - Letter spacing: -3% (tight)
  - Line height: 110% minimum
  
- **Body Text**: Tiempos Text Regular/Medium
  - Line height: 140% minimum
  
- **Detail/Card Text**: Styrene B Regular/Medium
  - Line height: 140% minimum

### Color Palette

```css
--ivory: #FAF9F5;     /* Primary background */
--slate: #141413;     /* Primary text */
--clay: #D97757;      /* Links and accents */
--oat: #E3DACC;       /* Secondary backgrounds */
```

Additional colors available:
- Sky: #6A9BCC
- Olive: #788C5D  
- Coral: #EBCECE
- Heather: #CBCADB

### Layout Structure

1. **Hero Section**: Dark slate background with ivory text featuring the event name and subtitle
2. **Content Area**: Ivory background with categorized grid of demo applications
3. **Cards**: White backgrounds with subtle shadows and clay-colored hover effects

## Font Files

All brand fonts are located in the `/fonts` directory with proper @font-face declarations in index.html.

## Development Notes

- The landing page emphasizes the event branding with the app/game index pushed down
- All interactive demos are self-contained HTML files
- The design follows Anthropic's brand guidelines for color, typography, and spacing

## Important Instructions

- **When creating new HTML files**: Always open them in the browser after creation using `open filename.html`
- **When adding new games, utilities, or applications**: Always update the index.html homepage to include the new item in the appropriate category section
- **After creating a new file**: Always tell the user the publicly accessible URL will be `https://dshields1.github.io/vibe-coding/[filename].html` (where [filename] is the actual name of the file created), and ask if they'd like to open a QR code that shows the URL. To show the QR code, open the local qr-generator.html file with a query parameter containing the public URL: `open qr-generator.html?url=https://dshields1.github.io/vibe-coding/[filename].html`