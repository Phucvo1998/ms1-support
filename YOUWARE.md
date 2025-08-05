# YOUWARE Project Guide

## Project Overview
This is an English-language technical support center website for m.i.crosoft products that has been redesigned as an independent third-party support service. The current implementation provides legitimate technical support information with modern design principles and advanced animations while clearly indicating independence from m.i.crosoft Corporation.

## File Structure
- `index.html` - Main entry point (Single-file architecture with embedded CSS and JavaScript)
- `images/` - Local image assets for offline functionality
  - `b9f144e3198245a184c14cf6715a6b97.jpeg` - Hero section support team image

## Key Implementation Details

### Design Approach
- **Mobile-first responsive design** with CSS Grid and Flexbox
- **Independent branding** without m.i.crosoft logo, using "m.i.crosoft" text branding instead
- **Neutral color scheme** with #0078d4 primary blue color maintained
- **English language content** throughout the entire site for global accessibility
- **Professional imagery** sourced and stored locally for offline functionality

### Technical Architecture
- **Single HTML file** with embedded styles and scripts for complete offline functionality
- **Semantic HTML structure** for accessibility and SEO
- **CSS Grid layouts** for responsive service cards and feature sections
- **Intersection Observer API** for scroll animations
- **Local asset storage** - all images stored in `images/` directory for offline use
- **No external dependencies** - completely self-contained

### Content Strategy
- **Independent technical support service** clearly identified as third-party
- **Comprehensive disclaimers** stating non-affiliation with m.i.crosoft Corporation
- **Service-focused content** covering Windows, Office, m.i.crosoft 365, Xbox, and Surface
- **Professional presentation** suitable for business or educational use
- **Contact information** with phone number 1-877-514-5149 for direct calling

### Key Features
- **Header without logo** - text-based branding "m.i.crosoft Support"
- Hero section with local images and call-to-action
- Service grid with staggered animations and hover effects
- Feature highlights with icons and professional animations
- Contact section with optimized mobile call buttons
- Comprehensive footer with detailed disclaimer
- **Mobile optimizations**: Responsive design with special mobile call button styling

### Offline Capabilities
- All images downloaded and stored locally in `images/` directory
- No external CDN dependencies
- Self-contained CSS and JavaScript
- Meta tags for mobile web app capabilities
- Complete offline functionality when downloaded

## Development Notes
- **Phone Number**: 1-877-514-5149 (direct calling enabled, no confirmation dialogs)
- **Mobile Optimization**: Call buttons optimized for mobile with circular design on small screens
- **Branding**: Uses "m.i.crosoft" instead of "Microsoft" throughout
- **Legal Compliance**: Multiple disclaimers indicating independent third-party status
- **Performance**: All assets local for fast loading and offline use

## Important Considerations
- **Independent Service**: This is explicitly an independent third-party support service
- **No Official Affiliation**: Clear disclaimers throughout stating non-affiliation with m.i.crosoft Corporation
- **Educational/Business Use**: Professional presentation suitable for legitimate support services
- **Offline-First**: Designed to work completely offline when downloaded
- **Mobile-Optimized**: Special attention to mobile user experience and call functionality
- **Accessibility**: Semantic HTML and proper ARIA considerations