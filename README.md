# Sagar Sharma - Data Analyst Portfolio

A modern, responsive portfolio website showcasing data analytics projects, skills, and professional experience.

## 🚀 Features

- **Responsive Design**: Optimized for mobile, tablet, and desktop
- **Dark/Light Mode**: Toggle between themes with persistent preference
- **Smooth Animations**: Subtle transitions and hover effects
- **SEO Optimized**: Meta tags and semantic HTML
- **Fast Loading**: Optimized CSS and minimal dependencies
- **Professional Design**: Clean, modern UI that impresses recruiters

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Styles (inline in HTML for single-file deploy)
├── js/
│   └── main.js        # JavaScript (inline in HTML for single-file deploy)
├── assets/
│   └── resume.pdf     # Your resume file (add this)
├── images/
│   └── (optional)     # Profile photo or project images
└── README.md          # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript**: Theme toggle, mobile menu, smooth scrolling
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 📦 Deployment Options

### Option 1: GitHub Pages (Recommended)

1. Create a new repository named `<your-username>.github.io`
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select "main" branch as source
5. Your site will be live at `https://<your-username>.github.io`

**Quick Deploy:**
```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
git push -u origin main
```

### Option 2: Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts
4. Your site will be live instantly

**Or use Vercel GUI:**
- Go to [vercel.com](https://vercel.com)
- Import your GitHub repository
- Click Deploy

### Option 3: Netlify

1. Drag and drop your folder to [netlify.com/drop](https://netlify.com/drop)
2. Or connect your GitHub repository
3. Your site will be live in seconds

### Option 4: Local Development

Simply open `index.html` in your browser:
```bash
# If you have Python installed
python -m http.server 8000
# Then visit http://localhost:8000

# Or use VS Code Live Server extension
```

## ✏️ Customization

### Update Personal Information

Edit the HTML file to update:
- Name and title
- Contact information (email, phone, LinkedIn, GitHub)
- Project descriptions and links
- Skills and certifications
- Work experience

### Change Theme Colors

In the CSS section, update the color variables:
```css
:root {
    --accent-blue: #3b82f6;    /* Primary color */
    --accent-purple: #8b5cf6;  /* Secondary color */
    --accent-pink: #ec4899;    /* Accent color */
}
```

### Add Your Resume

Place your resume PDF in the `assets/` folder and update the download link in the HTML.

### Add Profile Photo

1. Add your photo to the `images/` folder
2. Replace the avatar div with an img tag:
```html
<img src="images/profile.jpg" alt="Sagar Sharma" class="hero-avatar">
```

## 📱 Testing

Test your portfolio on:
- ✅ Desktop (Chrome, Firefox, Safari, Edge)
- ✅ Tablet (iPad, Android tablets)
- ✅ Mobile (iPhone, Android phones)
- ✅ Dark and Light modes
- ✅ Different screen sizes

## 🔧 Maintenance

### Regular Updates

1. Keep projects section updated with new work
2. Add new certifications as you earn them
3. Update skills as you learn new technologies
4. Refresh experience section with new roles

### SEO Optimization

- Update meta descriptions for better search ranking
- Add alt text to images
- Use semantic HTML
- Keep content fresh and relevant

## 📊 Analytics (Optional)

Add Google Analytics to track visitors:

```html
<!-- Add before </head> -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

## 🐛 Troubleshooting

**Dark mode not persisting?**
- Check browser localStorage is enabled

**Mobile menu not working?**
- Ensure JavaScript is enabled
- Check console for errors

**Fonts not loading?**
- Verify internet connection
- Check Google Fonts CDN is accessible

**Links not working?**
- Update all URLs with your actual profiles
- Ensure GitHub repos are public

## 📄 License

This portfolio template is free to use and customize for personal use.

## 🤝 Contributing

Found a bug or want to suggest an improvement?
- Open an issue on GitHub
- Submit a pull request

## 📞 Contact

**Sagar Sharma**
- Email: ssharma9663@gmail.com
- LinkedIn: [linkedin.com/in/sagar-sharma-712ba4324](https://www.linkedin.com/in/sagar-sharma-712ba4324/)
- GitHub: [github.com/SagarSharma01-ai](https://github.com/SagarSharma01-ai)
- Phone: +91 8920459663

---

**Built with ❤️ by Sagar Sharma | Data Analyst**

Last Updated: December 2025