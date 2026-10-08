# Layout Gym — Responsive Tailwind CSS

A responsive layout practice project built using **Tailwind CSS**.
The project contains five exercises that demonstrate responsive layouts, positioning, navigation, grids, and a Holy Grail page layout.

## Technologies Used

* HTML5
* Tailwind CSS
* Responsive Design
* CSS Flexbox
* CSS Grid

## Tasks Completed

### Task 1 — Nine Positions

Created nine boxes demonstrating different Flexbox positions:

* Top Left
* Top Center
* Top Right
* Middle Left
* Center
* Middle Right
* Bottom Left
* Bottom Center
* Bottom Right

The layout is responsive using Tailwind Grid classes.

### Task 2 — Responsive Navigation Bar

Created a responsive navigation bar.

* Navigation links are visible from `md` and above.
* A hamburger button is displayed below `md`.
* The navigation uses Flexbox.
* The Sign Up button is included.
* No JavaScript is used.

### Task 3 — Holy Grail Layout

Created a responsive Holy Grail layout.

* On phones, the sidebar appears above the main content.
* From `lg` and above, the sidebar moves to the left.
* The sidebar has a width of `220px` on large screens.
* The layout includes:

  * Header
  * Sidebar
  * Main Content
  * Footer

### Task 4 — Hero Section

Created a responsive hero section.

* On phones, the text and image are stacked vertically.
* From `md` and above, the text and image appear side by side.
* The heading uses `text-3xl` on phones.
* The heading changes to `text-5xl` from `lg`.
* Buttons are full width on phones.
* Buttons change to automatic width from `sm`.

### Task 5 — Dark Mode

Added Tailwind `dark:` variants throughout the page.

Dark mode includes changes for:

* Page background
* Section backgrounds
* Card backgrounds
* Text colors
* Borders
* Navigation
* Main content
* Footer

The page was tested using browser DevTools with `prefers-color-scheme`.

## Responsive Testing

The project was tested at the required viewport sizes:

### 360px — Mobile

At 360px:

* No horizontal scrolling occurs.
* Content fits within the screen.
* Navigation links are hidden and the hamburger button is shown.
* Layouts stack appropriately.
* Hero text and image are stacked.
* Buttons take full width.

**Screenshot:**

![360px Screenshot](![hero section](image-6.png))
![360px Screenshot](![page layout](image-7.png))

### 768px — Tablet

At 768px:

* Responsive layouts adjust to the medium breakpoint.
* Navigation links become visible.
* Hero content can appear side by side.
* Grid layouts adjust according to the responsive classes.

**Screenshot:**

![768px Screenshot](![ nine-position-768px](image.png))
![768px Screenshot](![navigation and comment](image-5.png))

### 1280px — Desktop

At 1280px:

* Full desktop layout is displayed.
* Navigation links are visible.
* Hero content appears side by side.
* The Holy Grail sidebar appears on the left with a width of 220px.
* Grid layouts use the available desktop space.

**Screenshot:**

![1280px Screenshot]([nine position](image-1.png))
![1280px Screenshot](![navigation and comment](image-2.png))
![1280px Screenshot]([page layout](image-3.png))
![1280px Screenshot](![hero section](image-4.png))

## Dark Mode Screenshots

The page was also tested in both light and dark modes using browser DevTools.

### Light Mode

![Light Mode Screenshot](![light mode layout](image-8.png))

### Dark Mode

![Dark Mode Screenshot](![dark mode layout](image-10.png))

## Project Structure

```text
week3-tailwind/
│
├── layouts.html
├── README.md
└── screenshots/
    ├── 360px.png
    ├── 768px.png
    ├── 1280px.png
    ├── light-mode.png
    └── dark-mode.png

