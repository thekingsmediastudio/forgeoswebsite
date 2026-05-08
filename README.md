# Forge OS Website

Official website for Forge OS - The ultimate Android productivity platform.

## 🌟 Features

This website includes:

### Core Pages
- **Homepage** (`index.html`) - Main landing page with hero, features, use cases, and testimonials
- **Download** (`download.html`) - Download page with installation instructions, version history, and troubleshooting
- **Documentation** (`docs.html`) - Comprehensive documentation with guides, tutorials, and API reference
- **Blog** (`blog.html`) - Blog listing page with latest posts and updates
- **FAQ** (`faq.html`) - Frequently asked questions with search and category filtering
- **Showcase** (`showcase.html`) - Community showcase of amazing automations
- **Plugins** (`plugins.html`) - Plugin marketplace for extending Forge OS
- **Roadmap** (`roadmap.html`) - Development roadmap and feature voting
- **Comparison** (`comparison.html`) - Feature comparison with other Android automation tools
- **Privacy Policy** (`privacy.html`) - Privacy policy and data handling
- **Terms of Service** (`terms.html`) - Terms of service and legal information

### Blog Posts
- Forge OS Had a Rough Week
- Introducing the Plugin System
- Mastering Telegram Automation (placeholder)
- Running Python Scripts on Android (placeholder)
- Forge OS v2.0 Released (placeholder)
- Community Showcase (placeholder)

### Additional Features
- **Dark/Light Theme Toggle** - Persistent theme switching
- **Responsive Design** - Mobile-friendly layouts
- **Navigation Menu** - Easy access to all pages
- **Search Functionality** - Search FAQs and plugins
- **Category Filtering** - Filter content by category
- **RSS Feed** (`rss.xml`) - Subscribe to blog updates
- **Sitemap** (`sitemap.xml`) - SEO optimization
- **Robots.txt** - Search engine crawling instructions

## 🎨 Design

- **Fonts**: Clash Display (headings) and Satoshi (body) from Fontshare
- **Color Scheme**: Dark mode by default with light mode option
- **Icons**: SVG logos and sponsor images
- **Layout**: Modern, clean, and professional

## 📁 File Structure

```
.
├── index.html              # Homepage
├── download.html           # Download page
├── docs.html              # Documentation
├── blog.html              # Blog listing
├── faq.html               # FAQ page
├── showcase.html          # Community showcase
├── plugins.html           # Plugin marketplace
├── roadmap.html           # Development roadmap
├── comparison.html        # Feature comparison
├── privacy.html           # Privacy policy
├── terms.html             # Terms of service
├── sitemap.xml            # SEO sitemap
├── robots.txt             # Robots file
├── rss.xml                # RSS feed
├── blog/                  # Blog posts
│   ├── forgeos-rough-week.html
│   └── plugin-system-launch.html
├── assets/                # Images, CSS, JS
│   ├── forge_logo.png
│   ├── forge_favicon.png
│   ├── forge_process.png
│   ├── Layout.CwMxruYy.css
│   └── ...
└── sponsors/              # Sponsor logos
    └── ...
```

## 🚀 Getting Started

1. **Clone or download** this repository
2. **Open `index.html`** in a web browser
3. **Navigate** through the site using the navigation menu

## 🛠️ Customization

### Changing Colors
Edit the CSS variables in each HTML file's `<style>` section:
```css
:root {
  --accent: #6366f1;
  --primary-bg: #0f172a;
  --text-primary: #f1f5f9;
  /* ... */
}
```

### Adding Blog Posts
1. Create a new HTML file in the `blog/` directory
2. Use the existing blog post templates as a reference
3. Add the post to `blog.html` listing
4. Update `rss.xml` and `sitemap.xml`

### Updating Content
- Edit the HTML files directly
- Update version numbers in `download.html`
- Add new plugins to `plugins.html`
- Update roadmap timeline in `roadmap.html`

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## 🔍 SEO Features

- Semantic HTML structure
- Meta tags for social sharing (Open Graph, Twitter Cards)
- Sitemap for search engines
- RSS feed for blog subscribers
- Descriptive alt text for images
- Clean URL structure

## 🌐 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This website is part of the Forge OS project. See the main repository for license information.

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

- **Telegram**: [@forgebuilders](https://t.me/forgebuilders)
- **GitHub**: [thekingsmediastudio/forge-os](https://github.com/thekingsmediastudio/forge-os)
- **Email**: support@forgeos.ai

## 🎯 Future Enhancements

- [ ] Interactive demo/playground
- [ ] Video tutorials
- [ ] Live chat support
- [ ] User dashboard
- [ ] Plugin submission form
- [ ] Community forum integration
- [ ] Multi-language support
- [ ] Analytics dashboard
- [ ] Newsletter signup
- [ ] Search functionality across all pages

## 📊 Analytics

To add analytics, insert your tracking code before the closing `</head>` tag in each HTML file.

## 🔒 Security

- No external dependencies (except fonts)
- No tracking by default
- Privacy-focused design
- Secure external links (target="_blank" with rel attributes)

---

Built with ❤️ for the Forge OS community
