# Claude Suggested Improvements for Portfolio Website

This document contains suggestions for improving the Skyler Reising portfolio website, generated on 2025-11-26.

## SEO & Discoverability

1. **Add structured data** - Consider JSON-LD schema for Person/Professional profile

## Performance

1. **External Font Awesome CDN** - index.html:36 loads from external source. Consider self-hosting or using only needed icons if further optimization needed

## Content Enhancements

1. **Add more projects** - Currently showing 3 projects; consider adding more or linking to detailed project pages
2. **Add resume/CV download** - No way to download your resume
3. **Expand project descriptions** - Consider adding more detail to existing projects
4. **Add blog section** - Optional, but could showcase technical writing

## Functionality

1. **Form for contact** - Currently only has email link; consider adding a contact form
2. **Analytics** - No Google Analytics or similar tracking detected
3. **Dark mode toggle** - Popular feature for developer portfolios
4. **Loading states** - Consider adding skeleton screens or loading indicators

## Modern Web Standards

1. **Add manifest.json** - Enable "Add to Home Screen" on mobile
2. **Consider PWA features** - Service worker for offline functionality
3. **Security headers** - If deploying, add Content-Security-Policy, X-Frame-Options, etc.

## Mobile Responsiveness

1. **Test on actual devices** - The template should be responsive, but verify all content displays well
2. **Mobile navigation** - Verify the hamburger menu works smoothly

## Social Links

1. **Consider adding more platforms** - Stack Overflow, Dev.to, Medium if applicable

## Priority Recommendations

If you want to tackle these incrementally, here's the suggested order:

1. **Add resume/CV download**
2. **Add structured data for SEO**
3. **Add more project content**

## File References

- Main page: `index.html`
- Main stylesheet: `assets/css/main.css`
- Main JavaScript: `assets/js/main.js`
- Images directory: `images/`

## Notes

- The site uses the "Stellar" template by HTML5 UP
- Current dependencies: jQuery, Font Awesome, custom scrolling libraries
- The site appears to be a single-page application with smooth scrolling navigation
