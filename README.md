# Merry Band

Static website for Merry Band, a small musician booking agency specialising in weddings and private events across the UK.

## Pages

| File | Description |
|------|-------------|
| `index.html` | Home page — agency overview and call to action |
| `musicians.html` | Roster of available musicians and ensembles |
| `services.html` | Services offered and sample repertoire |
| `media.html` | Audio and video samples |
| `contact.html` | Booking enquiry form |

## Structure

```
merry_band_site/
├── index.html
├── musicians.html
├── services.html
├── media.html
├── contact.html
├── css/
│   └── style.css
└── README.md
```

## Development

Pure HTML and CSS — no build step, no JavaScript, no frameworks. Open any `.html` file directly in a browser or serve with any static file server:

```bash
npx serve .
# or
python3 -m http.server
```

## Notes

- Image placeholders are marked with HTML comments throughout
- The contact form `action` attribute is a placeholder (`#`) pending backend integration
- All pages share a single stylesheet at `css/style.css`
