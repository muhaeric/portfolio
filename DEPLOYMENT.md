# Vercel Deployment Instructions

This document provides instructions for deploying the portfolio website to Vercel.

## Prerequisites

1. A Vercel account (create one at [vercel.com](https://vercel.com) if you don't have one)
2. Git installed on your computer (optional, but recommended)

## Deployment Options

### Option 1: Direct Upload to Vercel

1. Go to [vercel.com](https://vercel.com) and log in to your account
2. Click on "New Project"
3. In the "Import Git Repository" section, click on "Upload"
4. Drag and drop the entire `portfolio_website` folder or click to select it
5. Once uploaded, Vercel will automatically detect it as a static website
6. Click "Deploy" and Vercel will build and deploy your website
7. Once deployed, Vercel will provide you with a URL to access your website

### Option 2: Using Git and Vercel CLI (Recommended for future updates)

1. Initialize a Git repository in your project folder:
   ```
   cd portfolio_website
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. Create a new repository on GitHub, GitLab, or Bitbucket

3. Connect your repository to Vercel:
   - Go to [vercel.com](https://vercel.com) and log in
   - Click "New Project"
   - Import your Git repository
   - Configure project settings if needed
   - Click "Deploy"

4. For future updates, simply push changes to your Git repository and Vercel will automatically redeploy your website

## Project Structure

The portfolio website has the following structure:

```
portfolio_website/
├── assets/         # Additional assets
├── css/            # CSS stylesheets
│   └── style.css   # Main stylesheet
├── images/         # Image files
├── js/             # JavaScript files
│   └── main.js     # Main JavaScript file
└── index.html      # Main HTML file
```

## Custom Domain (Optional)

If you want to use a custom domain for your portfolio website:

1. Go to your project on Vercel dashboard
2. Click on "Settings" > "Domains"
3. Add your custom domain and follow the instructions to configure DNS settings

## Troubleshooting

If you encounter any issues during deployment:

1. Check that all file paths in your HTML, CSS, and JavaScript files are correct
2. Ensure all assets (images, fonts, etc.) are properly included in the project
3. Review Vercel's deployment logs for any errors
4. Consult Vercel's documentation at [vercel.com/docs](https://vercel.com/docs)
