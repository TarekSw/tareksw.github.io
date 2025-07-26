# Tarek Sw Personal Blog

A professional Jekyll-based blog and portfolio website showcasing my journey in computer science and cloud technologies.

## 🌐 Live Site

**URL:** [https://tareksw.github.io/](https://tareksw.github.io/)

## 📋 Features

- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Blog Posts** - Share technical insights and experiences
- **Professional Certifications** - Showcase AWS certifications and achievements
- **RSS Feed** - Stay updated with latest posts
- **Social Integration** - Connect via GitHub and Twitter
- **Google Analytics** - Track site performance

## 🛠️ Technology Stack

- **Jekyll 4.2.1** - Static site generator
- **GitHub Pages** - Hosting platform
- **HTML5 & CSS3** - Modern web standards
- **Responsive Grid** - Mobile-first design
- **Rouge** - Syntax highlighting
- **Kramdown** - Markdown processor

## 🚀 Local Development

### Prerequisites
- Ruby (2.6 or higher)
- Bundler
- Jekyll

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/TarekSw/tareksw.github.io.git
   cd tareksw.github.io
   ```

2. **Install dependencies:**
   ```bash
   bundle install
   ```

3. **Start development server:**
   ```bash
   bundle exec jekyll serve
   ```

4. **View locally:**
   Open [http://localhost:4000](http://localhost:4000) in your browser

## 📝 Adding Content

### Creating Blog Posts

1. Create a new file in `_posts/` directory
2. Use the naming convention: `YYYY-MM-DD-title-of-post.md`
3. Add Jekyll front matter:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: 2024-01-15 10:00:00 +0000
   categories: [category1, category2]
   tags: [tag1, tag2]
   ---
   ```

### Adding Certification Images

1. Place certification badge images in `/assets/` directory
2. Use PNG format for best quality
3. Recommended size: 200x200 pixels
4. Update the image paths in `certifications.md`

## 📂 Project Structure

```
tareksw.github.io/
├── _config.yml          # Jekyll configuration
├── _includes/           # Reusable HTML components
│   ├── footer.html
│   ├── head.html
│   └── header.html
├── _layouts/            # Page templates
│   ├── default.html
│   ├── page.html
│   └── post.html
├── _posts/              # Blog posts
├── _site/               # Generated site (auto-generated)
├── assets/              # Images and static files
├── css/                 # Stylesheets
│   └── main.css
├── about.md             # About page
├── certifications.md    # Certifications showcase
├── index.html           # Homepage
└── feed.xml             # RSS feed
```

## 🎨 Customization

### Updating Site Information
Edit `_config.yml` to update:
- Site title and description
- Social media usernames
- Analytics tracking code

### Modifying Styles
Edit `css/main.css` to customize:
- Colors and fonts
- Layout and spacing
- Responsive breakpoints

## 🚀 Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `master` branch.

### Manual Deployment Steps:
1. Commit your changes
2. Push to GitHub: `git push origin master`
3. GitHub Pages will automatically build and deploy

## 📊 Analytics

Google Analytics is configured to track site performance. The tracking ID is set in `_includes/head.html`.

## 🤝 Connect With Me

- **GitHub:** [@TarekSw](https://github.com/TarekSw)
- **Twitter:** [@TarekSwaidane](https://twitter.com/TarekSwaidane)
- **Website:** [tareksw.github.io](https://tareksw.github.io/)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with ❤️ using Jekyll and hosted on GitHub Pages*