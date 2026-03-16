# MD2PDF - Markdown to PDF Converter

A beautiful, professional Markdown to PDF converter that runs entirely in your browser. No backend required, no data leaves your device.

![MD2PDF Screenshot](https://via.placeholder.com/800x400/3b82f6/ffffff?text=MD2PDF+Screenshot)

## Features

- **Live Preview** - See your rendered Markdown instantly as you type
- **Drag & Drop** - Drop `.md`, `.markdown`, or `.txt` files directly into the editor
- **Multiple PDF Templates** - Choose from Minimal, Academic, or Modern styles
- **Client-Side PDF Generation** - Export to PDF using html2pdf.js (no server needed)
- **Dark/Light Mode** - Comfortable editing in any lighting condition
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Keyboard Shortcuts** - `Ctrl/Cmd + E` to export, `Ctrl/Cmd + Enter` to refresh

## Templates

### Minimal
Clean, distraction-free design perfect for documentation and notes.

### Academic
Serif typography with traditional formatting - ideal for papers and research.

### Modern (Default)
Contemporary design with gradient accents and polished styling - great for reports and proposals.

## Quick Start

1. Open `index.html` in any modern browser
2. Start typing Markdown or drag a file into the editor
3. Select your preferred template and page settings
4. Click "Export PDF" to download

## Deployment

### GitHub Pages (Free)

1. Fork this repository or create a new one
2. Upload the `index.html` file
3. Go to Settings → Pages
4. Select "Deploy from a branch" → "main"
5. Your site will be live at `https://yourusername.github.io/md-to-pdf`

### Netlify (Free)

1. Go to [netlify.com](https://netlify.com) and sign up
2. Drag and drop the `md-to-pdf` folder onto your sites dashboard
3. Your site will be live instantly with a custom URL

**Or using Netlify CLI:**
```bash
npm install -g netlify-cli
netlify deploy --prod --dir=md-to-pdf
```

### Vercel (Free)

1. Install Vercel CLI: `npm i -g vercel`
2. Navigate to the project folder: `cd md-to-pdf`
3. Deploy: `vercel --prod`

### Cloudflare Pages (Free)

1. Go to [dash.cloudflare.com](https://dash.cloudflare.com)
2. Create a new Pages project
3. Upload the `index.html` file
4. Your site will be deployed globally

## File Structure

```
md-to-pdf/
├── index.html          # Complete application (single file)
└── README.md          # This file
```

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + E` | Export PDF |
| `Ctrl/Cmd + Enter` | Refresh preview |

## Privacy

All processing happens in your browser. Your Markdown content is never sent to any server.

## Technologies Used

- [Marked](https://marked.js.org/) - Markdown parser
- [html2pdf.js](https://ekoopmans.github.io/html2pdf.js/) - PDF generation
- [Lucide](https://lucide.dev/) - Icons
- [Inter](https://rsms.me/inter/) & [Merriweather](https://fonts.google.com/specimen/Merriweather) - Typography

## License

MIT License - feel free to use for personal or commercial projects.

## Support

If you find this tool useful, consider:
- Starring the repository
- Sharing with others
- Contributing improvements

---

Made with care for the Markdown community.
