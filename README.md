# fr3hugs

A beautiful, mobile-first link aggregator page built with Gatsby, similar to Linktree or Hoo.be.

## Features

- 🎨 Modern, gradient design with smooth animations
- 📱 Mobile-first and fully responsive
- 🚀 Fast static site generation with Gatsby
- 🤗 Profile section with avatar
- 🔗 Social media links (Instagram, 𝕏/Twitter)
- ✨ Hover and touch interactions

## Development

```bash
# Install dependencies
npm install

# Start development server
npm run develop
# Visit http://localhost:8000

# Build for production
npm run build

# Serve production build
npm run serve
# Visit http://localhost:9000
```

## Project Structure

```
fr3hugs/
├── src/
│   ├── pages/
│   │   └── index.js          # Main landing page
│   └── styles/
│       └── global.css        # Global styles
├── gatsby-config.js          # Gatsby configuration
└── package.json              # Dependencies and scripts
```

## Customization

To customize the links and content, edit `src/pages/index.js`:
- Update the profile name and bio
- Change social media URLs
- Add or remove link buttons
- Modify the avatar emoji

To customize the design, edit `src/styles/global.css`:
- Change the gradient background
- Modify button colors
- Adjust spacing and sizes
- Update animations

## Deployment

The site can be deployed to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

Build the site with `npm run build`, then deploy the `public/` directory.

## License

MIT