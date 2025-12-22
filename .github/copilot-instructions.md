<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

# Krokåsdalen Forsamlingshus Website Development

## Project Overview
This is a static HTML/CSS website for Krokåsdalen community center venue rental on Askøy, Norway.

## Project Structure
- **index.html** - Home page
- **om-lokalet.html** - About the venue
- **leiepriser.html** - Pricing information
- **veibeskrivelse.html** - Location/directions
- **bildegalleri.html** - Photo gallery
- **kontakt.html** - Contact form
- **styles.css** - Main stylesheet
- **assets/images/** - Image directory (placeholder)

## Key Features
- Responsive design with mobile-first approach
- Professional color scheme (blue/orange)
- Navigation menu on all pages
- Contact form with email integration
- Footer with contact information
- Card-based layout for information sections

## Customization Guidelines

### Adding Images
Place images in `assets/images/` directory and reference them in HTML:
```html
<img src="assets/images/filename.jpg" alt="Description">
```

### Modifying Colors
Edit CSS variables in styles.css (lines 7-15):
```css
--primary-color: #2c5282;
--secondary-color: #4299e1;
--accent-color: #ed8936;
```

### Updating Contact Information
Search and replace:
- Email: janminde194@gmail.com
- Address: Krokåsdalen 120, 5302 Strusshamn
- Phone: Add as needed

### Content Guidelines
- Keep Norwegian language throughout
- Maintain consistent tone (professional, welcoming)
- Use metric units for measurements
- All prices should be in NOK (Norwegian Krone)

## Development Tips
- Use VS Code's Live Server for testing
- Test on mobile devices (responsive design)
- Validate HTML with W3C validator
- Keep file sizes optimized for web
- Use semantic HTML elements

## Future Enhancements
- Add real photos to gallery
- Integrate backend for form submission
- Add calendar for availability
- Implement online booking system
- Add multi-language support
- SEO optimization
