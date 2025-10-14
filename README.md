# GameHub - Video Games Shop

GameHub is a static website designed as an online video games shop. It provides users with a platform to browse featured games, learn about the store, contact support, and manage accounts through login and registration pages. The site is built with a clean, responsive design to ensure a great user experience across devices.

## Features

- **Home Page**: Hero section with a welcome message and call-to-action, featured games grid with pricing and add-to-cart buttons.
- **Games Page**: Browse all available games (linked from home).
- **About Page**: Information about GameHub and its team.
- **Contact Page**: Contact form and details for support.
- **Login/Register Pages**: User authentication forms.
- **Cart and Checkout**: Pages for managing shopping cart and completing purchases.
- **Thank You Page**: Confirmation page after successful actions.
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices using CSS media queries.
- **Newsletter Subscription**: Form to subscribe for updates.
- **Footer**: Quick links, contact info, and social media placeholders.

## Technologies Used

- **HTML5**: Structure and content of the website.
- **CSS3**: Styling, including custom styles in `style.css`, Google Fonts integration via `css2.css`, and Font Awesome icons via `all.min.css`.
- **Font Awesome**: Icons for navigation, buttons, and UI elements.
- **Images**: Game covers, banners, and team photos stored in the `images/` folder.

## Project Structure

```
video-games-shop-main/
├── css/
│   ├── style.css          # Main stylesheet with custom styles
│   ├── css2.css           # Google Fonts definitions
│   └── all.min.css        # Font Awesome icons
├── images/
│   ├── background.jpg     # Hero background
│   ├── gow_ragnarok.png   # Game image
│   ├── deadlink.png       # Game image
│   ├── dmc.png            # Game image
│   ├── re_village.png     # Game image
│   ├── cyberpunk.png      # Game image
│   ├── cod_warzone.png    # Game image
│   ├── about_background.jpg
│   ├── contact_background.jpg
│   ├── cart_banner.png
│   ├── checkout_banner.png
│   ├── login_banner.png
│   ├── register_banner.png
│   ├── thanks_banner.png
│   ├── team_1.png
│   ├── team_2.png
│   ├── team_3.png
│   └── home ss.png        # Screenshot or logo
└── pages/
    ├── index.html         # Home page
    ├── games.html         # Games listing
    ├── about.html         # About page
    ├── contact.html       # Contact page
    ├── login.html         # Login page
    ├── register.html      # Registration page
    ├── cart.html          # Shopping cart
    ├── checkout.html      # Checkout page
    └── thanks.html        # Thank you page
```

## Installation and Setup

Since this is a static website, no server or build process is required. Follow these steps to run the project locally:

1. **Clone the Repository**:
   ```
   git clone https://github.com/Arham43-ops/video-games-shop.git
   cd video-games-shop-main
   ```

2. **Open in Browser**:
   - Open `pages/index.html` in your preferred web browser.
   - Navigate through the site using the links in the navigation menu.

3. **Optional: Serve Locally** (if you prefer a local server):
   - Use a simple HTTP server like Python's built-in server:
     ```
     python -m http.server 8000
     ```
   - Then open `http://localhost:8000/pages/index.html` in your browser.

## Screenshots

- **Home Page**: Features a hero banner, featured games grid, and newsletter signup.
- **Games Page**: Displays all games with images, prices, and add-to-cart options.
- **About Page**: Team photos and company information.
- **Contact Page**: Form for inquiries with contact details.

*(Screenshots can be added to the `images/` folder and referenced here for better visualization.)*

## Contributing

Contributions are welcome! If you'd like to improve the site:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/new-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Create a Pull Request.

Please ensure your code follows the existing style and is tested across different browsers.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- **Arham Topiwala** - Initial work and development.

For questions or support, contact support@gamehub.com or visit the [Contact Page](pages/contact.html).

---

*Note: This is a front-end only project. For a full e-commerce functionality, backend integration (e.g., with Node.js, PHP, or a framework like React) would be needed.*
