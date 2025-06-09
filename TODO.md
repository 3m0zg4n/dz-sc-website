# TODO List

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

---
_Adapt this template for future projects as needed._
