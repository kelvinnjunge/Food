# Omnifood — AI-Powered Meal Subscription Website

Omnifood is a responsive food subscription website concept that helps users discover personalized, healthy meals delivered to their door. The website presents meal plans, recipes, customer testimonials, pricing options, and a sign-up form.

## Table of Contents

- [Omnifood — AI-Powered Meal Subscription Website](#omnifood--ai-powered-meal-subscription-website)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [Project Structure](#project-structure)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Website Sections](#website-sections)
    - [1. Hero](#1-hero)
    - [2. Featured In](#2-featured-in)
    - [3. How It Works](#3-how-it-works)
    - [4. Meals](#4-meals)
    - [5. Testimonials and Gallery](#5-testimonials-and-gallery)
    - [6. Pricing](#6-pricing)
    - [7. Features](#7-features)
    - [8. Sign-Up](#8-sign-up)
    - [9. Footer](#9-footer)
  - [Responsive Design](#responsive-design)
  - [Sign-Up Form](#sign-up-form)
  - [Customization](#customization)
  - [Future Improvements](#future-improvements)
  - [License](#license)

## Overview

Omnifood demonstrates the design and development of a modern food subscription landing page. It uses HTML, CSS, and JavaScript to create a user-friendly experience across desktop, tablet, and mobile devices.

The website focuses on healthy eating, personalized meal recommendations, convenient delivery, and flexible subscription plans.

## Features

- **Hero section:** Introduces the service with a headline, call-to-action buttons, and customer imagery.
- **Featured publications:** Displays logos of publications featuring the brand.
- **How it works:** Explains the three-step meal subscription process.
- **Meal selection:** Showcases meals with dietary tags, calorie information, nutrition scores, and ratings.
- **Dietary preferences:** Lists supported diets, including vegetarian, vegan, pescatarian, gluten-free, keto, and paleo.
- **Customer testimonials:** Displays customer feedback and experiences.
- **Food gallery:** Presents a collection of food photographs.
- **Pricing plans:** Compares Starter and Complete subscription options.
- **Service benefits:** Highlights convenience, organic ingredients, reduced waste, and subscription flexibility.
- **Sign-up form:** Collects customer names, email addresses, and referral sources.
- **Footer navigation:** Provides contact details, social media links, account navigation, and company resources.
- **Mobile navigation:** Includes a menu button for smaller screens.
- **Smooth scrolling:** Improves navigation between sections.

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and semantic content |
| CSS3 | Styling, layouts, and responsive presentation |
| JavaScript | Interactive behavior and navigation |
| Google Fonts — Rubik | Typography |
| Ionicons | Icons throughout the website |
| Smooth Scroll Polyfill | Smooth scrolling support for older browsers |
| Netlify Forms | Form handling when deployed and configured on Netlify |

## Project Structure

The project uses the following file organization:

```text
omnifood/
├── index.html
├── manifest.webmanifest
├── css/
│   ├── general.css
│   ├── style.css
│   └── queries.css
├── js/
│   └── script.js
└── img/
    ├── favicon.png
    ├── apple-touch-icon.png
    ├── omnifood-logo.png
    ├── hero.png
    ├── app/
    │   ├── app-screen-1.png
    │   ├── app-screen-2.png
    │   └── app-screen-3.png
    ├── customers/
    ├── gallery/
    ├── logos/
    └── meals/
        ├── meal-1.jpg
        └── meal-2.jpg
```

**Note:** This structure represents the assets referenced by the supplied HTML. Ensure all directories and files exist in your local project.

## Getting Started

### Prerequisites

You need:

- A modern web browser.
- A code editor, such as Visual Studio Code.
- The project's HTML, CSS, JavaScript, and image assets.

### Installation

1. Clone or download the project repository.
2. Open the project folder in your code editor.
3. Confirm that the `css`, `js`, and `img` directories contain the referenced files.
4. Open `index.html` in your browser.

For a better local development experience, use the **Live Server** extension in Visual Studio Code:

1. Install Live Server.
2. Open `index.html`.
3. Right-click the file and select **Open with Live Server**.

The website should open in your browser.

## Website Sections

### 1. Hero

Introduces Omnifood with the headline:

> A healthy meal delivered to your door, every single day.

Includes links to start a subscription and learn how the service works.

### 2. Featured In

Displays publication logos to represent media recognition.

### 3. How It Works

Explains the subscription process:

1. Tell Omnifood your food preferences.
2. Review and approve your weekly meal plan.
3. Receive meals at a convenient time.

### 4. Meals

Showcases example dishes, including Japanese Gyozas and Avocado Salad. Each meal includes dietary labels and nutritional information.

### 5. Testimonials and Gallery

Displays customer testimonials alongside a visual gallery of meals and food photography.

### 6. Pricing

The HTML defines two example subscription plans:

| Plan | Monthly Price | Meals |
|---|---:|---|
| Starter | $399 | One meal per day |
| Complete | $649 | Two meals per day |

These are sample prices from the website content and should be updated to reflect actual business pricing before launch.

### 7. Features

Highlights the main benefits of the service, such as daily meal availability, local and organic ingredients, reusable packaging, and subscription flexibility.

### 8. Sign-Up

Collects:

- Full name
- Email address
- Referral source

The form includes required-field validation through HTML attributes.

### 9. Footer

Contains contact information, social media links, account links, company information, and helpful resources.

## Responsive Design

The website separates its CSS into three files:

- `general.css` — shared styles, typography, reusable layouts, and utility classes.
- `style.css` — primary component and section styles.
- `queries.css` — media queries for adapting layouts to different screen sizes.

The `viewport` meta tag ensures the layout uses the device's actual viewport width:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

Test the website on desktop, tablet, and mobile screen sizes to verify that navigation, grids, images, and forms remain usable.

## Sign-Up Form

The supplied HTML uses a Netlify-compatible form:

```html
<form class="cta-form" name="sign-up" netlify>
```

The form collects customer information and uses HTML validation. To receive submissions, deploy the site to Netlify and ensure form detection is enabled. Test a production submission to confirm that the form is detected and submissions are recorded.

For other hosting providers, configure an appropriate backend or form-processing service.

**Important:** The form does not, by itself, implement a complete subscription system. User accounts, payments, meal personalization, delivery scheduling, and database storage would require additional development.

## Customization

You can customize the website by editing the following files:

- `index.html` — page content, section headings, meal information, and links.
- `css/general.css` — common styles and reusable layout rules.
- `css/style.css` — colors, spacing, buttons, cards, and section appearance.
- `css/queries.css` — responsive breakpoints and mobile layouts.
- `js/script.js` — mobile navigation and other interactive behaviors.
- `img/` — logos, food photography, customer portraits, and application screenshots.

You can also update the Google Fonts import, icon library, pricing, contact information, and social media URLs.

## Future Improvements

Potential enhancements include:

- Connect the sign-up form to a database or customer management platform.
- Add user authentication and account management.
- Integrate online payments and subscription management.
- Implement personalized meal recommendations.
- Add a searchable recipe directory.
- Provide meal ordering and delivery scheduling.
- Improve accessibility with keyboard navigation and clear focus indicators.
- Optimize images and implement lazy loading.
- Add SEO metadata, analytics, and performance monitoring.
- Configure privacy, consent, and data-protection features.

## License

No license information was provided with the supplied HTML. Add a `LICENSE` file if you intend to distribute or reuse the project publicly, and confirm the licensing terms of any third-party assets.

---

**Project:** Omnifood  
**Type:** Responsive food subscription landing page  
**Primary technologies:** HTML, CSS, and JavaScript  
**Status:** Front-end website concept
