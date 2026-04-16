# Mara Osei — Profile Card Component

A minimalist, high-fidelity profile card built with semantic HTML5, modern CSS (Flexbox/Grid), and vanilla JavaScript. This project was designed with a focus on accessibility (WCAG AA), responsiveness, and testability.

## 🚀 Live Demo
[Insert your GitHub Pages link here]

## 🛠️ Features

- **Dynamic Epoch Time:** Displays the current time in milliseconds (`Date.now()`), updating every second with `aria-live` support for screen readers.
- **Modern Design:** Dark mode aesthetic using CSS variables, custom "DM Serif Display" typography, and smooth micro-interactions.
- **Fully Responsive:** Adapts from a vertical stack on mobile to a multi-column grid on desktop using CSS Grid and Media Queries.
- **Accessible (A11y):** - Semantic tags (`<article>`, `<figure>`, `<nav>`, `<section>`).
  - High-contrast color palette.
  - Visible focus indicators for keyboard navigation.
  - `target="_blank"` links include `rel="noopener noreferrer"`.
- **Test-Ready:** Includes specific `data-testid` attributes for automated QA and DOM snapshot testing.

## 📂 File Structure

The project is kept intentionally lightweight with no build tools:
- `index.html`: Contains the document structure, internal CSS (Design Tokens), and the live-time script.
- `pro.png`: The profile avatar image.

## 🧪 Testing Guidelines

This component uses specific `data-testid` attributes to ensure stability during automated testing. The following elements are targeted:

| Element | Test ID |
| :--- | :--- |
| Root Card Container | `test-profile-card` |
| User Name | `test-user-name` |
| User Biography | `test-user-bio` |
| Avatar Image | `test-user-avatar` |
| Epoch Time Display | `test-user-time` |
| Social Links List | `test-user-social-links` |
| Specific Socials | `test-user-social-twitter`, `test-user-social-github`, etc. |
| Hobbies List | `test-user-hobbies` |
| Dislikes List | `test-user-dislikes` |

## 💻 Local Development

To run this project locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/mara-osei-profile-card.git](https://github.com/your-username/mara-osei-profile-card.git)
