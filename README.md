# Business Website

A modern, responsive business website built with HTML, CSS, and JavaScript.

## Features

- 🎨 Modern, professional design
- 📱 Fully responsive (works on mobile, tablet, and desktop)
- ⚡ Fast loading with Tailwind CSS
- 🎯 Clean sections: Home, About, Services, Contact
- 📊 Stats section to showcase achievements
- 📝 Contact form
- 🎭 Smooth animations and transitions

## Tech Stack

- **HTML5** - Structure
- **Tailwind CSS** - Styling (via CDN)
- **JavaScript** - Interactive features

## Getting Started

### View Locally

1. Simply open `index.html` in your web browser
2. No build process or server required!

### Customize Your Website

#### Change Business Name and Branding
- Replace "YourBrand" with your actual business name in the navigation and footer
- Update the title in the `<head>` section

#### Update Content
- **Hero Section**: Change the main headline and tagline
- **About Section**: Add your company's story
- **Services Section**: Customize the three service boxes with your offerings
- **Stats Section**: Update numbers to reflect your business
- **Contact Section**: Update email, phone, and address in the footer
- **Colors**: To change the color scheme, replace `blue-600`, `blue-700`, etc. with other Tailwind colors

#### Add Your Logo
Replace the text logo with an image:
```html
<img src="logo.png" alt="Your Business" class="h-10">
```

## Deployment Options

### Option 1: GitHub Pages (Free)
1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select main branch → Save
4. Your site will be live at: `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)
1. Sign up at netlify.com
2. Drag and drop your project folder
3. Site goes live instantly!

### Option 3: Vercel (Free)
1. Sign up at vercel.com
2. Import your GitHub repository
3. Deploy automatically

## File Structure

```
business-website/
├── index.html          # Main website file
└── README.md          # This file
```

## Customization Tips

### Changing Colors
Tailwind uses color classes like `bg-blue-600`. You can change these to:
- `bg-red-600` (red theme)
- `bg-green-600` (green theme)
- `bg-purple-600` (purple theme)
- `bg-gray-600` (gray theme)

### Adding Images
To add images to your sections:
1. Create an `images` folder
2. Add your images there
3. Reference them: `<img src="images/your-image.jpg" alt="Description">`

### Making the Form Work
The current form doesn't send emails. To make it functional:
1. Use a service like Formspree, EmailJS, or Netlify Forms
2. Or add a backend (Node.js, PHP, etc.)

## Need Help?

- Tailwind CSS Documentation: https://tailwindcss.com/docs
- HTML/CSS Basics: https://developer.mozilla.org/en-US/docs/Web/HTML
- JavaScript Basics: https://developer.mozilla.org/en-US/docs/Web/JavaScript

## License

Free to use for your business!
