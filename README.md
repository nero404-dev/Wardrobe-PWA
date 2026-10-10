# Wardrobe — Personal Style & Packing

A lightweight vanilla HTML/CSS/JavaScript progressive web app.

## Run locally

Open Terminal in this folder and run:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`. Use localhost or HTTPS; opening `index.html` directly as a `file://` URL does not enable service workers or PWA installation.

## Included
- Add, edit, search, sort, and categorize wardrobe items
- Collections such as Everyday, Summer, Winter, and Favorites
- Save outfits from existing wardrobe pieces
- Create trips and track checklist completion
- Reusable packing essentials and custom items
- LocalStorage persistence
- PWA manifest and service-worker caching
- Responsive dark interface
- Upload clothing photos (resized and stored in IndexedDB) or use image URLs; photos appear in wardrobe cards, saved outfit previews, and trip checklists

## Notes
Wardrobe, outfit, and trip details are stored in localStorage. Uploaded clothing photos are resized and stored separately in IndexedDB; linked image URLs load from their original host. Data does not sync between devices. Clearing this site’s browser data removes locally stored uploads, so keep your original photos backed up.
