# GitHub Pages Deployment Guide

## Quick Setup (No Git Required)

### Method 1: Direct Upload
1. Go to [GitHub.com](https://github.com) and sign in
2. Create a new repository named `Dalitso-Zulu.github.io`
3. Click "Add file" → "Upload files"
4. Drag and drop all your portfolio files:
   - `index.html`
   - `about.html`
   - `projects.html`
   - `contact.html`
   - `assets/` folder
   - `images/` folder
   - `README.md`
5. Click "Commit changes"

### Method 2: Using GitHub Desktop
1. Download [GitHub Desktop](https://desktop.github.com/)
2. Sign in with your GitHub account
3. Clone your repository
4. Copy all files to the repository folder
5. Commit and push changes

## Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll to **Pages** section
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/(root)** folder
6. Click **Save**

## Your Site URL
Your portfolio will be live at: `https://dalitso-zulu.github.io`

## Troubleshooting
- Make sure repository is **Public**
- Wait 5-10 minutes for changes to deploy
- Check the **Actions** tab for deployment status
- Ensure `index.html` is in the root folder

## Contact Form Setup
After deployment, set up your contact form:
1. Go to [Formspree.io](https://formspree.io)
2. Sign up with your email: `zuludalitso40@gmail.com`
3. Create a new form
4. Replace the form action in `contact.html` with your Formspree endpoint 