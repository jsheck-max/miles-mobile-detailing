# Miles Mobile Detailing — Website

Professional mobile car detailing website for Bay City, MI and surrounding areas.

## Pages
- **Home** (`index.html`) — Hero, services, gallery preview, why us, CTA
- **Gallery** (`gallery.html`) — Filterable photo gallery
- **Booking** (`booking.html`) — Multi-step booking form

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `milesmobiledetailing`)
2. Push this code to the repo
3. Go to **Settings → Pages → Source** and select `main` branch
4. Your site will be live at `https://yourusername.github.io/milesmobiledetailing/`

## Form Submissions

The booking form is set up for [Formspree](https://formspree.io) (free tier = 50 submissions/month).

To activate:
1. Sign up at formspree.io
2. Create a new form
3. Replace `YOUR_FORM_ID` in `booking.html` with your Formspree form ID

Without Formspree, the form shows a confirmation alert with the booking details.

## Customization

- **Phone number**: Search and replace `(989) 555-1234` and `+19895551234`
- **Email**: Replace `info@milesmobiledetailing.com`
- **Images**: Replace Unsplash URLs with your own photos
- **Prices**: Edit service cards in `index.html` and booking form in `booking.html`
- **Colors**: Edit CSS variables in `css/style.css` under `:root`

## Tech

Static HTML/CSS/JS — no build tools, no frameworks, no dependencies. Just upload and go.
