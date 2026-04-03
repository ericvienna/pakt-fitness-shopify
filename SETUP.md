# PAKT Fitness — Shopify Theme Setup Guide

## 1. Upload Theme

1. Go to **Online Store → Themes → Add theme → Upload zip**
2. Upload `pakt-fitness-theme.zip`
3. Click **Publish** to make it live

## 2. Upload Fonts

Upload these font files to **Settings → Files** (or include in `assets/`):
- `Countach-Light.otf`
- `Countach-Regular.otf`
- `Countach-Bold.otf`
- `Supply-Light.otf`
- `Supply-Regular.otf`
- `Supply-Medium.otf`
- `Supply-Bold.otf`

Source: `/Volumes/WD_BLACK/Projects/Active/pakt-fitness/public/fonts/`

## 3. Upload Logo

Upload `pakt-logo.svg` to **Settings → Files** (or include in `assets/`).

Source: `/Volumes/WD_BLACK/Projects/Active/pakt-fitness/public/images/pakt-logo.svg`

## 4. Create Collections

Create one collection with exact handle:
- **merch** — all merch products

## 5. Add Products

### Product 1: "First to Sweat" Oversized Tee
- **Price**: $65.00
- **Type**: Tee
- **Tags**: merch, tee, founding
- **Variants (Size)**: S, M, L, XL, XXL
- **Description**: Acid-wash oversized tee. Tone-on-tone "FIRST TO SWEAT" front print. Small PAKT mark on back right shoulder. Sand colorway. 100% heavyweight cotton. Boxy cut.
- **Images**: `222.jpg` (front + back flat lay)

### Product 2: "Last to Quit" Oversized Tee
- **Price**: $65.00
- **Type**: Tee
- **Tags**: merch, tee, founding
- **Variants (Size)**: S, M, L, XL, XXL
- **Description**: Acid-wash oversized tee. Tone-on-tone "LAST TO QUIT" front print. Small PAKT mark on back right shoulder. Black wash colorway. 100% heavyweight cotton. Boxy cut.
- **Images**: `FB/SQUARE.png`

### Product 3: "Movement is Connection" Oversized Tee
- **Price**: $65.00
- **Type**: Tee
- **Tags**: merch, tee, founding
- **Variants (Size)**: S, M, L, XL, XXL
- **Description**: Acid-wash oversized tee. "PAKT" front print in muted gold. "MOVEMENT IS CONNECTION" back print. Dark charcoal colorway. 100% heavyweight cotton. Boxy cut.
- **Images**: `FB/SQUARE-1.png`

### Product 4: PAKT Tote
- **Price**: $40.00
- **Type**: Accessories
- **Tags**: merch, accessories, founding
- **Variants**: One size
- **Description**: Natural canvas tote with embossed PAKT wordmark. Reinforced handles. Heavyweight 12oz canvas. Built to carry.
- **Images**: `FB/SQUARE-2.png`

### Product 5: PAKT. Dad Cap
- **Price**: $45.00
- **Type**: Accessories
- **Tags**: merch, accessories, founding
- **Variants**: One size
- **Description**: Unstructured dad cap. "PAKT." embroidered front in muted gold. "LAST TO QUIT" embroidered back in tonal black. Adjustable strap. Washed black.
- **Images**: `FB/SQUARE-3.png`

## 6. Configure Hero Section

In **Theme Editor → Homepage → Hero**:
- Eyebrow: `Founding Member Merch`
- Heading: `First to Sweat.`
- Subtitle: `Limited-run pieces for the crew who believed first. Once they're gone, they're gone.`
- Button: `Shop the Drop` → `/collections/merch`

## 7. Configure Featured Collection

In **Theme Editor → Homepage → Featured Collection**:
- Collection: `merch`
- Heading: `The Drop`
- Label: `Limited Edition`
- Products to show: 6

## 8. Domain

Point your merch subdomain (e.g., `shop.paktfitness.com`) to Shopify:
**Settings → Domains → Connect existing domain**

---

Theme built by Super Always · April 2026
