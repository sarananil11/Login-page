Responsive Login Page
This project is a responsive login page built using HTML, CSS, and Bootstrap 5.3.8. It features a two-column layout with social media login options on the left and an email/password login form on the right. The design is fully responsive, adapting to various screen sizes, including mobile, tablet, and desktop devices.
Features

Responsive Design: Utilizes Bootstrap's grid system to ensure the layout adjusts seamlessly across different screen sizes.
Social Media Login: Buttons for signing up with Facebook, Twitter, and Google.
Email/Password Login: A form with email and password fields, a "Remember me" checkbox, and a "Forgot password" link.
Modern Styling: Clean and professional design with a gradient background, rounded corners, and a shadow effect.
Scalable Typography: Uses clamp() for font sizes to ensure readability on all devices.
Bootstrap Icons: Includes icons for social media buttons to enhance the user interface.

Files

index.html: The main HTML file containing the structure of the login page.
style.css: Custom CSS to style the layout, with responsive adjustments for font sizes, padding, and layout stacking.

Setup Instructions

Clone or Download: Download the project files (index.html and style.css) to your local machine.
Place Files: Ensure index.html and style.css are in the same directory.
Open the Page: Open index.html in a web browser to view the login page.
No additional server setup is required, as the page uses CDN-hosted Bootstrap CSS, JavaScript, and Bootstrap Icons.

Customize (Optional):
Modify style.css to adjust colors, fonts, or other styles.
Update index.html to change button text, links, or form actions as needed.

Dependencies

Bootstrap 5.3.8: Loaded via CDN for CSS and JavaScript.
Bootstrap Icons: Loaded via CDN for social media icons.
No local dependencies or installations are required.

Usage

The left column provides buttons for social media signups (Facebook, Twitter, Google).
The right column contains a form for email/password login, with options to remember the user or recover a forgotten password.
On mobile devices (below 768px), the two columns stack vertically for better usability.
The page is centered on the screen with a gradient background for a modern look.

Notes

The form's action attribute is empty by default. Update it to point to your backend endpoint for form submission.
The social media buttons are placeholders. Add appropriate URLs or JavaScript functionality for actual social media login integration.
The "Forgot password" and "Sign Up Free!" links are placeholders. Update their href attributes to point to relevant pages.

Responsive Behavior

Desktop (≥768px): Two-column layout with social media buttons on the left and the login form on the right.
Mobile (<768px): Columns stack vertically, with adjusted padding and font sizes for better readability.
Typography: Font sizes use clamp() to scale smoothly across screen sizes.
Buttons and Inputs: Full-width elements ensure easy interaction on touch devices.
