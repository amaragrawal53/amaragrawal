# GitHub Pages Deployment Commands

## After creating the repository on GitHub, run these commands:

```bash
# Navigate to your portfolio folder
cd "C:\Workspace\amar-agrawal-portfolio"

# Add GitHub remote (replace YOUR_USERNAME with your actual GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/amaragrawal.github.io.git

# Push to GitHub
git push -u origin main
```

## Next Steps After Push:

1. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click **Settings** tab
   - Scroll down to **Pages** section
   - Source: **Deploy from a branch**
   - Branch: **main** / **/(root)**
   - Click **Save**

2. **Wait for Deployment:**
   - GitHub will build your site (2-5 minutes)
   - Check the **Pages** section for your live URL

3. **Your Website Will Be Live At:**
   ```
   https://YOUR_USERNAME.github.io
   ```

## Troubleshooting:

### If push fails with authentication error:
```bash
# Configure Git credentials
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### If repository name is different:
- Use your actual repository name in the remote URL
- The URL will be: `https://github.com/YOUR_USERNAME/your-repo-name.git`

## Verification:

Once deployed, check:
1. Website loads correctly
2. All sections display properly
3. Mobile responsiveness works
4. Download resume button works
5. Contact form displays (Formspree setup needed separately)

## Custom Domain (Optional):

If you want a custom domain later:
1. Buy domain from GoDaddy/Namecheap
2. Add CNAME file to repository
3. Configure DNS settings
4. Update GitHub Pages settings
