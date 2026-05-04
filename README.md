# 🌸 Marathi Wedding Invitation Website

A beautiful, fully customizable Marathi wedding invitation website — ready to deploy on GitHub Pages!

---

## ✨ Features

| Feature | Details |
|---|---|
| 🎵 Background Music | Toggle button — add your own MP3 URL |
| 🌸 Floating Petals | Animated rose petals falling across the page |
| ⏱️ Live Countdown | Real-time countdown to the wedding day |
| 📍 Google Maps | Embedded map with directions button |
| 📋 RSVP Form | Guests can RSVP with their name, phone, event preference |
| ✏️ Live Customizer | Side panel — change all names, dates, venues instantly |
| 📜 Events Timeline | All wedding ceremonies listed in a beautiful timeline |
| 🖼️ Gallery Section | Placeholder grid — add real photos easily |
| 📱 Responsive | Works on mobile, tablet, and desktop |
| 🔡 Marathi + English | Devanagari script throughout |

---

## 🚀 Deploy to GitHub Pages (Free!)

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **"New Repository"**
3. Name it: `my-wedding` (or anything you like)
4. Set it to **Public**
5. Click **"Create Repository"**

### Step 2 — Upload Your File
1. Click **"uploading an existing file"** link on the new repo page
2. Drag and drop `index.html`
3. Click **"Commit changes"**

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **"Source"**, select `main` branch, `/ (root)` folder
3. Click **Save**
4. Wait ~60 seconds, then visit:
   ```
   https://YOUR_USERNAME.github.io/my-wedding/
   ```

🎉 **Your wedding invitation is now live!**

---

## ✏️ How to Customize

### Using the Live Customizer Panel
- Click the **⚙️ Edit** tab on the left side of the website
- Fill in all the fields and click **"Apply Changes"**

### Or Edit the HTML Directly

Open `index.html` and find these sections:

**Names & Date** — in the `<input>` fields near the top of `<body>`:
```html
<input id="c-groom" value="आदित्य शर्मा"/>
<input id="c-bride" value="प्रिया पाटील"/>
<input id="c-date" type="date" value="2025-12-07"/>
```

**Venue & Map** — update the Google Maps embed URL:
```html
<input id="c-map" value="https://maps.google.com/maps?q=YOUR+VENUE&output=embed"/>
```

To get your venue's embed URL:
1. Go to [maps.google.com](https://maps.google.com)
2. Search your venue
3. Click **Share** → **Embed a map** → Copy the `src="..."` URL

**Music** — add your own MP3:
```html
<audio id="bg-music" loop>
  <source src="YOUR_MUSIC_URL.mp3" type="audio/mpeg"/>
</audio>
```
Or paste a public MP3 URL in the customizer panel.

**Add Real Photos** — replace gallery items:
```html
<!-- Replace emoji gallery items like this: -->
<div class="gallery-item">
  <img src="your-photo.jpg" style="width:100%;height:100%;object-fit:cover;"/>
  <div class="gallery-label">हळदी</div>
</div>
```

---

## 📁 File Structure

```
my-wedding/
└── index.html      ← Everything is in this single file!
```

No build process. No npm. No dependencies. Just one HTML file.

---

## 🎨 Color Customization

Edit CSS variables at the top of `<style>`:
```css
:root {
  --maroon: #7B1C2E;
  --gold:   #C9982A;
  --cream:  #FDF6EC;
  /* etc... */
}
```

---

## 📞 Share Your Invitation

Once deployed, share this link with your guests:
```
https://YOUR_USERNAME.github.io/REPO_NAME/
```

You can also create a free short URL at [bit.ly](https://bit.ly) or [tinyurl.com](https://tinyurl.com).

---

*Made with ❤️ for Marathi weddings • शुभमंगल सावधान 🌸*
