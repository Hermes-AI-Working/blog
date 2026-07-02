# Ember & Ink - Premium Tech Editorial Website

A premium tech editorial website template built with HTML, Tailwind CSS, and modern web design principles. Inspired by high-end tech publications, this template features dark mode aesthetics, gradient accents, glass morphism effects, and smooth animations.

## 🌟 Features

- **Dark Mode Design**: Sophisticated dark theme with orange/red accent gradients
- **Responsive Layout**: Fully responsive design that works on mobile, tablet, and desktop
- **Modern UI Components**: Glass cards, hover effects, smooth animations, and parallax scrolling
- **Premium Typography**: Uses Hanken Grotesk, Inter, JetBrains Mono, and Geist fonts
- **Interactive Elements**: Hover effects, reveal-on-scroll animations, and interactive buttons
- **Complete Page Set**: Home, About, Blog, Contact, Admin Dashboard, and 404 pages

## 📁 File Structure

```
├── index.html          # Homepage with featured article and hero section
├── about.html          # About page with mission and team information
├── blog.html           # Blog listing page with featured posts
├── contact.html        # Contact form and information page
├── admin.html          # Admin dashboard CMS interface
├── 404.html            # Custom 404 error page
└── README.md           # This file
```

## 🛠️ Technology Stack

- **HTML5** - Semantic markup structure
- **Tailwind CSS v3** - Utility-first CSS framework (via CDN)
- **Custom CSS** - Additional styles for gradients, glass effects, and animations
- **Google Fonts** - Hanken Grotesk, Inter, JetBrains Mono, Geist
- **Material Symbols** - Icons via Google Fonts
- **JavaScript** - Scroll reveal animations and parallax effects

## 🎨 Design System

### Color Palette
- **Primary**: `#ffb4a8` (soft coral/red)
- **Secondary**: `#ffdad7` (light coral)
- **Accent**: `#d00000` (rich red), `#a90219` (deep red), `#690000` (dark red)
- **Background**: `#200f0c` (dark ink black)
- **Surface**: `#2e1b18` (dark surface)
- **Text**: `#fedbd5` (light parchment)

### Typography
- **Headlines**: Hanken Grotesk (bold, impactful)
- **Body**: Inter (clean, readable)
- **Code/Technical**: JetBrains Mono (monospace)
- **UI/Labels**: Geist (clean, modern)

## 🚀 Getting Started

### Option 1: GitHub Pages (Recommended)
1. Fork this repository
2. Go to Settings > Pages
3. Select the `main` branch and `/root` folder
4. Your site will be live at `https://[username].github.io/blog/`

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/Hermes-AI-Working/blog.git

# Navigate to the directory
cd blog

# Start a local server (Python)
python -m http.server 8080

# Or use any static server of your choice
```

### Option 3: Direct HTML Files
Simply open any `.html` file in your web browser to view that page.

## 🔧 Customization

### Changing Content
- Edit the HTML files directly to update text, images, and links
- All images are currently hosted externally (Googleusercontent.com) - replace with your own
- Update navigation links in the header as needed

### Modifying Styles
- Tailwind configuration is in the `<script id="tailwind-config">` tag in each HTML file
- Custom CSS is in the `<style>` tags in each file's `<head>`
- To change colors globally, update the Tailwind config colors section

### Adding New Pages
1. Copy an existing HTML file
2. Update the content as needed
3. Add a link to the navigation menu in other pages
4. Ensure the Tailwind config is included in the new page's head

## 📱 Responsive Breakpoints

The template uses Tailwind's default breakpoints:
- **sm**: 640px
- **md**: 768px  
- **lg**: 1024px
- **xl**: 1280px
- **2xl**: 1536px

## 🎯 Features Breakdown

### Homepage (index.html)
- Hero section with featured article and call-to-action buttons
- Statistics section with reader counts and metrics
- Bento grid layout for latest posts
- Newsletter signup form
- Categories and popular posts sidebar
- Expert testimonials and author spotlight

### About Page (about.html)
- Mission statement and publication overview
- Team information and credentials
- Editorial standards and values
- Contact and partnership information

### Blog Page (blog.html)
- Grid layout of blog posts
- Featured post highlights
- Category filtering
- Pagination ready (implement as needed)

### Contact Page (contact.html)
- Contact form (connect to your preferred service)
- Office information and social links
- Newsletter subscription

### Admin Dashboard (admin.html)
- CMS interface mockup
- Content management overview
- Analytics and metrics display
- User management controls

## 🤝 Contributing

Feel free to fork this repository and customize it for your needs. If you'd like to contribute improvements:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available for personal and commercial use. Attribution is appreciated but not required.

## 🙏 Acknowledgments

- Tailwind CSS for the utility-first framework
- Google Fonts for the beautiful typography
- Material Symbols for the clean icon set
- Inspired by premium tech publications like Ember & Ink

---

*Built with ❤️ for tech enthusiasts, developers, and designers who appreciate beautiful, functional design.*