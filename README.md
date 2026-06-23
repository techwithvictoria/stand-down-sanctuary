# Stand Down Sanctuary and Farm — Website

The official website for **Stand Down Sanctuary and Farm**, a veteran-founded 501(c)(3) in Yelm, Washington, offering veterans, first responders, and their families healing through animals, farm life, and peer connection.

🌐 **Live site:** https://standdownsanctuaryandfarm.com/

---

## What this is

A single-page website built with plain HTML and CSS — no frameworks, no build step, nothing to install. It loads fast and works on phones, tablets, and computers.

## Files

```
index.html      → the entire website (all text and styling lives here)
images/         → all photos and the logo
README.md       → this file
```

Keep `index.html` and the `images/` folder together. The page references the photos by their location inside `images/`, so they have to travel as a pair.

## How to make common edits

All text and layout is inside **`index.html`**. Open it in any plain-text editor (or edit it right on GitHub) and use **Find** to jump to what you need.

- **Change wording** — search for the text you want to replace and type over it. Section markers like `<!-- HERO -->`, `<!-- MISSION -->`, and `<!-- VISIT -->` help you find your place.
- **Add the donation link** — search for `DONATE` (two spots). Replace `href="#visit"` with your donation URL (PayPal, Givebutter, Zeffy, etc.). The Donate buttons currently scroll to the contact section until a link is added.
- **Update contact info** — search for the phone number, email, or `facebook.com` and edit in place.
- **Swap a photo** — drop a new image into the `images/` folder and either give it the same filename as the one you're replacing, or update the matching `src="images/..."` line in `index.html`.

## Photos

Photos are saved at web-friendly sizes so the site loads quickly. If you add new ones, resize large camera files first (long edge around 1300px is plenty) so pages don't load slowly.

## Hosting (GitHub Pages)

This site is hosted free with GitHub Pages:

1. Upload `index.html` and the `images/` folder to the repository root.
2. Go to **Settings → Pages**.
3. Source: **Deploy from a branch** → Branch: **main** → Folder: **/ (root)** → **Save**.
4. The live link appears at the top of the Pages settings after a minute or two.

To update the site later, upload the changed file(s) again (**Add file → Upload files**) and commit.

## Contact

- **Phone:** Susan Cliber · 253-304-1771
- **Email:** standdownsanctuaryandfarm@gmail.com
- **Facebook:** Stand Down Sanctuary and Farm
- **Location:** Yelm, Washington

---

_Stand Down Sanctuary and Farm is a registered 501(c)(3) nonprofit. Donations are tax-deductible._
