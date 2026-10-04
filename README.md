# Nail Trace 💅

Nail Trace is a mobile-first web app designed to help nail artists size, position, simplify, and trace nail art directly from an iPhone screen.

The app allows artists to upload their own reference images or choose from a built-in design library, size artwork to real-world nail dimensions, simplify images into bold outlines, selectively restore colors, and lock the artwork in place for tracing.

## Live App

[Nail Trace](https://k3ilita.github.io/-nail-trace/)

For the best experience, open Nail Trace on an iPhone in Safari and add it to the Home Screen.

## Features

### Nail Sizing
- Enter nail width and length in millimeters
- Screen calibration using a standard credit/debit card
- Oval/almond, square, and coffin nail guides
- Fit artwork directly to the nail guide
- Nail dimensions remain visible while positioning artwork

### Image Tracing
- Upload images from your device
- Drag, pinch, zoom, and rotate artwork
- Crop images
- Rotate 90°
- Mirror horizontally
- Flip vertically
- Center or reset artwork
- Lock the canvas to prevent accidental movement while tracing

### Outline Mode
- Convert artwork into bold black outlines
- Adjust outline strength
- Remove colors completely
- Detect major colors in an image
- Turn individual colors back on for step-by-step tracing

This allows artists to trace the outline first and then work through individual color regions.

### Built-In Design Library
Designs are organized by categories and subcategories such as:

- Holidays
  - Halloween
  - Christmas
  - Valentine's Day
  - Easter
  - Thanksgiving
- Food
  - Fruits
  - Desserts
  - Drinks
  - Snacks
- Animals
  - Farm
  - Ocean
  - Pets
  - Insects
  - Wildlife
- Nature
- Space
- Accessories
- Symbols
- Extras

Artists can also upload their own designs instead of using the built-in library.

### Lettering

Nail Trace includes a mobile-first lettering tool for creating traceable text.

Current fonts include:

- UnifrakturMaguntia
- UnifrakturCook
- Raleway Dots
- League Script
- Meddon
- Eagle Lake
- Homemade Apple
- Borel
- Betania Patmos
- Moo Lah Lah

The font browser displays the artist's own text in each font so fonts can be selected visually.

Lettering can then be:

- resized
- rotated
- mirrored
- flipped
- cropped
- converted to outlines
- fitted to a nail
- locked for tracing

A letter-thickness control is also available to make very fine fonts easier to trace at nail scale.

## Mobile-First Design

Nail Trace is designed primarily for iPhone use.

The mobile interface includes:

- Design tab
- Nail tab
- View tab
- Edit tab
- Text tab
- Full-screen design browser
- Full-screen crop interface
- Large touch targets
- Persistent Fit to Nail and Lock controls
- Touch-safe tracing mode

## Add Nail Trace to Your iPhone

1. Open the live app in Safari.
2. Tap the Share button.
3. Select **Add to Home Screen**.
4. Name it **Nail Trace**.
5. Tap **Add**.

Nail Trace will then launch from the Home Screen like an app.

## Project Structure

```text
-nail-trace/
├── index.html
├── designs.json
├── README.md
└── images/
    ├── holidays/
    ├── food/
    ├── animals/
    ├── nature/
    ├── space/
    ├── accessories/
    ├── symbols/
    └── extras/
