# E-Tutor

A modern **online learning platform UI** built with HTML and Tailwind CSS.

E-Tutor is designed as an educational website where users can explore courses, browse categories, learn more about the platform, and contact the team.

## Overview

E-Tutor provides a clean e-learning interface inspired by modern online course platforms.

The project includes:

* Home page
* Course categories
* Best-selling courses section
* About page
* Contact page
* Instructor section
* Course browsing interface
* Search interface
* Authentication buttons
* Social media links
* App download section
* Responsive layouts
* Custom local image assets

## Pages

| Page            | Description                          |
| --------------- | ------------------------------------ |
| `index.html`    | Main landing page                    |
| `category.html` | Browse courses and categories        |
| `main.html`     | About E-Tutor                        |
| `contact.html`  | Contact information and contact form |

## Features

### 🏠 Home Page

The homepage contains:

* Navigation bar
* E-Tutor branding
* Course search bar
* Browse courses button
* Create Account button
* Sign In button
* Hero section
* Course categories
* Best-selling courses
* Instructor promotion
* Testimonials and additional sections
* Footer with useful links

### 📚 Course Categories

The platform displays multiple learning categories, including:

* Development
* Business
* Finance & Accounting
* IT & Software
* Personal Development
* Office Productivity
* Marketing
* Photography & Video
* Lifestyle
* Design
* Health & Fitness
* Music

Each category includes an icon and the number of available courses.

### 🎓 Courses

The course sections include:

* Course thumbnails
* Course categories
* Course prices
* Ratings
* Student counts
* Course titles
* Course cards

### 📩 Contact Page

The contact page includes:

* Contact information
* Email information
* Phone numbers
* Address
* Contact form
* Message field
* Map section
* Branch information

### 👨‍🏫 Instructor Section

The website also includes a section promoting the ability to become an instructor.


## Technologies

This project uses:

* **HTML5**
* **Tailwind CSS**
* **CSS**
* **Google Fonts**
* **Local PNG assets**

Tailwind CSS is loaded through the browser CDN:

```html
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
```

The project uses the **Inter** font from Google Fonts.

## Project Structure

```text
E-tutor-project/
│
├── index.html
├── category.html
├── main.html
├── contact.html
├── package-lock.json
│
└── images/
    ├── logo.png
    ├── Course Images.png
    ├── Course Images(1).png
    ├── Course Images(2).png
    ├── Course Images(3).png
    ├── ...
    ├── Cpu.png
    ├── Handshake.png
    ├── CreditCard.png
    ├── Camera.png
    ├── PenNib.png
    ├── Headphones.png
    ├── Linkedin.png
    ├── Twitter.png
    ├── apple 1.png
    ├── google-play-5 1.png
    └── ...
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/u0ke/E-tutor-project.git
```

### 2. Open the project

```bash
cd E-tutor-project
```

### 3. Run the website

Because this is a static HTML project, no backend installation is required.

You can simply open:

```text
index.html
```

in your browser.

For a better development experience, you can use **VS Code Live Server**.

## Navigation

The main navigation connects the different pages:

```text
Home
 ├── Courses
 ├── About
 ├── Contact
 └── Become an Instructor
```

## Design

The project follows a modern e-learning design with:

* Orange primary accent
* Dark navigation/footer
* Light gray backgrounds
* Course cards
* Category cards
* Inter typography
* Responsive Tailwind utility classes
* Custom icons and illustrations

### Main Colors

```text
Primary Orange: #FF6636
Dark Gray:      #1D2026
Light Gray:     #F5F7FA
White:          #FFFFFF
Text Gray:      #4E5566
```



## Future Improvements

Possible improvements for future versions:

* Add JavaScript interactions
* Implement functional course search
* Add course filtering
* Add authentication
* Add user profiles
* Add shopping cart
* Add course details pages
* Connect a backend/database
* Add instructor dashboard
* Add student dashboard
* Make the contact form functional
* Add real course data
* Improve mobile navigation
* Add dark mode

## Author

Created by **u0ke**

GitHub:

https://github.com/u0ke

## License

This project is intended for educational and portfolio purposes.
