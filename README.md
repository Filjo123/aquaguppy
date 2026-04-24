# 🐟 AquaGuppy — Guppy Fish Store

A GitHub Pages-compatible guppy fish selling website with a local admin panel.

## 📁 Project Structure

```
guppy-shop/
├── index.html        ← Main website (GitHub Pages)
├── admin.html        ← Local admin panel (open in browser)
├── products.json     ← Product data
└── images/           ← Fish images folder
```

## 🚀 How to Use

### Adding Products (Admin Panel)
1. Open `admin.html` in your browser (double-click)
2. Fill in fish name, price, description, stock status, and image
3. Click **Add Product**
4. Click **💾 Download products.json**
5. Replace `products.json` in your project folder
6. Move downloaded images to the `images/` folder

### Deploy to GitHub Pages
```bash
git add .
git commit -m "update products"
git push origin main
```

Then enable GitHub Pages:
- Go to repo Settings → Pages → Source: main branch → Save

Your website will be live at: `https://your-username.github.io/repo-name/`

## ⚠️ Notes
- Admin panel data is saved in browser localStorage
- Always download and replace products.json after making changes
- Images must be in the `images/` folder in your repo
