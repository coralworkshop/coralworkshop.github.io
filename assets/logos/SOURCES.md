# Logos

| File | Institute |
| --- | --- |
| `iisc.jpg` | Indian Institute of Science — host |
| `cps.png` | Robert Bosch Centre for Cyber-Physical Systems, IISc — host |
| `iitb.svg` | IIT Bombay |
| `iitd.webp` | IIT Delhi |
| `iitm.svg` | IIT Madras |
| `iitk.svg` | IIT Kanpur |
| `iitkgp.webp` | IIT Kharagpur (not currently shown) |
| `iitgn.svg` | IIT Gandhinagar: English Wikipedia file `Indian_Institute_of_Technology_Gandhinagar_Logo.svg` (iitgn.ac.in blocks automated access) |
| `iitmandi.jpg` | IIT Mandi: https://iitmandi.ac.in/images/logo_hires.jpg, from https://iitmandi.ac.in/institute/iitmandilogo (resized) |
| `iitjammu.png` | IIT Jammu: https://iitjammu.ac.in/images/iitjammulogo.png, from https://iitjammu.ac.in/institute-logo |
| `iitrpr.png` | IIT Ropar: official logo file from the former https://www.iitrpr.ac.in/logo-iit-ropar page (archived May 2025; resized), matches the live site header |
| `artpark.png` | ARTPARK, AI &amp; Robotics Technology Park, I-Hub @ IISc — Diamond sponsor |
| `abcmc.png` | Axis Bank Centre for Mathematics &amp; Computing, IISc — Platinum sponsor |
| `control_society_logo.png` | The Control Society: Platinum sponsor. Identical to https://controlsociety.org/wp-content/uploads/2021/03/control-society-logo1.png (the only size the site publishes, 130 x 98) |
| `tcsr.png` | TCS Research — Gold sponsor |

Files without a source above were supplied by the organisers. To add another participating institute, drop its logo
here and copy one `.logo-card` block in the `#institutes` section of `index.html`.

To add a sponsor, drop its logo here and copy one `.sponsor` block in the `#sponsors` section.
Tiers run `.tier.diamond` (one full-width card, 86px logo), `.tier.platinum` (two columns,
68px logo), then a plain `.tier` grid for lower tiers; add a `.subhead` above each tier.

Logos must be web formats: PNG, JPEG, WebP or SVG. A HEIC file from an iPhone or a Mac
screenshot will not render in Chrome or Firefox even if renamed `.png`; convert it first with
`sips -s format png in.heic --out out.png`.
