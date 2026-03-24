# 🐾 Chesper the Doodle — chesperdoodle.com

Chesper's personal website! A cute, animated page for the world's goodest Goldendoodle.

## How to Deploy on GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in to Chesper's account
2. Click the **+** button (top right) → **New repository**
3. Name it: `chesperdoodle.com` (or any name you like)
4. Set it to **Public**
5. Click **Create repository**

### Step 2: Upload These Files
1. On the new repo page, click **"uploading an existing file"**
2. Drag and drop ALL the files from this folder:
   - `index.html`
   - `CNAME`
   - `images/` folder (with all 10 photos inside)
3. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to your repo → **Settings** tab
2. In the left sidebar, click **Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**
6. Wait 1-2 minutes — your site will be live at `https://yourusername.github.io/chesperdoodle.com`

### Step 4: Connect Your Custom Domain (chesperdoodle.com)
1. Go to your domain registrar (wherever you bought chesperdoodle.com)
2. Update the **DNS settings** — add these records:

   | Type  | Name | Value                    |
   |-------|------|--------------------------|
   | A     | @    | 185.199.108.153          |
   | A     | @    | 185.199.109.153          |
   | A     | @    | 185.199.110.153          |
   | A     | @    | 185.199.111.153          |
   | CNAME | www  | yourusername.github.io   |

   *(Replace `yourusername` with Chesper's GitHub username)*

3. Back in GitHub → **Settings** → **Pages**:
   - Under "Custom domain", type `chesperdoodle.com`
   - Click **Save**
   - Check **Enforce HTTPS** (may take a few minutes to appear)

4. DNS can take up to 24-48 hours to fully propagate, but usually works within an hour.

## File Structure

```
chesperdoodle.com/
├── index.html          ← The main website
├── CNAME               ← Tells GitHub Pages about your custom domain
├── README.md           ← This file
└── images/
    ├── hero.jpg        ← Main profile photo (avatar)
    ├── walk.jpg         ← Outdoor walk photo
    ├── window.jpg       ← Window chillin photo
    ├── sleepy.jpg       ← Sleepy in bed photo
    ├── store.jpg        ← Pet store photo
    ├── toy.jpg          ← Close-up with toy
    ├── puppy.jpg        ← Puppy elevator photo
    ├── nose.jpg         ← Nose close-up
    ├── cuddles.jpg      ← Cuddle time photo
    └── park.jpg         ← Dog park photo
```

## Adding or Swapping Photos
To change a photo, just replace the matching file in the `images/` folder with a new image using the same filename. GitHub Pages will update automatically within a few minutes.

## 🐶 Woof!
