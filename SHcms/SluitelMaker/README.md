# SluitelMaker Website - SHcms

This is the SluitelMaker website built under the SHcms content management system.

## Directory Structure

```
SHcms/
└── SluitelMaker/
    ├── index.html          # Main website page
    ├── css/
    │   └── styles.css      # Website styling
    ├── js/
    │   └── main.js         # JavaScript functionality
    ├── images/             # Image assets directory
    └── config/
        └── site.json       # Site configuration
```

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Smooth Navigation**: Smooth scrolling between sections
- **Contact Form**: Functional contact form with validation
- **Service Showcase**: Grid layout for displaying services
- **Animation Effects**: Scroll-based animations for enhanced UX

## Website Sections

1. **Home (Hero)**: Landing section with call-to-action
2. **Services**: Showcase of key making and locksmith services
3. **About**: Information about SluitelMaker
4. **Contact**: Contact form for customer inquiries

## Services Offered

- Key Duplication
- Lock Installation
- Lock Repair
- Emergency Services (24/7)

## Configuration

The website can be configured through the `config/site.json` file, which includes:
- Site metadata (name, title, description)
- Theme colors
- Navigation structure
- Service definitions
- Contact information

## Usage

### Local Development

1. Open `index.html` in a web browser
2. Or use a local server:
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

### Deployment

Simply upload the entire `SluitelMaker` directory to your web server.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Technologies Used

- HTML5
- CSS3 (with Grid and Flexbox)
- Vanilla JavaScript
- Responsive Design
- Intersection Observer API

## Customization

### Colors
Edit the CSS variables or theme colors in `config/site.json`:
- Primary: `#3498db` (blue)
- Secondary: `#2c3e50` (dark blue)
- Accent: `#667eea` (purple)

### Content
Modify the HTML content in `index.html` or update the configuration in `config/site.json`.

### Styling
All styles can be modified in `css/styles.css`.

## License

Copyright © 2026 SluitelMaker. All rights reserved.
