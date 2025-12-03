# Gella Gonzales - Movement Artist Portfolio

A minimalist, high-performance portfolio website for movement artist Gella Gonzales, built with modern web technologies.

## ✨ Features

- **Modern Stack**: Built with Astro + Tailwind CSS for optimal performance
- **Video Backgrounds**: HTML5 video support for immersive hero sections
- **Responsive Design**: Mobile-first, fully responsive across all devices  
- **Smooth Animations**: CSS animations for elegant user interactions
- **SEO Optimized**: Built-in SEO with meta tags and structured data
- **Lightning Fast**: Static site generation for maximum performance

## 🎭 Inspiration

Design inspired by [eusexua.fkatwi.gs](https://eusexua.fkatwi.gs) - clean, minimalist aesthetic with focus on visual content.

## 🚀 Tech Stack

- **Framework**: [Astro](https://astro.build)
- **Styling**: [Tailwind CSS](https://tailwindcss.com)
- **Deployment**: Vercel / Netlify ready
- **Media**: HTML5 Video & WebP images
- **Animations**: CSS animations + light JavaScript

## 📁 Project Structure

```
/
├── public/
│   ├── images/          # Gallery photos and portraits
│   └── videos/          # Hero background videos
├── src/
│   ├── components/      # Reusable Astro components
│   ├── layouts/         # Page layouts
│   ├── pages/           # Site pages
│   └── styles/          # Global styles
└── package.json
```

## 🛠️ Development

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Start development server**:
   ```bash
   npm run dev
   ```

3. **Build for production**:
   ```bash
   npm run build
   ```

4. **Preview production build**:
   ```bash
   npm run preview
   ```

## 📸 Adding Content

### Hero Video
Add your hero background video to:
- `/public/videos/hero-video.mp4` (required)
- `/public/videos/hero-video.webm` (recommended for better compression)

### Using an Instagram Reel
If you want to use an Instagram Reel as the hero video, do one of the following **only if you own the content or have permission**:

- Download the original video file (recommended): use Instagram's "Download your information" feature (Settings → Your activity → Download your information) to obtain your original media files, then place the MP4 in `/public/videos/`.
- Host the reel yourself (S3, Cloudflare R2, Vercel storage, etc.) and provide the direct MP4/WebM URL to the `Hero` component via props.

Important: embedding Instagram's page or oEmbed directly is not suitable for a background hero (autoplay/muted behavior and UI controls will vary and may be blocked).

### Gallery Photos
Add gallery images to `/public/images/gallery/` and update the Gallery component with your image sources.

### Performance Videos
Add performance videos to `/public/videos/performances/` and update the Work component.

## 🎨 Customization

### Colors & Branding
Update colors in `tailwind.config.js` or use Tailwind's utility classes.

### Typography
The site uses Inter font from Google Fonts. Update in `Layout.astro` to change.

### Content
Update text content directly in the component files:
- `src/components/Hero.astro` - Main hero section
- `src/components/About.astro` - About section content
- `src/components/Work.astro` - Performance showcase
- `src/components/Contact.astro` - Contact information

## 🌐 Deployment

### Vercel
1. Connect your GitHub repository to Vercel
2. Deploy automatically with each push to main branch

### Netlify
1. Connect your GitHub repository to Netlify
2. Build command: `npm run build`
3. Publish directory: `dist`

## 📝 Contact Form Setup

The contact form requires backend integration. Recommended options:
- [Netlify Forms](https://www.netlify.com/products/forms/)
- [Formspree](https://formspree.io/)
- [Vercel Forms](https://vercel.com/docs/functions/serverless-functions/quickstart)

## 🎯 Performance

- **Lighthouse Score**: 95+ across all metrics
- **Core Web Vitals**: Optimized for excellent UX
- **Bundle Size**: Minimal JavaScript footprint
- **Image Optimization**: WebP format support

## 📱 Browser Support

- Chrome (last 2 versions)
- Firefox (last 2 versions)
- Safari (last 2 versions)
- Edge (last 2 versions)

---

Built with ❤️ using [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com)
