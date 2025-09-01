# Deployment Guide for TechSphere Solutions Letterhead

This guide will help you deploy the TechSphere Solutions letterhead website to GitHub Pages and obtain a shareable link for your professor to grade.

## Option 1: GitHub Pages Deployment

1. **Create a GitHub Repository**
   - Go to [GitHub](https://github.com) and sign in (or create an account if you don't have one)
   - Click the "+" icon in the top right corner and select "New repository"
   - Name your repository `it-services-letterhead`
   - Make it public
   - Click "Create repository"

2. **Upload Your Files**
   - Follow the instructions on the page to upload your files:
   ```
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/it-services-letterhead.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on "Settings"
   - Scroll down to "GitHub Pages" section
   - Under "Source", select "main" branch
   - Click "Save"
   - Wait a few minutes for your site to deploy

4. **Get Your Shareable Link**
   - Your site will be available at: `https://YOUR_USERNAME.github.io/it-services-letterhead/`
   - This is the link you can share with your professor

## Option 2: Quick Deployment with Netlify Drop

If you don't want to create a GitHub account, you can use Netlify Drop:

1. **Compress Your Files**
   - Create a ZIP file of all the files in the `it-services-letterhead` folder

2. **Upload to Netlify Drop**
   - Go to [Netlify Drop](https://app.netlify.com/drop)
   - Drag and drop your ZIP file onto the page
   - Wait for the upload and deployment to complete

3. **Get Your Shareable Link**
   - Netlify will provide a random URL like `https://random-name-123456.netlify.app`
   - This is the link you can share with your professor

## Submission Instructions

1. **Test Your Website**
   - Before submitting, make sure to visit your deployed website to ensure everything looks correct
   - Check that the letterhead displays properly
   - Verify that all required elements are present

2. **Submit to Your Professor**
   - Submit the URL of your deployed website
   - Include a brief note explaining that this is your Team Logo & Letterhead assignment
   - Mention that the website showcases your company name (TechSphere Solutions), logo, and catch phrase ("Your Business. Our Technology. One Solution.")

## Local Testing

To test the website locally before deployment:
- Simply open the `index.html` file in your web browser
- This will allow you to see how the website will look when deployed
