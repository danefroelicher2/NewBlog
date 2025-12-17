# 🏰 Quest Journal - Setup Instructions

Follow these steps to get your medieval blog live!

## ✅ Step 1: Configure index.html

You need to make TWO changes in `index.html`:

### Change 1: Your GitHub Repository (Line ~652)

Find this line:
```javascript
this.githubRepo = 'danefroelicher2/NewBlog';
```

This is already correct for you! ✅

### Change 2: Your Admin Password (Line ~657)

Find this line:
```javascript
this.adminPasswordHash = this.hashPassword('Pacers33!!!');
```

Change `'Pacers33!!!'` to YOUR password:
```javascript
this.adminPasswordHash = this.hashPassword('YourPasswordHere');
```

⚠️ **REMEMBER THIS PASSWORD** - you'll need it to login!

---

## ✅ Step 2: Create GitHub Personal Access Token

You need this ONE TIME to enable writing posts:

1. Go to: https://github.com/settings/tokens
2. Click: **"Generate new token"** → **"Generate new token (classic)"**
3. Fill out:
   - **Note:** `Quest Journal Admin`
   - **Expiration:** `90 days`
   - **Scopes:** ✓ Check the **`repo`** box
4. Click: **"Generate token"** (bottom of page)
5. **COPY THE TOKEN** - Save it somewhere safe!

---

## ✅ Step 3: Push to GitHub
```bash
# In your NewBlog directory
git add .
git commit -m "Setup Quest Journal"
git push origin main
```

---

## ✅ Step 4: Enable GitHub Pages

1. Go to: https://github.com/danefroelicher2/NewBlog
2. Click: **Settings** (top menu)
3. Click: **Pages** (left sidebar)
4. Under "Source":
   - Select: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
5. Click: **Save**

Wait 1-2 minutes for deployment.

Your blog will be live at: **https://danefroelicher2.github.io/NewBlog**

---

## ✅ Step 5: Login & Start Writing!

1. Visit: https://danefroelicher2.github.io/NewBlog
2. Scroll to footer, click the **⚔** symbol
3. Enter:
   - Password: (what you set in Step 1)
   - GitHub Token: (from Step 2)
4. Click "Enter"

You'll see "Scribe's Desk" panel appear!

---

## 🎉 You're Done!

Create your first post:
1. Click "Pen a New Tale"
2. Write your title and content
3. Click "Publish Tale"

Your blog is now live and bulletproof! 🏰
