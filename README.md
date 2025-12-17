# 🏰 The Quest Journal

A medieval-inspired blog built with GitHub Pages that works **forever** with zero maintenance.

## 🎯 Features

- ✅ **Works Forever** - No database pausing, no connection issues
- ✅ **Zero Maintenance** - No keep-alive scripts needed
- ✅ **Cross-Device Sync** - GitHub API = same posts everywhere
- ✅ **Professional** - Beautiful medieval design
- ✅ **Free Forever** - GitHub Pages + public repo = $0
- ✅ **Draft System** - Save without publishing
- ✅ **Mobile Responsive** - Looks great on all devices

## 🔒 Security

- Password authentication for admin access
- GitHub token for write operations
- Visitors can only read posts
- Token stored in session only

## 📁 File Structure
NewBlog/
├── index.html          # Complete blog application
├── data/
│   └── posts.json      # Blog posts storage
├── .github/
│   └── workflows/
│       └── deploy.yml  # Auto-deployment
├── README.md          # Project documentation
└── SETUP.md          # Setup instructions

## 🎨 Design

Medieval parchment aesthetic with:
- Aged paper textures
- Ornate decorative borders
- Classic serif typography (IM Fell English, Crimson Text)
- Warm sepia/brown/gold color palette
- Hidden admin interface (⚔ symbol)

## 📝 How It Works

**For Visitors:** Beautiful read-only blog experience
**For Admin:** Login with password + GitHub token to create/edit posts
**Storage:** Posts saved to `data/posts.json` via GitHub API
**Deployment:** Automatic via GitHub Actions on every push
