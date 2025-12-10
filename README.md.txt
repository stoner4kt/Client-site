# OG EDIBLES1738 Website

This is the source code for the OG EDIBLES1738 single-page website. It showcases cannabis products, collects reviews via Firebase, and handles order inquiries via Netlify Forms.

## Project Structure

* **`index.html`**: The main landing page containing all sections (Hero, Products, Reviews, About, Contact).
* **`thank-you.html`**: The success page displayed after a form submission.
* **`images/`**: Directory for all product images and assets.
* **`sitemap.xml`**: Sitemap for search engine indexing.
* **`robots.txt`**: Instructions for search engine crawlers.

## Features

1.  **Product Tooltips**: Hovering or clicking on product cards shows detailed descriptions.
2.  **Age Gate**: A modal checks if the user is 21+ (status stored in LocalStorage).
3.  **Reviews System**: Integrated with Firebase Firestore to display and submit real-time reviews.
4.  **Order System**: A Netlify-enabled form that captures inquiries.
5.  **WhatsApp Integration**: Direct links to chat with the business.
6.  **Google Maps**: Embedded map in the footer showing general location.
7.  **Responsive Design**: Built with Tailwind CSS via CDN for mobile-first layout.

## Setup & Configuration

### 1. Firebase (Reviews)
The site uses Firebase Firestore. The configuration is located in the `<script>` tag at the bottom of `index.html`. 

### 2. Netlify Forms (Orders)
The order form has the `netlify` attribute. When deployed to Netlify, submissions will automatically appear in your Netlify dashboard under "Forms".

### 3. Google Analytics
Search for `YOUR_GA4_MEASUREMENT_ID` in the `<head>` of `index.html` and replace it with your actual Google Analytics 4 ID.

### 4. Google Search Console
Search for `YOUR_SEARCH_CONSOLE_VERIFICATION_CODE` in the `<head>` of `index.html` and replace it with your verification meta tag content.

## Deployment

This site is static HTML/JS/CSS. 
1.  **Drag and drop** this entire folder into **Netlify** to deploy.
2.  Ensure your custom domain is connected in Netlify settings.