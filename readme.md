# TaxReview Website - Design Draft

## Overview
The **TaxReview** website is designed to provide users with essential tax-related information, including articles, tax reliefs, a tax calculator, a calendar for important deadlines, and a contact form.

## Pages Structure
1. **Home (index.html)** - Displays four of the newest articles and contains anchor links to additional resources.
2. **Tax Reliefs (tax-reliefs.html)** - Lists available tax relief options in a structured list format.
3. **Calculations (calculations.html)** - Provides a tax calculator with a form containing at least five different input fields.
4. **Calendar (calendar.html)** - Displays a table of important tax deadlines and stores placeholder multimedia content.
5. **Contacts (contacts.html)** - Contains a form for users to send messages, ensuring form elements are used.

## Navigation Structure
A navigation bar is included on every page:
```
Home | Tax Reliefs | Calculations | Calendar | Contacts
```

## Implementation
TaxReview/
│── index.html
│── tax-reliefs.html
│── calculations.html
│── calendar.html
│── contacts.html
│── styles.css
└── assets/   (For images, videos, or multimedia files)

- **5 different pages:** Implemented with five distinct pages.
- **Use of a form element:** Present in the **Calculations** and **Contacts** pages.
- **At least 5 different input type elements:**
  - Number (Annual Income, Dependents - **Calculations Page**)
  - Select Dropdown (Filing Status - **Calculations Page**)
  - Email Input (**Calculations & Contacts Pages**)
  - File Upload (Tax Document Upload - **Calculations Page**)
  - Textarea (User message - **Contacts Page**)
- **Semantic markup:**
  - `header`, `nav`, `main`, `section`, `form`, `table` elements are used across the project.
- **Anchor tags & lists:**
  - `a` tags included in **Home Page** for articles.
  - Lists (`ul`, `li`) in **Tax Reliefs** and **Home** pages.
- **Table for multimedia storage:**
  - Implemented in **Calendar Page** with placeholders for images/videos/music.
- **Navigation bar:**
  - Present in all pages, ensuring smooth navigation.

## Styling (styles.css)
- **Element ID Styling:** Used for targeting specific elements uniquely.
- **Class-Based Styling:** Applied to group similar elements together.
- **All Different Selectors:** Combines element, class, and ID selectors to structure styling.
- **Flexbox Layout:** Applied for responsive design across sections.
- **Transition/Overlay Effects:** Implemented for hover effects on images and interactive elements.

## Technologies Used
- **HTML5** for page structure
- **CSS3** for styling and layout
- **Responsive Design** for mobile-friendly viewing

## Next Steps
- **Extended the existing TaxReview website with Bootstrap styling, logic, DOM events, overlays, collapsibles, functions, objects.**

- **API integration with list + single result, parsing, dynamic rendering, and Bootstrap styling.** Created a new page: api-demo.html to demonstrate API usage.
- Implemented two different API calls:
  - Numbers API: returns a fact based on a random year (task: single result).
  - Frankfurter API: returns a list of exchange rates (task: list of objects).
