# 3D Printing Pontianak – Price Calculator

A single-page website (one file: `index.html`). No build step, no dependencies.

## Deploy on Vercel
1. Put `index.html` at the root of a GitHub repository (not inside a folder).
2. In Vercel: Add New → Project → import the repository.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
4. Deploy.

## Where to edit (search for these in `index.html`)
- Rate per gram: `id="rgi" value="350"` (TPU uses 500: the `<option value="500"`)
- Rate per hour: `id="rhi" value="600"`
- Markup %: `id="pi" value="10"`
- Minimum price: `Math.max(up,5000)`
- Time estimate ratio: `HT*0.4` (2 days per 5 hours), minimum 3 days: `Math.max(3,`
- WhatsApp number: `6289693291142`
- Instagram: `instagram.com/3dprinting_pontianak`
