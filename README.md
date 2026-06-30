# Sweet Susu Farm Produce Website

A modern, responsive website for Sweet Susu Farm Produce, built with React, Vite, and TailwindCSS.

## Vision
Growing prosperity through quality agriculture.

## Mission
Plant today and harvest tomorrow

## Features

- **Fully Responsive Design**: Optimized for both mobile phones and desktop computers
- **Modern UI**: Clean, contemporary design using TailwindCSS
- **Smooth Navigation**: Sticky header with mobile-friendly hamburger menu
- **Hero Section**: Eye-catching introduction with vision and mission statements
- **About Section**: Company information and core values
- **Products Section**: Showcase of farm produce offerings
- **Contact Section**: Contact form and information with social media links
- **Footer**: Quick links and social media connections

## Technology Stack

- **React 18**: Modern React library for building user interfaces
- **Vite**: Fast build tool and development server
- **TailwindCSS**: Utility-first CSS framework for styling
- **Lucide React**: Beautiful icon library

## Getting Started

### Prerequisites

- Node.js (version 16 or higher) installed on your machine
- npm or yarn package manager

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser and navigate to the URL shown in the terminal (typically `http://localhost:5173`)

### Building for Production

To create an optimized production build:

```bash
npm run build
```

The built files will be in the `dist` directory.

### Preview Production Build

To preview the production build locally:

```bash
npm run preview
```

## Project Structure

```
sweet-susu-farm-produce/
├── images/
│   └── logo.png              # Company logo
├── src/
│   ├── components/
│   │   ├── About.jsx         # About section
│   │   ├── Contact.jsx       # Contact section with form
│   │   ├── Footer.jsx        # Footer component
│   │   ├── Hero.jsx          # Hero section with vision/mission
│   │   ├── Navbar.jsx        # Navigation bar with mobile menu
│   │   └── Products.jsx      # Products showcase
│   ├── App.jsx               # Main app component
│   ├── main.jsx              # React entry point
│   └── index.css             # Global styles and Tailwind imports
├── index.html                # HTML template
├── package.json              # Dependencies and scripts
├── tailwind.config.js        # TailwindCSS configuration
├── vite.config.js            # Vite configuration
└── postcss.config.js         # PostCSS configuration
```

## Customization

### Colors

The website uses a custom color palette defined in `tailwind.config.js`:
- `farm-green`: Primary green (#2D5A27)
- `farm-light`: Lighter green (#4A7C44)
- `farm-cream`: Background cream (#F5F1E8)
- `farm-gold`: Accent gold (#D4A853)
- `farm-brown`: Earthy brown (#8B5A2B)

### Logo

The logo is located in the `images/logo.png` file. To replace it, simply update the file with your new logo while keeping the same filename.

### Contact Information

Update contact details in the `Contact.jsx` component:
- Phone number
- Email address
- Physical location
- Social media links

## Social Media

The website links to:
- Sweet Susu Farm Produce Facebook page
- Elizabeth's Library International Facebook page

## Browser Support

The website supports all modern browsers including:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2024 Sweet Susu Farm Produce. All rights reserved.
