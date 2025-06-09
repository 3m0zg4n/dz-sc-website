# TODO List (Updated)

## Project: dz-sc-website

### General Tasks
- [ ] Review and document all external code sources and their licenses
    - [ ] Visit each GitHub URL in `# Code Citations.md` and check for a LICENSE file
    - [ ] Update the citation file with license types or remove code if no license is found
- [ ] Clean up unused assets (images, CSS, JS)
    - [ ] Remove unused images from `assets/img/`, `assets/img/doctors/`, `assets/img/gallery/`, and `assets/img/testimonials/`
    - [ ] Remove unused CSS/JS files from `assets/css/` and `assets/js/`
    - [ ] Remove unused vendor libraries from `assets/vendor/`
- [ ] Refactor HTML files for consistency and accessibility
    - [ ] Ensure all pages use a consistent header, footer, and navigation
    - [ ] Use semantic HTML5 elements (header, nav, main, section, footer)
    - [ ] Add ARIA labels where appropriate
- [ ] Optimize CSS and JS for performance
    - [ ] Combine and minify CSS files
    - [ ] Combine and minify JS files
    - [ ] Defer or async load non-critical JS
- [ ] Ensure all forms (appointment, contact) are secure and validated
    - [ ] Add client-side validation to forms in `forms/`
    - [ ] Add server-side validation in `appointment.php` and `contact.php`
    - [ ] Protect forms from spam (add CAPTCHA or honeypot)
- [ ] Add alt text to all images for accessibility
    - [ ] Review all `<img>` tags in HTML files and add descriptive `alt` attributes
- [ ] Test website on multiple browsers and devices
    - [ ] Test on Chrome, Firefox, Edge, Safari
    - [ ] Test on mobile and tablet devices
- [ ] Set up favicon and meta tags for SEO
    - [ ] Add/update favicon in `assets/img/`
    - [ ] Add meta description, keywords, and Open Graph tags to all HTML files
- [ ] Minify CSS and JS for production
    - [ ] Use tools to minify `main.css` and `main.js`
- [ ] Create a README.md with project overview and setup instructions
    - [ ] Add project description, features, and setup steps
    - [ ] List dependencies and credits

### Feature-Specific Tasks
- [ ] Update or redesign the homepage (`index.html`)
    - [ ] Refresh hero section and main call-to-action
    - [ ] Update news, events, or announcements
- [ ] Review and update all service pages (e.g., `sluzba-deca.html`, `sluzba-odrasli.html`)
    - [ ] Ensure up-to-date information for each service
    - [ ] Add relevant images and contact info
- [ ] Improve navigation and internal linking
    - [ ] Add breadcrumbs if needed
    - [ ] Ensure all pages are accessible from the main menu
- [ ] Add or update testimonials and gallery sections
    - [ ] Add new testimonials in the testimonials section
    - [ ] Update gallery images and captions
- [ ] Integrate analytics (optional)
    - [ ] Add Google Analytics or other tracking code

### Deployment
- [ ] Prepare for deployment (hosting, domain setup)
    - [ ] Choose hosting provider and set up domain
    - [ ] Configure SSL certificate
- [ ] Test deployment process
    - [ ] Deploy to staging environment and test all features
    - [ ] Fix any deployment-specific issues
- [ ] Monitor for errors after launch
    - [ ] Set up error logging and monitoring
    - [ ] Periodically review site for issues

### Additional Suggestions for Improvement

#### Accessibility Improvements
- [ ] Implement keyboard navigation and focus indicators
- [ ] Use color contrast checkers to ensure text is readable for all users
- [ ] Add skip-to-content links for screen readers

#### Performance Enhancements
- [ ] Implement lazy loading for images and non-critical resources
- [ ] Use responsive images (`srcset`) for different device sizes
- [ ] Audit with tools like Google Lighthouse and address performance issues

#### Code Quality & Maintainability
- [ ] Organize CSS using methodologies like BEM or utility-first (if using frameworks)
- [ ] Split large JS files into modules for better maintainability
- [ ] Add comments and documentation to complex code sections

#### Security
- [ ] Sanitize all user inputs on both client and server sides
- [ ] Use HTTPS everywhere and set security headers
- [ ] Regularly update dependencies to patch vulnerabilities

#### User Experience
- [ ] Add loading spinners or skeleton screens for slow-loading content
- [ ] Provide clear error and success messages for all forms
- [ ] Add smooth scrolling and subtle animations for a modern feel

#### Content & SEO
- [ ] Write unique, descriptive titles and meta descriptions for each page
- [ ] Add structured data (JSON-LD) for better search engine understanding
- [ ] Create a sitemap.xml and robots.txt for search engines

#### Analytics & Feedback
- [ ] Set up event tracking for key actions (form submissions, button clicks)
- [ ] Add a feedback form or survey for users to report issues or suggestions

#### Progressive Web App (PWA)
- [ ] Add a manifest.json and service worker for offline support and installability
- [ ] Test the site as a PWA and address any issues

#### Backup & Version Control
- [ ] Ensure the project is under version control (e.g., Git) with regular commits
- [ ] Set up automated backups for critical files and databases (if any)

#### Documentation
- [ ] Expand the README with screenshots, usage examples, and contribution guidelines
- [ ] Document the deployment process and environment variables

---
_Adapt this template for future projects as needed._
