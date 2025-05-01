# Tailwind Media Query Practice

## Objective
Practice building responsive layouts using Tailwind CSS's mobile-first utility classes.

## Project Overview
This simple HTML page uses Tailwind CSS (via CDN) to create a grid of profile cards. Students will edit and style the layout using responsive utility classes such as `sm:`, `md:`, `lg:`.

---

## Tasks

### 1. View and Test the Layout
- Open `index.html` in a browser.
- Resize the screen to observe how the layout changes:
  - 📱 1 column on mobile (`grid-cols-1`)
  - 💻 2 columns on medium screens (`md:grid-cols-2`)
  - 🖥️ 3 columns on large screens (`lg:grid-cols-3`)

---

### 2. Modify the Following
- Add your own card with a new name, image, and job title.
- Change the text size using responsive classes (e.g., `text-lg`, `md:text-xl`).
- Make the profile image circular on small screens and square on larger screens (`rounded-full` and `lg:rounded-none`).
- Change the card background color on large screens using `lg:bg-*` utility classes.
- Add hover effects to the card using `hover:shadow-lg` and `hover:bg-*`.
- Use responsive padding and margins (e.g., `p-4`, `lg:p-6`, `mt-2`, `md:mt-4`).
- Add a new section at the bottom with a responsive text block (e.g., `text-center md:text-left`).
- Make the card layout stack **vertically on mobile** but display **side-by-side on large screens** using `flex flex-col lg:flex-row`.

---

## References
- [Tailwind Responsive Design Docs](https://tailwindcss.com/docs/responsive-design)
- [Tailwind Grid Layout Docs](https://tailwindcss.com/docs/grid-template-columns)
- [Tailwind Spacing Docs](https://tailwindcss.com/docs/padding)
- [Tailwind Typography Docs](https://tailwindcss.com/docs/font-size)

