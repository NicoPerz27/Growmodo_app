Custom WordPress Real Estate Theme
Overview

This project is a custom WordPress theme developed based on a provided Figma design. It includes dynamic content, custom post types, responsive layouts, Swiper.js carousels, and fully editable property data using ACF fields.

The goal was to replicate the UI as closely as possible within a 4-hour time-boxed technical test, focusing on clean structure, dynamic data, and performance-friendly code.

Features
✔ Custom WordPress Theme

Fully hand-coded theme (no builders).

Responsive layout matching the Figma design.

Shared header/footer + page-specific sections.

✔ Custom Post Type: Properties

property CPT with archive and single templates.

Custom fields for price, description, address, bedrooms, bathrooms, type, and 5 images.

Managed with ACF (free version).

✔ Dynamic Property Carousel

Swiper.js slider integrated dynamically.

Breakpoints: 1 slide (mobile), 2 slides (tablet), 3 slides (desktop).

Custom navigation styling.

✔ Menus

Primary navigation.

Multi-column footer menus (dynamic via WP Menu Manager).

✔ Styling & Performance

Clean CSS with variables.

Mobile-first responsive layout.

Minimal JS, only for Swiper and menu behavior.

Tech Stack

WordPress

PHP

HTML5 / CSS3

JavaScript

Swiper.js

ACF (Free)

Google Fonts

Installation

Clone the repository into /wp-content/themes/.

Activate the theme from the WordPress Admin Panel.

Install and activate Advanced Custom Fields (ACF).

Go to Appearance → Menus and assign all theme menu locations.

Add properties in Properties → Add New.

Development Choices

Custom theme vs. child theme:
A ground-up custom theme was chosen for full design control.

ACF for property data:
Allows fast structured content without writing custom meta boxes.

Swiper.js for sliders:
Lightweight, responsive, and configurable.

CSS custom variables:
Ensures consistent theming and easier maintenance.

Demo

Provide either:

Live URL, or

Instructions for running locally using LocalWP / XAMPP / MAMP.
