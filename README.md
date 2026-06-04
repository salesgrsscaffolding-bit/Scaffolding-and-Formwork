# Scaffolding and Formwork Landing Page

A professional, responsive landing page for showcasing scaffolding and formwork services with an embedded YouTube video.

## Features

- 🎥 **YouTube Video Integration** - Embedded video player with responsive design
- 📱 **Responsive Design** - Mobile-friendly layout that works on all devices
- 🎨 **Modern UI** - Clean, professional design with gradient accents
- ⚡ **Fast Loading** - Lightweight HTML with minimal dependencies
- ♿ **Accessible** - Semantic HTML and proper accessibility attributes

## Files

- `index.html` - Main landing page

## How to Use

1. **Replace the YouTube Video ID**
   - Open `index.html`
   - Find the line with `src="https://www.youtube.com/embed/dQw4w9WgXcQ"`
   - Replace `dQw4w9WgXcQ` with your YouTube video ID
   - To get your video ID: Go to your YouTube video, copy the ID from the URL (the part after `v=`)

2. **Customize Content**
   - Edit the title and description in the header section
   - Update the "About Our Services" text
   - Modify feature cards to match your services
   - Update footer information

3. **View Locally**
   - Simply open `index.html` in your web browser
   - No server required

## Customization

### Update Video
Replace the video ID in the iframe `src` attribute:
```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID_HERE"
```

### Change Colors
The primary gradient colors are defined in the CSS:
- Primary: `#667eea` (purple-blue)
- Secondary: `#764ba2` (purple)

Edit the `style` section to customize colors.

### Add More Sections
Simply duplicate feature cards or content sections and modify as needed.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Deployment

You can deploy this landing page to:
- GitHub Pages (free)
- Netlify (free)
- Vercel (free)
- Any web hosting service

## License

Free to use and modify for your scaffolding and formwork business.

## Support

For customizations or issues, please create an issue in the repository.
