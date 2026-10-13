# PsyHab — Vite + Tailwind CSS

The final PsyHab design migrated to Vite, Tailwind CSS 4 and vanilla JavaScript. Includes original logo, team portraits, photographs, FAQs, navigation and WhatsApp booking enquiries.

## Run
Requires Node.js 22.12+.

```sh
npm install
npm run dev
```

## Build and preview
```sh
npm run build
npm run preview
```

Upload the contents of `dist/` to a static hosting directory. This is a standalone frontend project, not an installable WordPress theme or Elementor template.

## Edit
- `index.html`: page sections and team profiles.
- `src/main.js`: services, FAQs, navigation and booking.
- `src/style.css`: Tailwind imports, brand tokens and original responsive styling.
- `public/`: supplied logo, portraits and other imagery.

Tailwind utilities are enabled and used in the markup. Original custom CSS is retained to preserve the design; Tailwind Preflight is intentionally omitted. Add utilities freely; existing higher-specificity brand selectors may override them.

Bookings send a WhatsApp enquiry; they do not confirm appointments or store submissions. Google Fonts require internet access. No WordPress or hosting credentials are included.
