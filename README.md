# Wallet CV

An interactive 3D wallet that works as a CV. Open the wallet, pull out the Designer Licence or any of the project cards, turn them over and read about each one.

Part of Harrison Greener's Digital Media Project.

**[View the website →](https://harrisongreener.co.uk/)**

## Run it

It is a single static page. Serve the folder with any static server, for example:

```
npx serve .
```

Then open the address it prints. Opening `index.html` straight from disk will not load the card images, because browsers block local file loads.

## Change the cards

- Artwork lives in `assets/cards/`, as `<id>-front.jpg` and `<id>-back.jpg`.
- The list of items, their text and which slot they sit in is the `ITEMS` array near the top of the script in `index.html`.

Built with [three.js](https://threejs.org/) 0.160, loaded from jsDelivr.
