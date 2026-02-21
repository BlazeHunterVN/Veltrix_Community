<div align="center">

# 🔥 Veltrix Community - Free Fire Fan Gallery

[![Website Status](https://img.shields.io/website?url=https%3A%2F%2Fveltrixcommunity.vercel.app&style=for-the-badge&label=LIVE%20STATUS)](https://veltrixcommunity.vercel.app)
[![License MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Performance](https://img.shields.io/badge/Performance-A+-success?style=for-the-badge)](#-seo-features)
[![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com)

**Unofficial Free Fire Media Gallery & News Hub 🎮**

[🌐 Official Website](https://veltrixcommunity.vercel.app) • [📋 Features](#-features) • [🚀 Tech Stack](#-tech-stack) • [📦 Installation](#-installation) • [🔧 Configuration](#-configuration)

![Veltrix Community Banner](https://veltrixcommunity.vercel.app/assets/image/VC_SHORT_RED.png)

</div>

---

## 📑 Table of Contents

- [📖 About](#-about)
- [✨ Features](#-features)
- [🏗️ Project Structure](#️-project-structure)
- [🚀 Tech Stack](#-tech-stack)
- [📦 Installation](#-installation)
- [🔧 Configuration](#-configuration)
- [🎨 Customization](#-customization)
- [🚀 Deployment](#-deployment)
- [🔍 SEO Features](#-seo-features)
- [🛡️ Security](#️-security)
- [🏷️ Keywords](#️-keywords)
- [📄 License](#-license)
- [🤝 Contributing](#-contributing)
- [📞 Contact](#-contact)

---

## 📖 About

**Veltrix Community** is a comprehensive, fan-made Free Fire media archive featuring:
- 🗺️ **Multi-Regional Content**: Brazil, India, Indonesia, Pakistan, Singapore, Taiwan, Thailand, Vietnam
- 📰 **Latest News**: Real-time Free Fire news and updates
- 🏆 **Esports Coverage**: Tournament schedules, team updates, and competition results
- 🤖 **AI Assistant**: Powered by Chatbase for instant support and information

> **Note**: This is an unofficial fan-made project. Free Fire is a registered trademark of Garena.

---

## ✨ Features

### 🎨 User Experience
- ✅ **Responsive Design** - Seamless experience across desktop, tablet, and mobile
- ✅ **Dark Mode** - Eye-friendly browsing with modern aesthetics
- ✅ **Bilingual Support** - English & Vietnamese (EN/VI)
- ✅ **Fast Loading** - Optimized performance with lazy loading
- ✅ **AI Chatbot** - 24/7 intelligent assistant for Free Fire queries

### 🔐 Security & Privacy
- ✅ **Content Security Policy** (CSP) - Protection against XSS attacks
- ✅ **No Tracking** - Zero personal data collection
- ✅ **No Registration** - Anonymous browsing experience
- ✅ **Content Protection** - Disabled right-click and text selection

### 📱 SEO & Performance
- ✅ **SEO Optimized** - Complete meta tags, Open Graph, structured data
- ✅ **Sitemap & Robots.txt** - Full search engine coverage
- ✅ **PWA Support** - Installable as progressive web app
- ✅ **Performance Score A+** - Optimized assets and caching

---

## 🏗️ Project Structure

```
WEBSITE_FF_NEW_V4/
├── 📄 index.html                    # Homepage with latest news preview
├── 📄 404.html                      # Custom error page
├── 📄 operating-policy.html         # Operating policy (EN/VI)
├── 📄 terms-of-use.html             # Terms of use (EN/VI)
├── 📄 sitemap.xml                   # SEO sitemap (auto-generated)
├── 📄 robots.txt                    # Search engine crawler rules
├── 📄 manifest.json                 # PWA manifest
├── 📄 vercel.json                   # Vercel deployment config
├── 📄 package.json                  # Node.js dependencies
├── 📄 .env                          # Environment variables
├── 📄 .gitignore                    # Git ignore rules
├── 📄 README.md                     # Project documentation
│
├── 📁 admin/                        # Admin panel (protected)
│   ├── 📄 index.html                # Admin dashboard
│   └── 📁 assets/
│       ├── 📁 css/                  # Admin-specific styles
│       │   └── style.css
│       └── 📁 js/                   # Admin-specific scripts
│           └── app.js
│
├── 📁 api/                          # Serverless API functions
│   ├── 📄 chat.js                   # Chat API endpoint
│   ├── 📄 admin.js                  # Admin operations
│   └── 📄 config.js                 # Configuration endpoint
│
├── 📁 assets/                       # Public assets
│   ├── 📁 css/                      # Stylesheets
│   │   ├── style.min.css            # Main stylesheet (minified)
│   │   └── chat_style.css           # Chat widget styles
│   │
│   ├── 📁 js/                       # JavaScript files
│   │   ├── script.js                # Main script (latest)
│   │   └── script.min.js            # Main script (minified)
│   │
│   ├── 📁 fonts/                    # Custom web fonts
│   │   ├── Exo-Bold.ttf
│   │   ├── Exo-Regular.ttf
│   │   └── Exo-SemiBold.ttf
│   │
│   ├── 📁 image/                    # Images & logos
│   │   ├── VELTRIX.png
│   │   └── ...
│   │
│   ├── 📁 icon/                     # Icons & favicons
│   │   └── ...
│   │
│   ├── 📁 json/                     # Static JSON data
│   │   ├── language.json            # Translation strings
│   │   ├── translations.json        # Localization data
│   │   └── region_config.json       # Regional configurations
│   │
│   └── 📄 bot_prompt.md             # AI chatbot configuration
│
└── 📁 scripts/                      # Build & deployment tools
    ├── minify.js                    # CSS/JS minification (Node.js)
    ├── minify.py                    # CSS/JS minification (Python)
    └── minify.ps1                   # CSS/JS minification (PowerShell)
```

---

## 🚀 Tech Stack

### Frontend
- **HTML5** - Semantic markup with SEO optimization
- **CSS3** - Modern styling with animations and transitions
- **Vanilla JavaScript** - Zero framework dependencies for fast performance

### Backend & Services
- **Supabase** - Database and authentication
- **ImageKit** - CDN and image optimization
- **Chatbase** - AI-powered chatbot integration
- **Vercel** - Serverless deployment and hosting

### Build Tools
- **Node.js** - Asset minification
- **PowerShell/Python** - Cross-platform build scripts

---

## 📦 Installation

### Prerequisites
- Node.js 16+ (optional, for minification)
- Git

### Local Development

```bash
# Clone repository
git clone https://github.com/BlazeHunterVN/veltrix-community.git
cd veltrix-community

# Install dependencies (optional, for minification)
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your Supabase credentials

# Serve locally (using any static server)
# Option 1: VS Code Live Server extension
# Option 2: Node.js http-server
npx http-server -p 8000

# Open browser at http://localhost:8000
```

### Environment Variables

Create `.env` file in root:

```env
SUPABASE_URL=your_supabase_project_url
SUPABASE_ANON_KEY=your_supabase_anon_key
CHATBASE_BOT_ID=your_chatbase_bot_id
```

> **Security Note**: Never commit `.env` to version control. It's already included in `.gitignore`.

---

## 🔧 Configuration

### Chatbase AI Assistant

1. **Create Chatbase Account**: [chatbase.co](https://www.chatbase.co)
2. **Configure Bot**:
   - Add data sources (website URLs, documents)
   - Customize appearance (colors, avatar, welcome message)
   - Disable domain restrictions for development
3. **Update Script**: Replace `JrqXeshbSI2ekMahrwear` with your bot ID in HTML files

### Supabase Database

1. **Create Tables**:
   - `nation_banners` - Event banners and posters by region
   - `news` - News articles
   - `admins` - Admin authentication
   - `home_settings` - Homepage background configurations

2. **Set Up Row Level Security (RLS)**:
   - Public read access for banners and news
   - Admin-only write access with authentication

---

## 🎨 Customization

### Branding
Edit `manifest.json` for PWA settings:
```json
{
  "name": "Your Site Name",
  "short_name": "Short Name",
  "theme_color": "#FF6B00",
  "background_color": "#1a1a1a"
}
```

### Styles
Modify `assets/css/style.min.css` or source CSS files

### Content
Update language files in `assets/json/language.json`

---

## 🚀 Deployment

### Deploy to Vercel (Recommended)

The simplest deployment method:

1. **Fork this repository**
2. **Import to Vercel**: [vercel.com/new](https://vercel.com/new)
3. **Configure environment variables** in Vercel dashboard
4. Click **Deploy**

Or use Vercel CLI:

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel

# Production deployment
vercel --prod
```

### Alternative Platforms
- **Netlify**: Drag & drop deployment
- **GitHub Pages**: Static hosting (requires build step)
- **Firebase Hosting**: Google infrastructure
- **Cloudflare Pages**: Edge network deployment

---

## 🔍 SEO Features

### Implemented Optimizations
- ✅ **Meta Tags**: Title, description, keywords on every page
- ✅ **Open Graph**: Social media previews (Facebook, Twitter, LinkedIn)
- ✅ **Structured Data**: JSON-LD schema markup for rich snippets
- ✅ **Canonical URLs**: Prevent duplicate content penalties
- ✅ **XML Sitemap**: All 14 pages indexed with priorities
- ✅ **Robots.txt**: Crawler directives with admin exclusion
- ✅ **Alt Text**: All images described for accessibility and SEO
- ✅ **Semantic HTML**: Proper heading hierarchy (H1-H6)
- ✅ **Mobile-First**: Responsive design with mobile optimization
- ✅ **Fast Loading**: Performance optimization with lazy loading
- ✅ **HTTPS**: Secure connection with SSL/TLS
- ✅ **Clean URLs**: SEO-friendly URL structure

### Performance Metrics
- 🚀 **Page Load**: < 2s
- 🎯 **First Contentful Paint**: < 1.5s
- ⚡ **Time to Interactive**: < 3s
- 📊 **Lighthouse Score**: 95+
- 🎨 **Cumulative Layout Shift**: < 0.1

---

## 🛡️ Security

### Content Security Policy
Strict CSP configured in `vercel.json`:
- Scripts only from whitelisted domains (CDN, Supabase, Chatbase)
- Frame protection to prevent clickjacking
- XSS protection headers
- HTTPS enforcement

### Additional Security
- **XSS Protection** headers enabled
- **MIME type sniffing** disabled
- **Referrer policy** configured
- **Admin panel** hidden from search engines (`robots.txt`)
- **Environment variables** protected via `.gitignore`
- **No sensitive data** in client-side code

---

## 🏷️ Keywords

**For SEO and GitHub Discovery:**

`free-fire` `free-fire-news` `free-fire-events` `garena-free-fire` `ff-max` `free-fire-gallery` `game-news` `esports` `gaming-website` `vercel-deployment` `supabase` `ai-chatbot` `chatbase` `imagekit` `responsive-design` `pwa` `progressive-web-app` `multi-language` `vietnam` `brazil` `india` `indonesia` `taiwan` `thailand` `singapore` `pakistan` `seo-optimized` `performance-optimized` `vanilla-javascript` `html5` `css3` `serverless` `fan-made` `community-project`

---

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

**Disclaimer**: This is an unofficial fan-made project. Free Fire is a registered trademark of Garena. This site is not affiliated with, endorsed by, or sponsored by Garena International Private Limited or any of its subsidiaries.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### How to Contribute:

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request

### Contribution Guidelines:
- Follow existing code style
- Test your changes locally
- Update documentation if needed
- Keep commits focused and descriptive

---

## 📞 Contact

- **Website**: [veltrixcommunity.vercel.app](https://veltrixcommunity.vercel.app)
- **Email**: Contact via website contact form
- **Issues**: Report bugs or request features via GitHub Issues

---

## 🌟 Show Your Support

If you find this project helpful, please consider:
- ⭐ **Star this repository**
- 🐛 **Report bugs** to help improve
- 💡 **Suggest features** for future updates
- 📢 **Share with the Free Fire community**

---

<div align="center">

**Made with ❤️ by the Free Fire Community**

⭐ Star this repo if you find it helpful!

[Back to top ↑](#-veltrix-community---free-fire-fan-gallery)

</div>
