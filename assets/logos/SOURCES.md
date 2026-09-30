# Logos

| File | Institute |
| --- | --- |
| `iisc.jpg` | Indian Institute of Science — host |
| `cps.png` | Robert Bosch Centre for Cyber-Physical Systems, IISc — host |
| `iitb.svg` | IIT Bombay |
| `iitd.webp` | IIT Delhi |
| `iitm.svg` | IIT Madras |
| `iitk.svg` | IIT Kanpur |
| `iitkgp.webp` | IIT Kharagpur |
| `artpark.png` | ARTPARK, AI &amp; Robotics Technology Park, I-Hub @ IISc — Diamond sponsor |
| `abcmc.png` | Axis Bank Centre for Mathematics &amp; Computing, IISc — Platinum sponsor |

All files supplied by the organisers. To add another participating institute, drop its logo
here and copy one `.logo-card` block in the `#institutes` section of `index.html`.

To add a sponsor, drop its logo here and copy one `.sponsor` block in the `#sponsors` section.
Tiers run `.tier.diamond` (one full-width card, 86px logo), `.tier.platinum` (two columns,
68px logo), then a plain `.tier` grid for lower tiers; add a `.subhead` above each tier.

Logos must be web formats: PNG, JPEG, WebP or SVG. A HEIC file from an iPhone or a Mac
screenshot will not render in Chrome or Firefox even if renamed `.png`; convert it first with
`sips -s format png in.heic --out out.png`.
