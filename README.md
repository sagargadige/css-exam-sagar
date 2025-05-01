# css-exam-sagar
User Profile Web Page with Footer
Developed by: Sagar Gadige

Introduction
This project is a simple yet visually appealing web page that serves as a user profile interface. It is designed using HTML and CSS and focuses on displaying essential user information in a structured and styled format. The web page includes a main profile section and a fixed footer. The layout is enhanced with background images and social media icons to give it a professional look. The goal of the project is to practice and demonstrate fundamental front-end development skills.

Objective
The primary objective of this project is to create a user profile page that contains the user's personal and professional details, along with contact information and links to social media platforms. The project also aims to implement a footer that remains fixed at the bottom of the screen, regardless of the page scroll position. This helps in maintaining visibility of key contact information at all times.

Technologies Used
The project is built using the following technologies:

HTML5 is used for the structure and content of the web page.

CSS3 is used for styling, layout, and responsiveness.

Font Awesome is used to include icons for GitHub, Facebook, and Twitter.

Project Structure
The project consists of the following files and folders:

index.html: The main HTML file that contains the structure of the webpage.

css/style.css: The CSS file that includes all the styles and design rules for the page.

images/: This folder contains the profile picture (profile pic.png) and the background image (background-img.jpg).

fontawesome-free-6.7.2-web/: This folder contains the local files for Font Awesome icons.

Profile Section
The profile section is placed inside a styled container that is centered on the page using CSS Flexbox. It contains a circular profile image followed by the user's full name and job title. Below that, there are personal details such as the job role, department, office phone, mobile number, and email. At the bottom of the profile section, there are social media icons that link to the user's GitHub account, and placeholders for Facebook and Twitter icons.

The design of the profile card uses a semi-transparent gray background with rounded corners and a box shadow to give a modern look. The section is scrollable if the content exceeds the height limit, thanks to the overflow-y: scroll property.

Footer Section
The footer is fixed to the bottom of the page and spans the full width of the screen. It includes the user's address and additional social media links. The content is styled using Flexbox for layout, with the address on the left and icons on the right. The background color matches the main profile card to maintain a consistent visual theme.

Styling and Design
The overall design features a full-page background image that covers the entire viewport and does not repeat. The main container has a maximum width to keep the layout centered and readable on different screen sizes. Font families, sizes, colors, and spacing are consistently used throughout the page for a clean and readable appearance.

Font Awesome icons are used for social media and are linked both through local files and CDN for better accessibility. The design ensures that even if the user is offline, the icons will still display properly using the local Font Awesome setup.

Responsiveness
While the page is mostly static, basic responsive techniques such as Flexbox and max-width containers are used to ensure it looks good on larger screens. Future enhancements can include media queries to improve the display on mobile and tablet devices.

How to Run the Project
Download and extract the project folder.

Ensure that all related folders like css, images, and fontawesome are present and correctly linked.

Open index.html using any web browser to view the web page.

Future Enhancements
There are several opportunities to improve this project in the future. Adding full mobile responsiveness using media queries would enhance usability on smaller devices. Including additional sections such as skills, experience, or a portfolio would turn this into a more complete profile page. A contact form and animations could also improve the interactivity and user engagement.

Conclusion
This project demonstrates a foundational understanding of front-end development using HTML and CSS. It focuses on layout design, styling techniques, and the integration of external resources like icons. With a professional layout and clear structure, this user profile page serves as a strong base for further development and customization.