# Design Guide – Tech Treasure Blog

## Theme
Modern Professional with a touch of treasure hunt (dark navy with glowing teal accents)

## Color Palette
- **Navy (#0a192f)** – Main background
- **Light Navy (#112240)** – Secondary background
- **White (#ffffff)** – Primary text
- **Slate (#8892b0)** – Secondary text
- **Teal (#64ffda)** – Accents, links, highlights

## Typography
- **Primary Font:** Inter (fallback: -apple-system, BlinkMacSystemFont, Roboto)
- **Headings:** Gradient from white to teal, bold, 2.8rem for H1
- **Body text:** 1.2rem on desktop, 1rem on mobile, line-height 1.6 for readability

## Layout Strategy
- **Single-column container** centered on the page with max-width 800px
- **Glassmorphism effect** (backdrop-filter blur) on container for modern feel
- **Flexbox** used for navigation links and blog post grouping
- **Responsive design** – media query reduces padding and font size on mobile
- **Consistent spacing** – 2.5rem padding inside container, 1.5rem between blog posts

## Special Elements
- Hover effects on links: background flips to teal, text becomes navy
- Blog posts have a left border of teal (#64ffda) to draw attention
- Gradient text on main heading

## Reason for Choices
The dark navy background reduces eye strain, teal gives a sense of discovery (treasure!), and the clean layout makes content easy to read. The glass effect feels modern and premium.