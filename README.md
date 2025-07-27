
# AI-Powered Product Recommendation System

A modern web application that provides personalized product recommendations using AI similarity matching. Users can search for products and get visually appealing recommendations with similarity scores.

## Features

- **Intuitive Search Interface**: Clean, accessible search form with modern styling
- **Visual Product Cards**: Responsive cards with hover animations and image scaling
- **Performance Optimized**: Lazy loading images and modern CSS transitions
- **Accessibility Focused**: Semantic HTML and ARIA labels
- **Fully Responsive**: Works on mobile, tablet, and desktop devices
- **Bootstrap Powered**: Utilizes Bootstrap 5 for layout and components

## Technologies Used

- HTML5
- CSS3 (with modern gradients and animations)
- Bootstrap 5
- Jinja2 templating (for backend integration)

## User Manual

### 1. Searching for Products
1. Type your product name in the search box (e.g., "wireless headphones")
2. Press Enter or click the "Search" button
3. The system will display 5 most relevant products

### 2. Understanding Results
Each product card displays:
- Product image (with hover zoom effect)
- Product title
- Category
- Brand
- Similarity score (0-1, where 1 is most similar)

### 3. Interacting with Results
- **Hover over cards** to see elevation effect and image zoom
- **Click on images** to view larger versions (requires backend implementation)
- **Responsive layout** automatically adjusts to screen size

### 4. Mobile Usage
- On small screens:
  - Search button moves below input field
  - Cards stack vertically
  - Font sizes adjust for readability

### 5. Accessibility Features
- Keyboard navigable (Tab/Enter)
- Screen reader friendly labels
- Semantic HTML structure
- Proper contrast ratios

## System Requirements
- Modern web browser (Chrome, Firefox, Edge, Safari)
- Internet connection (for CDN resources)
- Backend server with recommendation engine (not included)
