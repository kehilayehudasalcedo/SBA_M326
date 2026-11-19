# Frontend Mentor - Hotel booking confirmation page solution
This is my solution to the Hotel booking confirmation page challenge on Frontend Mentor
https://www.frontendmentor.io/challenges/hotel-booking-confirmation-page

# The challenge
For this project, I built a responsive hotel booking confirmation page for "Maison Soleil". 

# Approach and Customizations
In brief, to build this page, I followed these steps:
.1. HTML Structure - I organized the original text into semantic HTML tags (<aside>, <main>, <header>, <section>, and <article>).
.2. Bootstrap - I used Bootstrap's 12-column grid system to separate the left sidebar from the main content. I also used Bootstrap cards, buttons, badges, and flexbox utilities (d-flex, justify-content-between)
.3. Custom CSS (style2.css) - I created a small CSS file to add the exact HSL colors from style-guide.

# Challenges and Solutions

.1  Tilting the receipt and welcome cards without breaking the mobile view.
Tilting the cards on a small phone screen made them overlap awkwardly. I used a CSS media query (@media (min-width: 768px)) so the transform: rotate() effect only turns on for tablets and desktop computers.

.2 Learning the layout tools outside of class.
Since we did not have enough hands-on practice with these specific Bootstrap components in class, I used VS Code, Live Server, and the official Bootstrap documentation on my own time to test how each class worked until the layout matched the design images.


## Reflection

# Challenges
One of the main challenges I encountered during this project was implementing Bootstrap's responsive grid, collapsible navigation, and overlapping card layouts without prior hands-on practice during class sessions. To overcome this gap, I dedicated extra hours outside of class—sacrificing sleep—to independently study the official Bootstrap documentation and test different layout behaviors using VS Code.

# Approach for challenges
Relying on official documentation proved to be the most effective approach to understanding how utility classes, flexbox containers, and breakpoints interact across mobile and desktop viewports.

# Improvements
If given more time and a more focused, practical learning environment, I would deepen my understanding of advanced CSS positioning and JavaScript interactivity. Specifically, I would implement functional clipboard copying for the Wi-Fi password, create a print-friendly stylesheet for the receipt, and refine the hover animations for the layered cards.
