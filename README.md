# real-state-demo-website-
A  responsive Real Estate Management Website built to simplify property listings and customer enquiries. Features include property search and filters, property details, image galleries, an owner dashboard, property management, enquiry tracking, and site visit scheduling. Developed as a user-friendly interface for both buyers and  owners.
# Sample Realty – Real Estate Website (Demo)

A responsive real estate website with a **Client side** and an **Owner panel**, built with plain HTML, CSS and JavaScript (no frameworks, no build step). Royal navy and gold theme.

> Demo project: all properties, names and contact details are sample data.

## Client side
- Property listings with price, location, BHK, bathrooms and area
- Search, city, type and budget filters, plus price sorting
- Save favourite properties (♥)
- Property details popup with "Book site visit"
- Home loan EMI calculator
- Enquiry form with validation and preferred visit date
- WhatsApp buttons on every property, plus a floating button

## Owner panel (hidden from visitors)
- There is no public login button. Open `yourwebsite/#manage` (or tap the footer text 5 times)
- Default password: `owner123` (change it in Website settings after first login)
- Dashboard stats (listings, sold, enquiries)
- Add, edit, delete properties and mark them sold or available
- Upload property photos (up to 5 per property, auto-resized) with a gallery on the client side
- Website settings: change company name, WhatsApp number, phone, address, homepage text and background photo, and hide the demo banner (no coding needed)
- View client enquiries, update status (New / Contacted / Closed) and reply on WhatsApp
- Changes appear instantly on the client side

## Run locally
Open `index.html` in a browser.

## Customize
Edit these lines in the `<script>` of `index.html`:
```js
var WHATSAPP = "919999999999";
var PHONE_DISPLAY = "+91 99999 99999";
```

## Note
The owner login is a front-end demo lock only; real security needs a backend.
Data and photos are stored in the browser (localStorage, about 5 MB), so there is no backend. For a real product, connect a database and proper authentication.

## Tech stack
HTML5, CSS3, Vanilla JavaScript
