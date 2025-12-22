# Krokåsdalen forsamlingshus - Static Website

A professional static website for Krokåsdalen community center venue rental, located on Askøy island near Bergen, Norway.

## Overview

This is a clean, modern, and responsive HTML/CSS website that replicates the design and functionality of www.forsamlingshuset.no. The site provides information about the community center venue, its facilities, rental prices, location details, photo gallery, and contact information.

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Clean Navigation**: Easy-to-use navigation menu across all pages
- **Multiple Pages**:
  - Home page with welcome and key information
  - About the venue (facilities and capabilities)
  - Rental prices and contract information
  - Location and directions
  - Photo gallery
  - Contact form with email integration

## Pages

1. **index.html** - Home page with hero section and quick info cards
2. **om-lokalet.html** - Detailed information about the venue
3. **leiepriser.html** - Pricing and contract information
4. **veibeskrivelse.html** - Location and driving directions
5. **bildegalleri.html** - Photo gallery section
6. **kontakt.html** - Contact form and contact details

## Styling

- **styles.css** - Complete styling with custom color scheme
  - Primary color: #2c5282 (Dark Blue)
  - Secondary color: #4299e1 (Light Blue)
  - Accent color: #ed8936 (Orange)

## How to Use

1. Simply open `index.html` in your web browser
2. Or use a local server to serve the files:
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. Or use VS Code's Live Server extension:
   - Install the "Live Server" extension
   - Right-click on index.html
   - Select "Open with Live Server"

## Content

The website includes:
- **Capacity**: 60-65 people
- **Facilities**: Kitchen with stove, steamer, dishwasher, refrigerator
- **Equipment**: Projector with large screen
- **Parking**: Approximately 20 cars
- **Location**: Krokåsdalen 120, 5302 Strusshamn, Norway
- **Distance from Bergen**: 15 minutes
- **Distance from Kleppestø**: 5 minutes

## Customization

To customize this website:

1. **Update Contact Information**: Edit the email address and phone number throughout the site
2. **Add Photos**: Replace placeholder images in the gallery section with actual venue photos
3. **Modify Colors**: Change CSS variables in `styles.css` (lines 7-15)
4. **Update Text**: Edit HTML content in each page file
5. **Add Maps**: Integrate Google Maps in the directions page

## Browser Support

Works with all modern browsers:
- Chrome/Chromium
- Firefox
- Safari
- Edge

## File Structure

```
forsamlingshuset/
├── index.html
├── om-lokalet.html
├── leiepriser.html
├── veibeskrivelse.html
├── bildegalleri.html
├── kontakt.html
├── styles.css
└── assets/
    └── images/
```

## Contact

For more information about the venue:
- Email: janminde194@gmail.com
- Address: Krokåsdalen 120, 5302 Strusshamn, Norway
- Facebook: https://www.facebook.com/551626331

## License

This website is created for Krokåsdalen forsamlingshus. All rights reserved.

---

*Created: December 2024*
