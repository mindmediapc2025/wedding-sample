# Dhanush & Merlin Priyadharshini — Wedding Invitation Website

## Included
- Responsive bilingual (English + Tamil) invitation
- Countdown to 11 November 2026 at 10:00 AM India Standard Time
- Venue details and Google Maps link
- WhatsApp sharing
- Background music controls
- Photo placeholders to replace with your couple photos

## Preview locally
Open `index.html` in a modern browser.

## Add couple photos
Replace the placeholder `<div class="photo-placeholder">...</div>` blocks in `index.html` with image tags, for example:
`<img src="couple-main.jpg" alt="Dhanush and Merlin" style="width:100%;height:100%;object-fit:cover">`
Put the image file in the same folder and use the same filename. Repeat for the three gallery placeholders.

## Add music
Place a music file you own or have permission to use in this folder and name it `music.mp3`. The Play music buttons will use it.

## Check the map
The supplied Google Maps URL appears to be a long tracking/search URL. The website starts with a venue-name search link. Please open it and confirm the exact hall pin, then replace the `href` on the `mapLink` element with the confirmed share URL.

## Publish free with GitHub Pages
1. Sign in to GitHub and create a new public repository.
2. Upload `index.html` and any photo/music files.
3. In repository Settings → Pages, select deploy from the main branch and root folder.
4. Save and wait for GitHub to provide the website URL.
5. Test the link on a phone before sharing it with guests.

Note: WhatsApp sharing opens a pre-filled message; guests can send it after reviewing. Music does not autoplay because modern browsers require a tap.
