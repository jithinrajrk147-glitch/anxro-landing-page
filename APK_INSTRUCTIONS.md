# 📱 APK Upload Instructions

## How to Add Your Anxro APK File

Your landing page is configured to serve the APK file from `base.apk`. Follow these steps to upload your app:

### Method 1: GitHub Web Interface (Easiest)

1. **Go to your repository**: [anxro-landing-page](https://github.com/jithinrajrk147-glitch/anxro-landing-page)

2. **Click "Add file"** → **"Upload files"**

3. **Drag and drop** your APK file or click to browse

4. **Rename the file** to `base.apk` (important!)

5. **Commit changes**:
   - Add commit message: "Add Anxro APK file"
   - Click "Commit changes"

### Method 2: Git Command Line

```bash
# Clone the repository
git clone https://github.com/jithinrajrk147-glitch/anxro-landing-page.git
cd anxro-landing-page

# Copy your APK file and rename it
cp /path/to/your/anxro-app.apk base.apk

# Add, commit, and push
git add base.apk
git commit -m "Add Anxro APK file"
git push origin main
```

### Method 3: GitHub Desktop

1. Open GitHub Desktop
2. Clone the repository
3. Copy your APK file to the repository folder
4. Rename it to `base.apk`
5. Commit and push the changes

## ⚠️ Important Notes

- **File name must be exactly**: `base.apk` (lowercase)
- **Maximum file size**: GitHub allows files up to 100MB
- **For larger files**: Consider using [Git LFS](https://git-lfs.github.com/) or hosting the APK elsewhere

## 🔗 After Upload

Once uploaded, your APK will be available at:
```
https://jithinrajrk147-glitch.github.io/anxro-landing-page/base.apk
```

The download button on your landing page will automatically work!

## 📊 File Size Recommendations

- **Optimal**: Under 50MB for faster downloads
- **Maximum**: 100MB (GitHub limit)
- **For larger apps**: Consider:
  - Using Google Play Store
  - Hosting on Firebase Storage
  - Using a CDN service

## 🔒 Security

- The APK file is served over HTTPS
- Users will see a download prompt
- Android will verify the APK signature on installation

## ✅ Verification

After uploading, verify the download works:
1. Visit your landing page
2. Click the "Download APK" button
3. Confirm the file downloads correctly
4. Test installation on an Android device

---

**Need help?** Contact: jithinrajrk147@gmail.com