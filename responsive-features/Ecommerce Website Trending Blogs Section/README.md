📰 Trending Blogs Section – Bootstrap 4

📌 Overview

This project implements a responsive “Trending Blogs” section for a website using Bootstrap 4 and custom CSS.

It displays featured blog cards with images, categories, titles, short descriptions, and a clear “Read More” action.

The layout is designed to be clean, readable, and mobile-friendly, following modern UI practices.

🧩 Technologies Used

HTML5

CSS3

Bootstrap 4.5.2

Google Fonts (Roboto)

🧭 Layout Structure

1️⃣ Container & Grid System

Uses Bootstrap’s container → row → column structure

Responsive column layout:

col-12 → mobile view

col-lg-6 → two-column layout on large screens

<div class="col-12 col-lg-6 col-md-12">

2️⃣ Section Heading

Section title spans full width

Styled for clarity and hierarchy

<h1>Trending Blogs</h1>

3️⃣ Blog Cards

Each blog is displayed inside a Bootstrap card containing:

Blog image

Category label

Blog title

Short description

“READ MORE” call-to-action with icon

<div class="card">

  <img class="image" />

  <p class="paragraph-Amazon">Category</p>

  <h1>Blog Title</h1>

  <p class="paragraph">Description...</p>

</div>

4️⃣ Images

Fixed height to maintain consistency

Width adjusts automatically to preserve aspect ratio

.image {

  height: 190px;

  width: auto;

}

5️⃣ Typography & Styling

Font family: Roboto

Clear color contrast for readability

Category, description, and CTA text styled separately for hierarchy

.readmore {

  color: #ff9f00;

  font-weight: 600;

}

6️⃣ Call-to-Action Button

A “View All” button aligned to the right for easy navigation.

<button>View All</button>

📱 Responsive Behavior

Cards stack vertically on mobile

Cards display side-by-side on larger screens

Text wraps naturally without overflow

Achieved using:

Bootstrap grid system

Utility classes

Flexible widths and spacing

⚠️ Best Practices Followed

✔ Mobile-first responsive design

✔ Proper use of Bootstrap grid

✔ Clean separation of HTML & CSS

✔ No unnecessary JavaScript

✔ Consistent typography and spacing

✔ Reusable card structure

🛠️ How to Customize

🔹 Add More Blog Cards

Duplicate one card column block:

<div class="col-12 col-lg-6 col-md-12">...</div>

🔹 Change Colors

Update values in CSS:

.readmore { color: #ff9f00; }

button { background-color: #1754a1; }

🔹 Replace Images & Text

Update image URLs and content directly inside each card.

🚀 Why This Implementation Works Well

Clean and readable UI

Scales easily with more blog posts

Uses Bootstrap components correctly

Suitable for blogs, news sections, and content-driven websites

✅ Final Notes

Fully responsive across devices

Easy to integrate into larger websites

Clean structure for future enhancements

<img width="644" height="309" alt="Screenshot 2026-01-17 200451" src="https://github.com/user-attachments/assets/7e8b54c2-b797-4e7d-bfcd-a0785a7a6cab" />
![Uploading Screenshot 2026-01-17 200523.png…]()
