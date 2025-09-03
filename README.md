# DeliveryLogger Legal & Privacy Pages

This repository contains the privacy policy and data deletion pages for the DeliveryLogger mobile application.

## Pages

- **Home Page**: `index.html` - Landing page with links to all legal documents
- **Privacy Policy**: `privacy.html` - Comprehensive privacy policy
- **Terms of Service**: `terms.html` - Terms and conditions for using the app
- **Data Deletion**: `delete-account.html` - Instructions for account deletion

## Setup Instructions

### 1. Create GitHub Repository

1. Go to [GitHub.com](https://github.com)
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name it: `deliverylogger-policies`
5. Make it **Public**
6. Don't initialize with README (we already have files)
7. Click "Create repository"

### 2. Push Code to GitHub

After creating the repository, run these commands in Terminal:

```bash
cd /Users/danny/Desktop/deliverylogger-policies
git remote add origin https://github.com/YOUR-USERNAME/deliverylogger-policies.git
git branch -M main
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username.

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" section (left sidebar)
4. Under "Source", select:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
5. Click "Save"
6. Wait 2-5 minutes for deployment

### 4. Your URLs

Once GitHub Pages is enabled, your URLs will be:

- **Home**: `https://YOUR-USERNAME.github.io/deliverylogger-policies/`
- **Privacy Policy**: `https://YOUR-USERNAME.github.io/deliverylogger-policies/privacy.html`
- **Terms of Service**: `https://YOUR-USERNAME.github.io/deliverylogger-policies/terms.html`
- **Data Deletion**: `https://YOUR-USERNAME.github.io/deliverylogger-policies/delete-account.html`

## Using These URLs

### In Facebook Developer Console:
1. Go to your Facebook app settings
2. Settings → Basic
3. Add:
   - Privacy Policy URL: Your privacy.html URL
   - User Data Deletion URL: Your delete-account.html URL

### In Azure External ID:
1. Go to your app registration
2. Branding & properties
3. Add the privacy policy URL

### In Apple App Store Connect (Future):
Add the privacy policy URL when submitting your app.

## Customization

Feel free to modify the content to match your specific needs:
- Update email addresses
- Add your company information
- Modify the styling in `styles.css`
- Add additional legal pages as needed

## Support

For questions about these pages, contact: support@deliverylogger.com