# 🛒 MyCart - Online Shopping Web Page

This is a simple, responsive HTML and CSS-based web page simulating an **e-commerce homepage** for an online shopping site. It showcases products in different categories such as **cricket gear**, **furniture**, and **phones**, with images dynamically loaded from [Unsplash](https://source.unsplash.com/).

---

## 🚀 Features

- Responsive layout using CSS media queries
- Random product images using **Unsplash Source API**
- Navigation bar with search functionality
- Multiple product categories with promotional text
- Footer section with copyright
- Clean utility classes for reusability

---

## 🗂️ Project Structure

mycart/

│

├── index.html # Main HTML file (you may rename as needed)

├── css/

│ ├── style.css # Main styling (you can expand here)

│ ├── utils.css # Utility classes (flex, buttons, margins, etc.)

│ └── responsive.css # Responsive layout for smaller screens

├── img/

│ └── image.png # Site logo or any placeholder image

├── about.html # About page (not fully implemented)

├── contact.html # Contact page (not fully implemented)

└── home.html # Homepage duplicate or landing



---

## 🎨 Technologies Used

- HTML5
- CSS3
- Responsive design with media queries
- Image API: [Unsplash Source](https://source.unsplash.com/)

---

## 📱 Responsive Design

The layout adjusts automatically for smaller screens (like tablets and mobiles). Styles are defined in `responsive.css`, where flex-direction and sizing are adjusted for a better user experience on small devices.

---

## 📸 Image Handling

Product images are randomly pulled from **Unsplash Source** using relevant keywords like:

- `?cricket`, `?phones`, `?furniture`, etc.
- This eliminates the need to store local images and provides dynamic image generation.

---

## 🛠️ How to Run

1. Clone or download this repository.
2. Open `index.html` (or your main HTML file) in any modern browser.
3. No server or build tools are needed — it's 100% frontend.

```bash
git clone https://github.com/your-username/mycart.git
cd mycart
start index.html   # Or just double-click it
