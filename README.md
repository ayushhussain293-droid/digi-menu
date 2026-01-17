# Digital Menu - Cloud-Powered QR Menu 🍽️

A beautiful, responsive digital menu system with admin panel for restaurants, cafes, and shops.

## Features

- 📱 **Customer View**: Browse products, filter by category, order via WhatsApp
- 🔐 **Admin Panel**: Manage products, toggle visibility, update shop branding
- ☁️ **Cloud Storage**: Powered by Supabase (database + image storage)
- 💰 **INR Currency**: Prices displayed in Indian Rupees
- 🎨 **Modern UI**: Clean, mobile-first design

## Live Demo

🌐 **[View Live Site](https://YOUR-USERNAME.github.io/digi-menu)**

## Quick Start

### For Customers
1. Scan QR code or visit the link
2. Browse menu by category
3. Click "Order on WhatsApp" to place order

### For Shop Owners (Admin)
1. Click the 🔐 lock icon (bottom-right)
2. Enter password: `1234`
3. Manage your menu and settings

## Deployment

This site is hosted on **GitHub Pages** and uses **Supabase** for cloud storage.

### Initial Setup (Already Done)
- ✅ Supabase project created
- ✅ Database tables configured
- ✅ Image storage enabled
- ✅ GitHub Pages deployed

## Technology Stack

- **Frontend**: Vanilla HTML, CSS, JavaScript
- **Database**: Supabase (PostgreSQL)
- **Storage**: Supabase Storage
- **Hosting**: GitHub Pages
- **CDN**: Supabase JS Client (v2)

## Security

- Password-protected admin panel
- Row Level Security (RLS) policies on Supabase
- Public read access for customer view
- Secure image uploads

## Customization

To change the admin password, edit line 1090 in `index.html`:
```javascript
const ADMIN_PASSWORD = '1234'; // Change this
```

## Support

For issues or questions, create an issue in this repository.

---

Made with ❤️ for local businesses
