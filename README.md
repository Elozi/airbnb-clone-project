# Airbnb Clone Project

This repository contains the development and design process for an Airbnb-like booking system, focusing on clean UI/UX, organized team roles, and reusable UI component patterns.

---

## UI/UX Design Planning

### Design Goals
- Build a clean, modern, and intuitive interface that mimics Airbnb's user experience.
- Ensure responsiveness across all devices.
- Simplify user flow from browsing properties to completing a booking.
- Maintain accessibility and visual clarity.

### Key Features
- Property listings with filters
- Property detail view with images, amenities, and reviews
- Seamless checkout process
- User authentication
- Booking management

### Primary Page Descriptions

| Page | Description |
|------|-------------|
| **Property Listing View** | Displays a list of properties with filter options (e.g., location, price, dates). Shows key information like name, image, price, and rating. |
| **Listing Detailed View** | Provides detailed info about the selected property, including images, description, amenities, host info, and booking button. |
| **Simple Checkout View** | Allows users to review booking details, input payment info, and confirm reservation. Emphasis on simplicity and trust. |

### Importance of User-Friendly Design
User-friendly design is essential in a booking system to ensure:
- Ease of navigation, especially for first-time users
- Higher conversion rates during the booking process
- Fewer user errors and support issues
- Improved satisfaction and return visits

---

## More UI/UX Design Planning

### Figma Design Properties

**Color Styles:**
- Primary: #FF5A5F (Airbnb Red)
- Secondary: #484848 (Dark Gray)
- Background: #F7F7F7 (Light Gray)
- Accent: #00A699 (Teal)

**Typography:**
- Font Family: `Circular`, fallback: `Arial`, `sans-serif`
- Font Weights: 400 (Regular), 600 (Semi-Bold), 700 (Bold)
- Font Sizes:
  - Header: 24px, 32px
  - Subheader: 18px
  - Body: 14px, 16px

### Importance of Identifying Design Properties
Understanding design properties such as typography and color styles:
- Ensures design consistency across all pages and components
- Helps developers implement design accurately
- Allows for easier changes and scalability
- Improves overall visual hierarchy and accessibility

---

## Project Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| **Project Manager** | Oversees the project schedule, coordinates between teams, ensures deliverables are met on time. |
| **Product Owner** | Defines the vision and priorities of the product, manages the product backlog, represents stakeholder needs. |
| **Scrum Master** | Facilitates Agile ceremonies, removes blockers, and helps the team follow Scrum best practices. |
| **Frontend Developers** | Build the user interface based on Figma designs using technologies like React. Implement responsiveness and interactivity. |
| **Backend Developers** | Develop the server-side logic, handle database connections, and build APIs. Ensure security and performance. |
| **Designers** | Create wireframes, mockups, and visual components. Focus on usability, branding, and visual consistency. |
| **QA/Testers** | Test features to catch bugs early, ensure functionality meets requirements, perform UI/UX testing. |
| **DevOps Engineers** | Set up CI/CD pipelines, manage deployment environments, and monitor infrastructure health. |

---

## UI Component Patterns

### Planned UI Components

- **Navbar**  
  Contains site logo, search bar, user menu, and links. Should be responsive and sticky.

- **Property Card**  
  Compact display of property info including image, title, location, price, and rating. Used in listing view.

- **Footer**  
  Contains links to About, Support, Legal pages, and social media icons.

Each component will be designed for reusability and responsiveness, following the established design system.

---
