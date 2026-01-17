🎉 Responsive Offers Banner – Bootstrap 4

📌 Overview

This project implements a responsive promotional offers banner for an e-commerce website using Bootstrap 4 and custom CSS.

The section features:

A gradient background

Promotional text

Product images

A special offer badge

Credit card offer image

The layout is mobile-first and adapts smoothly across small, medium, and large screens.

🧩 Technologies Used

HTML5

CSS3

Bootstrap 4.5.2

Google Fonts (Roboto)

🧭 Layout Structure

1️⃣ Container & Grid

Uses Bootstrap’s container → row → column structure

Columns rearrange using Bootstrap ordering utilities

<div class="row bg">

Responsive column behavior:

col-12 → mobile

col-md-* → desktop

order-md-* → change layout order on desktop

2️⃣ Background Styling

A linear gradient is applied to the banner container.

.bg {

  background-image: linear-gradient(to right, #f49541, #dd5d97);

}

✔ Smooth color transition

✔ Full-width promotional look

3️⃣ Offer Badge Image

Displayed prominently and resized only on small devices.

.image1 {

  width: 180px;

  height: auto;

}



@media (max-width: 767px) {

  .image1 {

    width: 300px;

    margin-bottom: -36px;

  }

}

✔ Larger emphasis on mobile

✔ Maintains aspect ratio

4️⃣ Product Image

Main appliance image scales responsively without distortion.

.image2 {

  width: 100%;

  height: 450px;

  object-fit: contain;

}

5️⃣ Text Content

Includes heading and promotional text with emphasis.

<h1>BEST NEW YEAR SPECIAL OFFERS</h1>

<p>Best time to buy. Save upto <span class="seven">70% cash</span></p>

.seven {

  font-style: italic;

  font-weight: 800;

}

6️⃣ Credit Card Offer Image

Placed below the text and centered for clarity.

.image3 {

  width: 100%;

  height: 180px;

  object-fit: contain;

}

📱 Responsive Behavior

Achieved using:

Bootstrap grid

Flex utilities

Media queries

⚠️ Best Practices Followed

✔ Mobile-first design

✔ Bootstrap grid used correctly

✔ Media queries only where necessary

✔ No inline styles

✔ Clean separation of HTML & CSS

✔ Images scaled using object-fit

🛠️ How to Customize

🔹 Change Gradient Colors

background-image: linear-gradient(to right, #color1, #color2);

🔹 Increase Image Size on Mobile

@media (max-width: 767px) {

  .image1 {

    width: 340px;

  }

}

🔹 Replace Images

Update image URLs inside:

.image1

.image2

.image3

🚀 Why This Implementation Works Well

Clean, readable structure

Responsive without JavaScript

Uses Bootstrap utilities correctly

Suitable for real-world promotional banners

This is a production-ready banner section, not a demo layout.

✅ Final Notes

Fully responsive across devices<img width="822" height="349" alt="Screenshot 2026-01-17 185832" src="https://github.com/user-attachments/assets/0b8c6dae-b5e1-4151-a16e-fdef262f7724" />


Easy to integrate into an e-commerce homepage

Scales well with additional promotional content<img width="513" height="663" alt="Screenshot 2026-01-17 185910" src="https://github.com/user-attachments/assets/40e908b6-da8c-4ed9-8307-56b9e2379a04" />


