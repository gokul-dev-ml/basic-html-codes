Responsive Footer (Bootstrap 4)

This project implements a fully responsive website footer using Bootstrap 4 and custom CSS.

The layout adapts correctly across mobile, tablet, and desktop screen sizes.

📌 Features

Responsive grid layout using Bootstrap 4

Mobile-first design

Social media icons with circular background

Clean typography and spacing

Dark-themed footer

Fully semantic and valid HTML structure

🛠️ Technologies Used

HTML5

CSS3

Bootstrap 4.5.2

SVG Icons

📐 Layout Structure

The footer follows the Bootstrap grid rules strictly:

.container

 └── .row

      ├── .col-12 col-lg-4   
      └── .col-12 col-lg-4

           └── .row

                ├── Column 1 (Get to know us)

                ├── Column 2 (Contact with us)

                └── Column 3 (Let us help you)

This structure ensures:

Stacking on mobile

Two columns on tablets

Three columns on desktops

📱 Responsiveness Behavior

Screen SizeLayoutMobile (<576px)All sections stack verticallyTablet (≥768px)Footer links appear in two columnsDesktop (≥992px)Footer links appear in three columns🎨 Styling Overview

Background

Dark blue background (#0d2436)

Icons

Circular icon containers

SVG icons centered using Flexbox

Muted icon color for professional look

Typography

Headings use larger font size and bold weight

Links styled using .para class

Consistent spacing for readability

📂 File Structure

project-folder/

│

├── index.html

├── style.css

└── README.md

✅ Best Practices Followed

Proper container → row → col hierarchy

No invalid Bootstrap nesting

Mobile-first column definitions

No conflicting utility classes

Clean separation of HTML and CSS



📌 Notes

Bootstrap JavaScript is not required for this footer

SVG icons are embedded directly for performance

Easy to customize colors, spacing, or text


<img width="300" height="588" alt="Screenshot 2026-01-20 161902" src="https://github.com/user-attachments/assets/b2866d6e-1d26-4968-882c-7bb4bb951971" /><img width="583" height="377" alt="Screenshot 2026-01-20 161913" src="https://github.com/user-attachments/assets/a3501488-0b07-4285-90b7-48ae37f304dc" />
<img width="588" height="206" alt="Screenshot 2026-01-20 161924" src="https://github.com/user-attachments/assets/02daf15d-7b93-4e08-9fe3-d7dbc24c71fa" />
