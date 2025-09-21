# Niyantri Coffee Website

This project contains a three-page website for Niyantri Coffee with a warm, chocolate-infused coffee theme. Pages included:

- index.html (Home)
- about.html (About the brand)
- contact.html (Contact form)

Tech & Implementation Details:

- Tailwind CSS is loaded via CDN for styling. All styling is done with Tailwind utility classes directly in HTML (no external CSS files).
- All images use placeholder syntax per requirements: src="https://images.unsplash.com/photo-1591470943257-26f29f263ee6?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw2fHwuLi58ZW58MHwwfHx8MTc1ODQ2MjUwOHww&ixlib=rb-4.1.0&q=80&w=1080" with descriptive alt text.
- Semantic HTML5 elements are used: header, nav, main, section, article, footer.
- Accessibility: descriptive alt text for images, aria-labels for sections and interactive elements.
- Interactive elements (buttons, links, cards) include Tailwind transition classes: transition-all duration-300 ease-in-out.
- A responsive, hamburger-style navigation is implemented for mobile with a playful toggle button.
- The hero section uses a full-viewport background with a semi-transparent overlay for readability.
- A testimonials section mirrors the requested structure with 5-star ratings.
- The footer is a professional 3-column layout with a subscribe form and copyright.

How to Run:

1) Open the three HTML files in a browser to view the site. No build step is required since Tailwind is loaded via CDN. 
2) If you want to customize, edit the HTML files directly. Replace placeholder images with your own assets using the same placeholder format.

Notes:
- Current date and location context is Hyderabad, Telangana, India (as of Sunday, Sep 21, 2025).
- Copyright year in the footer is 2025.
