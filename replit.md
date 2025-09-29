# Shruti Sanap Portfolio

## Overview

This is a personal portfolio website for Shruti Sanap, an MCA student and aspiring software developer/DevOps engineer. The site serves as a professional showcase of her skills, projects, and contact information. It's built as a single-page application with multiple sections including home, about, skills, projects, and contact areas.

## Recent Changes

**September 29, 2025:**
- Complete portfolio website implementation with all requested sections
- Professional HTML structure with semantic markup and clean organization  
- Modern CSS styling with responsive design, gradient backgrounds, and smooth animations
- JavaScript functionality for navigation, mobile menu, and smooth scrolling
- All content sections implemented: hero/introduction, education, skills, projects, contact
- Professional profile image placeholder system with fallback handling
- Fixed education content to accurately reflect BCA degree information
- Responsive design working across desktop, tablet, and mobile devices
- Website successfully deployed and running on port 5000

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Single-Page Application (SPA)**: Built using vanilla HTML, CSS, and JavaScript without any frontend frameworks
- **Responsive Design**: Mobile-first approach with hamburger menu navigation for smaller screens
- **Section-Based Layout**: Organized into distinct sections (home, about, skills, projects, contact) with smooth scrolling navigation
- **Component Structure**: Modular CSS classes for reusable styling patterns

### Navigation System
- **Fixed Header**: Sticky navigation bar that remains visible during scrolling
- **Smooth Scrolling**: JavaScript-powered smooth transitions between sections
- **Mobile Navigation**: Collapsible hamburger menu for mobile devices
- **Dynamic Styling**: Navbar background changes on scroll for visual feedback

### Styling Architecture
- **CSS Reset**: Global reset for consistent cross-browser rendering
- **Utility Classes**: Reusable CSS classes for buttons, containers, and layout components
- **Responsive Breakpoints**: Mobile-responsive design with flexible layouts
- **Visual Hierarchy**: Typography and color scheme optimized for readability

### JavaScript Features
- **Event-Driven Interactions**: Click handlers for navigation and mobile menu toggle
- **Scroll Detection**: Dynamic navbar styling based on scroll position
- **Intersection Observer**: Prepared for scroll-based animations (partially implemented)
- **Error Handling**: Image fallback system for profile pictures

### Asset Management
- **Static Assets**: Local image files with fallback mechanisms
- **Profile Image System**: Primary profile image with placeholder fallback
- **No Build Process**: Direct file serving without compilation or bundling

## External Dependencies

### Core Technologies
- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with flexbox, transitions, and responsive design
- **Vanilla JavaScript**: No external JavaScript libraries or frameworks

### Browser Dependencies
- **Modern Browser Features**: Relies on CSS flexbox, smooth scrolling, and ES6 JavaScript features
- **Cross-Browser Compatibility**: Uses standard web APIs for maximum compatibility

### Assets
- **Local Images**: Profile photos stored locally with error handling
- **Web Fonts**: Uses system fonts (Segoe UI family) for performance and consistency
- **No CDN Dependencies**: All resources served locally for fast loading and offline capability

### Development Environment
- **No Build Tools**: Direct file editing without webpack, gulp, or other build systems
- **No Package Manager**: No npm, yarn, or other dependency management
- **Static Hosting Ready**: Designed for deployment to any static web server