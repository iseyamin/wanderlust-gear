# Wanderlust Gear (Influencer Products)

A responsive landing page for an influencer gear store, featuring cameras, drones, microphones, and other creator equipment. It is built with plain HTML and CSS, with no frameworks or JavaScript.

## Features

- **Navigation bar** with links (Home, Products, Sign up, Log In) and search and cart icons
- **Hero banner** with a headline, a short intro, a "Pre-book now" call-to-action, and a product image
- **Partner logos strip** (Alibaba, Amazon, Daraz, eBay, Rakuten, Target, Walmart)
- **Popular Collection grid** of product cards with image, title, price, and shipping/protection details
- **Featured section** with a promotional image and a "Join Now" button
- **Footer** with copyright text and social media icons
- **Responsive layout** that adapts to mobile screens (575px and below)

## Tech Stack

- HTML5
- CSS3 (Flexbox, Grid, media queries)
- [Poppins](https://fonts.google.com/specimen/Poppins) font via Google Fonts

## Project Structure

```
wanderlust-gear/
├── index.html
├── styles/
│   └── gear.css
├── images/        # Product and banner images (tripod, mic, airpod, drone, action, gear, main-camera)
├── logos/         # Nav icons and partner brand logos
└── social/        # Social media icons
```

## Getting Started

1. Clone the repository:
```bash
   git clone https://github.com/iseyamin/wanderlust-gear.git
```
2. Open the project folder:
```bash
   cd wanderlust-gear
```
3. Open `index.html` in your browser (or use a tool like VS Code's Live Server).

No build step or dependencies are required.

## Customization

- **Colors:** The primary button color is `#e02c6d` and the main text color is `#3A3A3A`. Both are set in `styles/gear.css`.
- **Products:** Each product is a `.item` block in the `.items` grid. Copy one and update the image, title, price, and description.
- **Font:** Change the Google Fonts import and the `.poppins-medium` class to use a different typeface.

## Responsive Behavior

| Screen width | Layout                                                                 |
|--------------|------------------------------------------------------------------------|
| > 575px      | Multi-column product grid, side-by-side banner and featured sections   |
| ≤ 575px      | Stacked navigation, single-column products, 3-column logo strip        |

## Roadmap

- [ ] Add real links to navigation items
- [ ] Add JavaScript for search and cart functionality
- [ ] Improve accessibility (alt text for all images)
- [ ] Add tablet breakpoint

## Author

Created by IS Eyamin. Feel free to connect through the social links in the footer.

## License

Copyright © 2026  wanderlust products
