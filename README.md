# Pantry Junction — Restaurant Management Website

Pantry Junction is a modern, responsive restaurant website built with **HTML**, **CSS**, and **JavaScript**. It simulates a complete front-end experience for a restaurant where visitors can browse the menu, place orders, reserve tables, and manage their profile and order history.

Live demo

- If you use VS Code, run the Live Server extension or open `index.html` using a local web server (for example: `http://127.0.0.1:5500/index.html`).

Highlights

- Clean, mobile-first responsive design with smooth UI interactions.
- Menu browsing, add-to-cart and order simulation (cart persisted in localStorage).
- Table reservation flow with date/time selection and booking summary.
- Authentication pages (signup/login) and a user profile page that shows account details and past orders.
- Contact page with a contact form and location details.

Features

- 🍽️ Browse menu categories and individual dishes
- 🛒 Add to cart, view cart summary, and simulate checkout
- 📅 Book tables with date/time and party size
- 🔐 Simple login and signup pages (front-end only)
- 👤 Profile and order history (stored client-side)
- 📱 Fully responsive layout for desktop, tablet, and mobile
- 🎨 Modern UI using CSS and Font Awesome icons

Pages included

- `index.html` — Home page with featured dishes and promotions
- `about.html` — Restaurant story and values
- `contact.html` — Contact form and location details
- `order.html` — Food ordering and cart page
- `table_booking.html` — Table reservation flow
- `login.html` — Login page
- `signup.html` — Signup page
- `profile.html` — User profile and order history
- `edit-profile.html` — Edit profile details
- `tracking.html` — Order tracking simulation

Technologies used

- HTML5 — Semantic markup
- CSS3 — Responsive layout and styling
- JavaScript — Interactivity and localStorage-based state management
- Font Awesome — Icons

Project structure

```
Restaurant-Management-System/
├── index.html
├── about.html
├── contact.html
├── order.html
├── table_booking.html
├── login.html
├── signup.html
├── profile.html
├── edit-profile.html
├── tracking.html
├── assets/ (styles, images, scripts)
├── README.md
```

How to run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Prasanthi207-code/Restaurant-Management-System.git
   cd Restaurant-Management-System
   ```
2. Open `index.html` in your browser directly, or run a local web server. Recommended (VS Code Live Server):
   - Install the Live Server extension in VS Code
   - Right-click `index.html` → "Open with Live Server"

Notes

- This project is a front-end demonstration only. There is no back-end—orders, reservations, and user data are simulated and stored in the browser's localStorage.
- Replace placeholder images, text, or icons with real assets if you plan to deploy to production.

Contributing

Contributions, suggestions and improvements are welcome. If you'd like to contribute, open an issue or submit a pull request describing your changes.

Author

Developed by **Prasanthi**

License

This project is open for personal and educational use. Add a license file if you want to specify licensing terms.
