Responsive Landing Page – Bootstrap 4

A modern, responsive landing page built using HTML5, CSS3, and Bootstrap 4, featuring a custom navigation bar, full-screen hero section, responsive typography, and device-specific word breaking for optimal readability.

✨ Features

Responsive Navbar

Collapsible navigation for mobile devices

Right-aligned navigation links on larger screens

Custom background color overriding Bootstrap defaults

Hero Section

Full viewport height (100vh) background image

Centered content using Flexbox

Clean typography with Google Fonts

Device-Specific Word Breaking

Uses <wbr> for controlled line breaks

Line breaks enabled only on large screens (≥1200px)

Prevents awkward text wrapping on smaller devices

Mobile-First Design

Built with Bootstrap’s grid and utility classes

Responsive margins and spacing (mt-md-*, ml-md-*, etc.)

🛠️ Technologies Used

HTML5

CSS3

Bootstrap 4.5

Google Fonts

Flexbox

📂 Project Structure

├── index.html

├── styles.css

└── README.md

🎯 Key Implementation Details

Navbar Background Override

Bootstrap’s default bg-dark class was intentionally removed and replaced with a custom class:

.bg2 {

    background-color: #0c0521;

}

This ensures predictable styling without relying on !important.

Full-Screen Hero Section

.bg {

    background-image: url("...");

    background-size: cover;

    background-position: center;

    height: 100vh;

}

The hero content is vertically and horizontally centered using Flexbox.

Responsive Word Breaking (Advanced)

To control where text breaks only on large screens, the <wbr> tag is used:

<wbr>

wbr {

    display: none;

}



@media (min-width: 1200px) {

    wbr {

        display: inline;

    }

}

✅ This avoids forcing breaks on mobile

✅ Provides precise control over text flow

✅ Industry-standard approach for headings and hero text


📱 Responsive Breakpoints Used



Avoided !important

Used semantic HTML

Followed mobile-first principles

Clean separation of concerns (HTML vs CSS)

Predictable, scalable CSS rules




<img width="509" height="664" alt="Screenshot 2026-01-21 201754" src="https://github.com/user-attachments/assets/c809fdd3-c9ff-4e98-8b1b-293d6428acaf" />
<img width="866" height="554" alt="Screenshot 2026-01-21 202627" src="https://github.com/user-attachments/assets/e0b1d286-051a-4223-ac55-c524d3c72e52" />
<img width="478" height="616" alt="Screenshot 2026-01-21 201824" src="https://github.com/user-attachments/assets/6da8f0e1-31eb-4e49-aaa2-d08e7069153b" />
