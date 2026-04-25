# AI Agent Instructions for A/C-K Service Website

## Project Overview
This is a static air conditioning repair service website built with HTML, SCSS, JS, and PHP for contact form. No build tools required - pure static site with manual SCSS compilation.

## Key Conventions
- **File Structure**: HTML pages in root, styles in `scss/` (source) and `css/` (compiled), JS in `js/`, libraries in `lib/`
- **Styling**: Use SCSS variables for colors (#DA9F5B primary, #33211D secondary), custom components like .section-title, .btn-square
- **JavaScript**: jQuery-based, main.js handles nav, carousels, animations
- **Forms**: Client validation with jqBootstrapValidation, server with PHP

## Development Workflow
- Edit `scss/style.scss`, compile to `css/style.css` manually
- Test contact form requires PHP server
- Update hardcoded email in `mail/contact.php` before deployment

## Common Pitfalls
- Both minified and non-minified CSS loaded - remove one
- Hardcoded recipient email in contact.php
- No CSRF protection on forms
- Bootstrap 4 is EOL

## Links
- [README.md](README.md) - Project description
- [git_flow.md](git_flow.md) - Branching strategy
- [scss/style.scss](scss/style.scss) - Style source and patterns
- [js/main.js](js/main.js) - Main script
- [mail/contact.php](mail/contact.php) - Backend form handling

## Skills Available
- frontend-design: For creating distinctive web interfaces
- responsive-design: For responsive layouts