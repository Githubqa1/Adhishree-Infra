# RMC Concrete Plant Website

A professional website template for Ready Mix Concrete (RMC) plant businesses. This template provides a complete structure with all essential pages and modern, responsive design.

## 📁 Project Structure

```
/rmc-website
│
├── index.html          → Home page
├── about.html          → About Us page
├── products.html       → Concrete Grades page
├── services.html       → Services page
├── projects.html       → Projects showcase
├── quality.html        → Quality & Testing page
├── contact.html        → Contact page
│
├── css/
│   └── style.css       → Main stylesheet
│
├── js/
│   └── main.js         → JavaScript functionality
│
├── images/
│   ├── hero.jpg        → Hero section image
│   ├── plant.jpg       → Plant image
│   ├── projects/       → Project images folder
│   └── products/       → Product images folder
│
└── README.md           → This file
```

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **7 Complete Pages**: All essential pages for an RMC plant website
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Ready-to-use contact form (backend integration needed)
- **SEO Friendly**: Semantic HTML structure
- **Easy Customization**: Well-organized code with clear comments

## 📄 Pages Overview

### 1. **Home (index.html)**
   - Hero section with call-to-action
   - Features section highlighting key benefits
   - About preview section
   - Footer with quick links

### 2. **About Us (about.html)**
   - Company story and background
   - Core values section
   - Plant information

### 3. **Concrete Grades (products.html)**
   - Display of various concrete grades (M10 to M50)
   - Specifications for each grade
   - Use cases and applications

### 4. **Services (services.html)**
   - Comprehensive service offerings
   - Service details and benefits
   - Call-to-action section

### 5. **Projects (projects.html)**
   - Portfolio of completed projects
   - Project details and specifications
   - Image gallery for projects

### 6. **Quality & Testing (quality.html)**
   - Quality assurance processes
   - Testing procedures
   - Industry standards compliance
   - Quality features

### 7. **Contact (contact.html)**
   - Contact information
   - Contact form
   - Map placeholder section

## 🎨 Customization Guide

### Adding Your Content

1. **Replace Placeholder Text**
   - Search for `[Your Address]`, `[Your Phone]`, `[Your Email]` in all HTML files
   - Replace with your actual contact information

2. **Add Images**
   - Replace `images/hero.jpg` with your hero image
   - Replace `images/plant.jpg` with your plant image
   - Add product images to `images/products/` folder
   - Add project images to `images/projects/` folder
   - Update image paths in HTML files accordingly

3. **Update Company Information**
   - Edit company name in navigation and footer
   - Update about section with your company story
   - Modify services and products as per your offerings

4. **Customize Colors**
   - Edit CSS variables in `css/style.css`:
     ```css
     :root {
         --primary-color: #2c3e50;
         --secondary-color: #3498db;
         --accent-color: #e74c3c;
     }
     ```

### Contact Form Integration

The contact form currently shows an alert on submission. To make it functional:

1. **Option 1: Use a Form Service**
   - Integrate with services like Formspree, Netlify Forms, or EmailJS
   - Update the form action in `contact.html`

2. **Option 2: Backend Integration**
   - Create a backend endpoint to handle form submissions
   - Update the form submission handler in `js/main.js`

### Adding Google Maps

1. Get your Google Maps embed code
2. Replace the map placeholder in `contact.html`:
   ```html
   <div class="map-placeholder">
       <!-- Paste your Google Maps embed code here -->
   </div>
   ```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Vanilla JS for interactivity
- **Responsive Design**: Mobile-first approach

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Setup Instructions

1. **Download/Clone** the project files
2. **Open** `index.html` in a web browser to view the website
3. **Customize** the content, images, and styling as needed
4. **Test** on different devices and browsers
5. **Deploy** to your web hosting service

## 📝 Notes

- All images are placeholders - replace with your actual images
- Contact form requires backend integration for full functionality
- Map section needs Google Maps embed code
- Update all placeholder text with your actual information
- Consider adding a favicon for better branding

## 🎯 Next Steps

1. Add your company logo
2. Replace all placeholder images
3. Update all text content with your information
4. Integrate contact form with backend
5. Add Google Maps to contact page
6. Test on various devices
7. Deploy to hosting service
8. Set up domain and SSL certificate

## 📞 Support

For customization help or questions, refer to the code comments or consult with a web developer.

---

**Note**: This is a template. Make sure to replace all placeholder content with your actual business information before going live.

