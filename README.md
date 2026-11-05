EventPulse — Modern Event Management Platform

EventPulse is a feature-rich, responsive single-page web application designed for discovering events, viewing agenda details, reserving standard or VIP passes with real-time client-side form validation, generating dynamic digital QR tickets, and managing pass registrations locally.

🚀 Live Demo & Repository Links

Live Website: https://sande-ux.github.io/Eventkexplore-website/

GitHub Repository: https://github.com/Sande-ux/Eventkexplore-website

✨ Key Features & Technical Capabilities

1. Header Navigation & Utility Actions

Glassmorphic Navigation Bar: Sticky, semi-transparent header with background blur (backdrop-filter).

Dynamic Theme Switcher: Instant Dark Mode and Light Mode toggle switch with class-based Tailwind toggling.

Ticket Locker Drawer: Quick navigation button with a live badge showing the current count of saved registrations.

Responsive Mobile Drawer: Mobile menu toggle navigation bar for seamless navigation across screen sizes.

2. Flagship Event & Real-Time Countdown

Featured Showcase: Dedicated hero banner highlighting the Global AI & Tech Summit 2026.

Live Dynamic Counter: Real-time ticker counting down days, hours, minutes, and seconds until the event launch date.

Direct Quick-Register Link: Direct registration action button pointing directly to the flagship event modal.

3. Event Discovery & Filtering

Interactive Category Pills: Filter event listings by category (All Categories, Tech & AI, Music & Festivals, Workshops, Business & Leadership, Sports & Gaming).

Instant Keyword Search Bar: Real-time filtering algorithm matching queries against event titles, descriptions, and venue locations.

Dynamic Empty State: Visual fallback display when search criteria yield zero matching results.

4. Event Detail Modal & Form Validation

Rich Event Overview: Detailed preview modal with high-resolution imagery, scheduling, venue location, pass pricing, and keynote agenda breakdown.

Client-Side Form Validation:

Full Name (required)

Email Address validation (standard format check)

Mobile Phone Number (10-digit numeric check)

Ticket Tier Selection (General Admission, VIP Access, Student Pass)

Duplicate Protection: Prevents duplicate bookings under the same email for a given event.

5. Dynamic Digital Pass & QR Code Ticket Generation

HTML5 Canvas Engine: Procedural QR code generator rendered instantly upon successful form submission.

Printable Event Pass: Detailed pass ticket modal displaying Attendee Name, Event Title, Ticket Tier, Venue, Date, and Unique Reference ID.

Print & Export: Dedicated print button formatting passes for instant PDF export or physical printing.

6. Local Storage Persistence (Ticket Locker)

Offline Storage: All booked tickets are persisted in the browser's localStorage.

Ticket Manager: Slide-over drawer allowing users to review all booked passes or cancel/delete individual registrations.

🛠️ Built With

HTML5: Semantic document layout (<header>, <main>, <section>, <form>, <canvas>, <footer>).

Tailwind CSS (v3 CDN): Utility-first styling framework with custom colors, glassmorphism filters, and dark mode configuration.

FontAwesome (v6.4.0 CDN): Vector icon system for user interface indicators.

Google Fonts: Inter font typography family.

Vanilla JavaScript (ES6+): DOM manipulation, event listeners, timer intervals, local storage handler, HTML5 canvas rendering engine, and form validation logic.

📁 Repository Structure

Eventkexplore-website/
├── index.html       # Single-Page Application (HTML + Tailwind CSS + JavaScript Logic)
└── README.md        # Comprehensive project documentation & submission guide


💻 How to Run Locally

Clone the Repository:

git clone https://github.com/Sande-ux/Eventkexplore-website.git


Navigate into the Project Folder:

cd Eventkexplore-website


Launch the Web Page:

Open index.html directly in any standard browser (Chrome, Edge, Firefox, Safari).

Alternatively, use the Live Server extension in Visual Studio Code.

📧 Contact & Support

Platform: EventPulse Inc.

Support Email: support@eventpulse.io
