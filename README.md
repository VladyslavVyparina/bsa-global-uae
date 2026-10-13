# BSA Global UAE

A marketing site for BSA Global: cargo moving through Dubai. The page is plain HTML, CSS, and JavaScript, with a Webflow paste version of the same layout.

## Problem

The company needed a public page that explained the Dubai cargo route, the services, and how to start a shipment, in a layout that could also be dropped into Webflow without rebuilding it by hand.

## What was built

- `index.html`, `styles.css`, and `script.js` are the standalone site.
- `webflow-paste.html` is the same layout prepared for Webflow’s HTML embed.
- `webflow.json` is the Webflow project descriptor used while assembling that paste.
- `images/` holds the photography and icons used on the page. Large source files that were not referenced by the layout were left out of this public copy.

## How it works

The standalone page is static. Sections follow the offer from the route through the services to the contact block. The Webflow paste file is the version a designer imports when the same blocks need to live in the Webflow project. `script.js` covers the small interactions on the page (menu, anchors). There is no backend in this repository.

## Stack

HTML, CSS, JavaScript, Webflow.

## Run locally

```bash
python3 -m http.server 8080
```

Open `http://127.0.0.1:8080`.
