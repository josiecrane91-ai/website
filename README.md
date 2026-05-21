# AI Safety Personal Website

Welcome to my personal website portfolio. This site showcases my work, research, and passion for advancing AI safety and alignment.

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Professional Styling**: Modern, clean design with a focus on readability
- **AI Safety Focus**: Tailored sections for research, projects, and expertise in the AI safety domain
- **Easy to Customize**: Simple HTML/CSS structure for easy updates and personalization

## Sections

### Home
A welcoming hero section that introduces you and your focus on AI safety.

### About
Share your background, expertise, and key focus areas in AI safety. Includes:
- Personal introduction
- AI safety focus areas
- Core competencies

### Research
Showcase your research articles, publications, and whitepapers. Currently configured as a placeholder for future content.

### Projects
Display your AI safety projects with:
- Project descriptions
- Technology tags
- Links to project details or GitHub repositories

### Contact
Multiple ways for people to reach you:
- Email
- GitHub
- LinkedIn

## How to Use

### 1. Customize Your Information

Edit `index.html` and replace:
- `your-email@example.com` with your email
- `https://linkedin.com/in/yourprofile` with your LinkedIn profile
- Project titles and descriptions with your actual projects
- Research section placeholders with your publications

### 2. Update Styling (Optional)

The CSS variables in `styles.css` control the color scheme. Modify the `:root` section to customize:
- Primary color: `--color-primary`
- Accent color: `--color-accent`
- Typography and spacing

### 3. Deploy

You can deploy this website using:
- **GitHub Pages**: Enable in repository settings (Settings → Pages → Source: main)
- **Netlify**: Connect your GitHub repository
- **Vercel**: Import the repository and deploy
- **Traditional Hosting**: Upload files to any web server

## File Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # CSS styling
└── README.md           # This file
```

## Getting Started Checklist

- [ ] Update contact information (email, LinkedIn, GitHub)
- [ ] Add your project details and links
- [ ] Replace research placeholders with actual publications
- [ ] Customize the color scheme if desired
- [ ] Deploy to GitHub Pages or hosting provider
- [ ] Test on mobile devices

## GitHub Pages Deployment

1. Go to your repository settings
2. Navigate to "Pages" section
3. Set source to "Deploy from a branch"
4. Select `main` branch and `/ (root)` folder
5. Your site will be available at `https://josiecrane91-ai.github.io/website`

## Customization Tips

### Add More Projects
Duplicate the `.project-card` div in the Projects section and update the content.

### Add More Research Items
Duplicate the `.research-item` div in the Research section and update the content.

### Change Colors
Edit the CSS variables at the top of `styles.css`:
```css
:root {
    --color-primary: #2563eb;    /* Change this */
    --color-accent: #06b6d4;     /* And this */
}
```

### Add Social Links
Add more contact methods by duplicating the `.contact-item` div and updating the content.

## License

This website framework is open source. Feel free to modify and use it for your own portfolio.

---

**Ready to get started?** Edit `index.html` with your information and deploy to share your AI safety work with the world!
