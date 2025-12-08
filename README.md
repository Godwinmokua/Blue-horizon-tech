Blue Horizon Tech - Complete 8-Page Static Website
📋 Project Overview
Blue Horizon Tech is a fully responsive 8-page static website for a fictional technology company, built exclusively with HTML and CSS (no JavaScript). This project demonstrates modern web design principles, mobile-first responsive design, and interactive elements using pure CSS techniques.

🎯 Project Requirements Met
✅ 8 interconnected pages with smooth navigation
✅ No frameworks - Pure HTML and CSS only
✅ No JavaScript - All interactivity achieved with CSS
✅ Mobile responsive design with CSS media queries
✅ Modern, professional design with consistent styling
✅ No templates - All code written from scratch
✅ Uses only concepts covered in introductory web development classes

📁 Pages Included
Home (index.html) - Landing page with hero section and company overview
About Us (about.html) - Company history, mission, values, and timeline
Services (services.html) - Technology services and solutions offered
Products (products.html) - Software products catalog and comparisons
Our Team (team.html) - Team member profiles and department overview
Projects (projects.html) - Project portfolio with case studies
Contact (contact.html) - Contact form and company information
Resources (resources.html) - Guides, whitepapers, tools, and FAQ

🎨 Design Features
Color Scheme
Primary: Deep Blue (#1a365d)
Secondary: Light Blue (#4fc3f7)
Accent: Medium Blue (#2d4d7a)
Background: Light Gray (#f8f9fa)
Text: Dark Gray (#333)

Typography
Primary Font: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
Clean, readable typography with proper hierarchy
Responsive font sizes for all screen sizes

Layout Components
Sticky header with navigation
Hero sections with gradient backgrounds
Card-based content presentation
CSS Grid and Flexbox for responsive layouts
Consistent spacing and alignment

📱 Responsive Design
Mobile-First Approach
Base styles for mobile devices
Media queries for tablets (768px) and desktops (1200px)
Fluid layouts that adapt to all screen sizes

CSS-Only Mobile Menu
Checkbox hack technique for toggle functionality
Smooth transitions with max-height animation
Touch-friendly navigation items

✨ Interactive Elements (CSS Only)
1. Mobile Navigation
css
/* Hidden checkbox controls menu visibility */
#menu-toggle:checked ~ nav {
    max-height: 500px;
    padding: 1rem 0;
}
2. Tabbed Content (Projects & Resources)
css
/* Radio buttons control which content to display */
.tab-input:checked ~ .category-content {
    display: grid;
}
3. FAQ Accordion
css
/* Checkbox controls answer visibility */
.faq-input:checked + .faq-question + .faq-answer {
    max-height: 500px;
    padding: 1.5rem;
}
4. Hover Effects
Button hover with transform and shadow

Card hover with lift effect

Navigation hover with background color change

🛠️ Technical Implementation
File Structure
text
blue-horizon-tech/
│
├── index.html          # Home page
├── about.html          # About Us page
├── services.html       # Services page
├── products.html       # Products page
├── team.html           # Our Team page
├── projects.html       # Projects page
├── contact.html        # Contact page
└── resources.html      # Resources page
CSS Architecture
CSS Reset for consistent baseline

Global styles for typography and colors

Component-based styling
Media queries organized by breakpoint
Reusable utility classes (btn, container, etc.)

Performance Optimizations
Internal CSS (no external requests)
Efficient selectors and minimal repetition
Optimized images using emoji placeholders
Minimal HTTP requests

📐 Layout Techniques
1. CSS Grid
css
/* Responsive grid layouts */
.grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

2. Flexbox
css
/* Flexible component layouts */
.flex-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

3. Positioning
Sticky headers for easy navigation
Absolute positioning for decorative elements
Relative positioning for contained layouts

🎓 Educational Value
This project demonstrates core web development concepts:

HTML Skills
Semantic HTML5 elements
Form structure and input types
Table markup for data presentation
Accessible markup practices

CSS Skills
Box model and layout fundamentals
CSS Grid and Flexbox for modern layouts
Responsive design with media queries
CSS transitions and transforms
Advanced selectors and specificity
CSS-only interactivity techniques

🚀 How to Use
Viewing the Website
Clone or download the project files
Open index.html in any modern web browser
Navigate between pages using the header menu
Test responsiveness by resizing the browser window

Modifying the Project
Edit HTML files to change content
Modify CSS within each HTML file's <style> tag
Add new pages by copying an existing page structure
Update colors by changing the CSS custom properties

📝 Browser Compatibility
✅ Chrome (latest)
✅ Firefox (latest)
✅ Safari (latest)
✅ Edge (latest)
✅ Mobile browsers (iOS Safari, Chrome Mobile)

🔧 Customization Tips
Changing Colors
css
/* Update these variables in each page's CSS */
:root {
    --primary: #1a365d;
    --secondary: #4fc3f7;
    --accent: #2d4d7a;
}

Adding New Pages
Copy an existing HTML file
Update the navigation active state
Change page title and content
Update footer links if needed
Adding More Interactive Features
Use radio buttons for tabbed interfaces
Use checkboxes for toggle functionality
Use :target pseudo-class for single-page navigation
Use :hover and :focus states for accessibility

📚 Learning Resources Demonstrated
Responsive Web Design Fundamentals
CSS Layout Techniques (Grid, Flexbox)
CSS Selectors and Specificity
CSS Transitions and Animations
Form Styling and Validation
Typography and Color Theory
Accessibility Best Practices
Mobile-First Development

🏆 Project Achievements
Complete 8-page website with consistent design
Fully responsive on all device sizes
Interactive elements without JavaScript
Clean, maintainable code structure
Professional appearance suitable for real business use
Educational value for web development students

📄 License & Usage
This project is created for educational purposes as part of a web development course. The code is free to use for learning and portfolio purposes. All content and design are original creations.

Created by: Godwin Mokua Obiria
Course: Web Development Fundamentals
Date: December 2023
Purpose: Capstone Project - Static Website Implementation