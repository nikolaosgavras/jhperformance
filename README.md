# JH Performance Website

A professional website for JH Performance, featuring information about services, contact details, and company information.

## Project Structure

```
.
├── css/           # Stylesheet files
├── js/            # JavaScript files
├── images/        # Image assets
├── index.html     # Homepage
├── about.html     # About page
├── services.html  # Services page
├── contact.html   # Contact page
├── formsuccess.html # Form submission success page
├── robots.txt     # Search engine crawling instructions
├── sitemap.xml    # XML sitemap for search engines
└── .htaccess      # Apache server configuration
```

## Pages

- **Home** (`index.html`): Main landing page
- **About** (`about.html`): Company information and background
- **Services** (`services.html`): Details about offered services
- **Contact** (`contact.html`): Contact form and information
- **Form Success** (`formsuccess.html`): Confirmation page for form submissions

## Setup

1. Clone the repository:
   ```bash
   git clone [https://github.com/nikolaosgavras/jhperformance.git]
   ```

2. The website can be served using any web server that supports static file hosting. For local development, you can use:
   - Python's built-in HTTP server:
     ```bash
     python -m http.server 8000
     ```
   - PHP's built-in server:
     ```bash
     php -S localhost:8000
     ```
   - Or any other web server of your choice

3. Access the website by opening `http://localhost:8000` in your web browser

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Apache Server (for production)

## Server Requirements

- Apache web server with mod_rewrite enabled (for .htaccess support)
- Support for static file serving

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is proprietary and confidential. All rights reserved.

## Contact

For any inquiries, please use the contact form on the website or reach out through the provided contact information. 