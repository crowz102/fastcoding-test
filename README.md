# Reanty Real Estate Landing Page

A modern, responsive, high-fidelity real estate landing page built for the brand **Reanty**.

## Demo URL

[Live Demo Placeholder](https://example.com/reanty-demo) (Staging / Production link)

## Features & Sections

The landing page contains the following sections:
1. **Top Bar**: Standard company contact info (Email, Address) and social media handles.
2. **Navigation Header**: Clean sticky navigation menu with logo, active link indication, and custom CSS-only responsive hamburger drawer for mobile viewports.
3. **Hero Section**: Premium layout highlighting headline, interactive search bar, and hero image placeholder decorated with floating trend-metrics (revenue total) and play buttons.
4. **Commercial Real Estate Guides**: Centered guides card grid introducing Buyer, Seller, and active Renter guides.
5. **Dream Living Spaces Details**: Rating badge and a features list showcasing security, verification, and flexibility policies.
6. **Today Sells Properties Grid**: Overview of hot deals with client avatar strips and asymmetrical image grid placeholders.
7. **Services Section**: 3-column service catalog layout displaying 6 cards with subtle hover shift animations.
8. **Featured Properties**: Property catalog category tabs (Apartment, Villa, Land) and 3 premium property spec cards.
9. **Large Property Preview Banner**: A high-impact background preview showcase with Unit No. 9A circle badge and floating price cards.
10. **Testimonials Slider**: 5-star customer review display with static pagination slider buttons.
11. **Successful Locations & Newsletter**: Cards showcasing completed brokerages overlayed with a responsive newsletter registration form.
12. **Blog & Resources**: 3 recent articles with hover links.
13. **Contact desk**: 2-column contact section containing direct support perks and a styled inquiry form.
14. **Footer**: 5-column layout containing logo, social media profile links, quick navigation, resources list, and copyright.

## Design Decisions & Aesthetics

- **Vibrant Modern Palette**: Used a professional custom color theme featuring a primary orange-red (`#ff553e`), a deep slate-dark for headers (`#061f22`), soft gray-blues (`#8da0aa`), and elegant light background highlights (`#f2f7f8`).
- **Typography Integration**: Powered by premium Google Web Fonts ('Outfit' for large bold titles, 'Inter' for highly readable body paragraphs).
- **Responsive Flexbox & CSS Grid**: Built using modern layout primitives. All grids shift dynamically from multi-column rows (up to 5 columns in the footer) to centered single-column stacks on mobile devices.
- **CSS-Only Hamburg Drawer**: Implemented hamburger menu drawer using pure CSS checkboxes and relative selectors to ensure interactive responsiveness without requiring custom JS libraries.
- **Stylized SVG Vector Icons**: Avoided FontAwesome or similar heavy third-party CDNs by embedding precise inline vector shapes inside HTML tags. This keeps pages lightweight, robust, and offline-compatible.
- **Premium Grey Placeholders**: Styled image placeholders with custom linear-gradient shadows, subtle dotted layout structures, and icon indicators to make them look intentional and aesthetically pleasing.

## Technologies Used

- **Pure HTML5**: Semantic structural elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<aside>`).
- **Pure CSS3**: CSS Custom Properties/variables, CSS Grid, Flexbox, media queries, keyframe animations.
- **SVG Vectors**: Customized vector nodes.

This allows the project to be run directly off local file systems or static web storage nodes (e.g. AWS S3, GitHub Pages, Netlify) without modifications.
