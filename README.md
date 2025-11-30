# 📌 Clove Dental 

A fully responsive, pixel-perfect clone of the Clove Dental landing page, built without any frameworks, using only HTML, CSS.  
This project replicates the professional UI/UX of the official Clove Dental website across desktop, tablet, and mobile viewports, making it an excellent demonstration of frontend development skills.

---

## 🚀 Demo

https://yasminghazala21.github.io/clove-project/

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Screenshots](#-screenshots)
- [Project Structure](#-project-structure)
- [Setup Instructions](#-setup-instructions)
- [Responsive Design Approach](#-responsive-design-approach)
- [Future Enhancements](#-future-enhancements)
- [License](#-license)

---

## 📌 Overview

This project is a static multi-section landing page designed for a dental service provider.  
The goal of the build is to match the layout, design language, spacing, typography, and responsiveness of the official Clove Dental UI reference.

The website includes:

- Hero section with consultation form
- Auto-scrolling achievements bar
- Treatment cards
- Real patient transformation gallery
- “Why Choose Us” section
- Patient testimonials (auto-scroll)
- Frequently Asked Questions (FAQs)
- Footer with legal and branding links

The page is optimized for large screens, laptops, tablets, and mobile (including common iPhone viewports).

---

## ⭐ Features

### 🔹 Frontend UI/UX

- Clean, modern, brand-accurate design
- Custom UI built from scratch (no Tailwind / Bootstrap)
- Proper color palette and typography system using CSS variables
- Smooth auto-scroll animations (CSS keyframes)
- Fully responsive layout

### 🔹 Components

- Header with mobile hamburger menu
- Hero form with Captcha-style UI (static)
- Auto-scrolling Achievements section
- Root Canal Treatment cards
- Patient Transformation image grid
- “Why Choose Us” details section
- Testimonial slider / auto-scroll section
- FAQs section
- Footer with branding and legal information

### 🔹 Code Quality

- Semantic HTML5
- Organized CSS with variables
- Consistent, readable naming conventions
- Mobile-first improvements
- No unnecessary code or repetition
- Clean, readable and interview-friendly

---

## 🛠 Tech Stack

| Technology           | Purpose                                |
|----------------------|----------------------------------------|
| HTML5                | Structure of the page                  |
| CSS3                 | Styling, responsiveness, animations    |
| No Frameworks Used   | Fully custom handcrafted UI            |

---

## 📸 Screenshots

### 🖥 Desktop View

`/images/1.png`
`/images/2.png`
`/images/3.png`
`/images/6.png`
`/images/5.png`
`/images/7.png`

---

## 📂 Project Structure

```
clove-dental-website/
│
├── index.html          # Main page
├── css/
│   └── style.css       # All styling + responsive design
│
├── js/
│   └── script.js       # Mobile menu toggle + interactions
│
├── images/             # All assets and icons
│
└── README.md           # Documentation
```

---

## 🔧 Setup Instructions

No installation is required. This is a static HTML/CSS/JS project.

### ➡ Option 1: Open Locally

1. Download or clone the repository:
   ```
   git clone https://github.com/Yasminghazala21/clove-project.git
   ```
2. Open `index.html` in any browser.
3. Done.

### ➡ Option 2: Deploy on Netlify / GitHub Pages

- **GitHub Pages**  
  - Push the project to a GitHub repository.  
  - Go to **Settings → Pages**.  
  - Select the branch (usually `main`) and root (`/`) folder.  
  - Save and use the generated GitHub Pages URL.

---

### ✔ Flexbox Layout

- Used for multi-column desktop sections
- Stacks vertically on smaller screens for readability

### ✔ CSS Media Queries

Breakpoints used:

- `≥ 1200px` → Large desktops
- `≥ 768px` → Tablets
- `< 768px` → Mobile layout

### ✔ Auto-scroll Animations

- Achievements bar and testimonial section use CSS keyframe animations
- Example pattern:
  ```
  animation: scroll-achievements 20s linear infinite;
  ```

### ✔ Mobile-friendly Navigation

- Hamburger menu on smaller screens
- Click-to-toggle navigation
- Sticky header for better UX

---


## 🚀 Future Enhancements

Possible improvements:

- Connect the hero consultation form to a real backend API
- Add Swiper.js or a custom JS slider for testimonials
- Implement fade-in / on-scroll animations using Intersection Observer
- Improve accessibility (ARIA labels, keyboard navigation, alt text review)
- Add a dark mode toggle using CSS variables + JS
- Convert the project into reusable React.js components

---

## 📄 License

This project is for educational, practice, and interview purposes only.  
Not affiliated with Clove Dental — the UI is cloned purely for learning.
```
