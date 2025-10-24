# SAP MDG Material Master Data Form - Deployment Guide

## 🚀 Option A: Deploy to GitHub Pages (Recommended)

### Prerequisites
- GitHub account (free)
- Git installed on your computer

### Step-by-Step Instructions

#### 1. Create GitHub Repository
1. Go to https://github.com
2. Click the **"+"** button (top right) → **"New repository"**
3. Repository settings:
   - **Repository name**: `mdg-material-form` (or any name you prefer)
   - **Description**: `SAP MDG Material Master Data Creation Form`
   - **Public** or **Private** (your choice)
   - ✅ Check **"Add a README file"**
   - Click **"Create repository"**

#### 2. Upload Files to Repository

**Method A: Via Web Interface (Easiest)**
1. In your repository, click **"Add file"** → **"Upload files"**
2. Drag and drop the `index.html` file
3. Scroll down, add commit message: `Initial commit - MDG Form`
4. Click **"Commit changes"**

**Method B: Via Git Command Line**
```bash
# Clone your repository
git clone https://github.com/YOUR-USERNAME/mdg-material-form.git
cd mdg-material-form

# Copy index.html to this folder
# Then commit and push
git add index.html
git commit -m "Add MDG Material Form"
git push origin main
```

#### 3. Enable GitHub Pages
1. In your repository, go to **Settings** (top menu)
2. Scroll down to **"Pages"** section (left sidebar)
3. Under **"Source"**, select:
   - Branch: **main** (or master)
   - Folder: **/ (root)**
4. Click **"Save"**
5. Wait 2-3 minutes for deployment

#### 4. Access Your Live Application
Your application will be available at:
```
https://YOUR-USERNAME.github.io/mdg-material-form/
```

Example: `https://johnsmith.github.io/mdg-material-form/`

### ✅ Verification
1. Open the GitHub Pages URL
2. You should see the SAP MDG Material Master Data Form
3. Test by selecting a class (e.g., ZSI1_ICT_CABLE)
4. Fill in characteristics and submit

### 🔄 Updates
To update the application:
1. Edit `index.html` in your repository
2. Commit the changes
3. GitHub Pages will automatically rebuild (2-3 minutes)

---

## 📁 Files Included
- `index.html` - Complete application with embedded data (1.86 MB)
- `README.md` - This deployment guide

## 🎯 Features
- 256 Material Classes (TABLE 1 only)
- 2,304 Characteristics with validation
- 1,020 Characteristics with predefined values
- Smart input handling (dropdown/text/custom)
- Real-time material description preview
- SAP Fiori design theme
- Fully offline-capable (embedded data)

## 🆘 Troubleshooting

### Issue: GitHub Pages not showing
- **Solution**: Wait 5 minutes, clear browser cache, try incognito mode

### Issue: Application shows blank page
- **Solution**: Check browser console (F12) for errors, ensure index.html was uploaded correctly

### Issue: Data not loading
- **Solution**: The data is embedded, so no external API needed. Check if index.html file is complete.

## 📞 Support
For issues or questions, refer to the GitHub repository Issues tab.

---

**Last Updated**: October 24, 2025
