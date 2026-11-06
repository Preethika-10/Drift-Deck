# Drift-Deck 🏎️

Drift-Deck is an interactive, multi-page car showcase and digital platform designed to explore top-tier automotive brands, view specifications, manage a virtual garage, and simulate checkout processes.

---

## 🌟 Key Features

- **Brand Showcases:** Detailed vehicle pages highlighting performance metrics and background info for leading manufacturers (Ferrari, Porsche, McLaren, Bugatti, and more).
- **Interactive Garage & Fleet:** Manage select vehicles, check specifications, and interact with dynamic car assets.
- **Responsive Layout:** Optimized views across mobile and desktop interfaces.
- **Account & Checkout Flows:** Seamless user flow from viewing models to interactive cart and checkout screens.

---

## 🛠️ Project Structure

```text
Drift-Deck/
├── index.html            # Main landing page / entry point
├── about.html            # Brand & project overview
├── garage.html           # Interactive garage view
├── cart.html             # Shopping cart interface
├── checkout.html         # Payment & checkout simulation
├── login.html            # User login / authentication view
│
├── css/                  # Stylesheets
│   ├── style.css         # Core brand styling
│   ├── carstyle.css      # Custom styling for vehicle cards
│   └── mobileview.css    # Responsive design rules
│
├── js/                   # Frontend Application Logic
│   ├── nav-loader.js     # Global navigation loading logic
│   ├── car-logic.js      # Vehicle filtering and interactions
│   ├── testdrive.js      # Test drive scheduling logic
│   └── fleet.js          # Garage fleet management
│
└── images/               # Media Assets
    ├── *-logo.jpg        # Manufacturer brand badges
    └── carvideo.mp4      # Background video assets
