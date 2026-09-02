# GioHost WHMCS Product Details Style

Custom-styled product details / order pages built for **GioHost**, a web hosting company — designed to replace WHMCS's default plain product spec tables with clean, card-based UI showing plan limits at a glance (storage, bandwidth, vCPU, RAM, I/O, backups, SSL, etc.).

Built while working as a developer at a hosting company, for use inside WHMCS product configuration / description fields.

## ✨ Features

- Clean, modern card layout for hosting plan specs
- Responsive grid for performance specs (vCPU, RAM, I/O, EP/NP)
- Highlighted badges for Storage, Transfer, SSL, and Backups
- "30-Day Money Back" trust badge
- Pure HTML + inline CSS — drop-in ready for WHMCS product description fields, no build step needed

## 📁 Files

Each file is a standalone product tier style, ready to paste into the corresponding WHMCS product's description:

| File | Plan |
|---|---|
| `Eco-Standard.html` | Eco Standard |
| `Standard-Blog.html` | Standard – Blog |
| `Standard-Plus.html` | Standard Plus |
| `Turbo-Dev.html` | Turbo – Dev |
| `Turbo-E-Shop.html` | Turbo – E-Shop |
| `Turbo-Portal.html` | Turbo – Portal |
| `VIP-Bronze.html` | VIP Bronze |
| `VIP-Gold.html` | VIP Gold |
| `VIP-Silver.html` | VIP Silver |

## 🚀 Usage

1. Open any `.html` file in this repo
2. Copy the full HTML block
3. Paste it into the **Product Description** field of the matching WHMCS product (WHMCS admin → Products/Services → Edit Product → Description)
4. Save — the styled card will render on the order page instead of the default plain list

## 🛠️ Tech

- HTML5
- Inline CSS (no external stylesheet dependency — safe for WHMCS's sandboxed description editor)

## 👤 Author

Built by [shoabul](https://github.com/shoabul)
