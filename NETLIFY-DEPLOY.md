# How to Deploy to Netlify (Free)

## Method 1: Drag and Drop (Easiest - 2 minutes)

1. **Go to Netlify:**
   - Visit: https://app.netlify.com/
   - Sign up for free (use email or GitHub)

2. **Deploy:**
   - On the Netlify dashboard, find "Sites" section
   - Look for "Want to deploy a new site without connecting to Git?"
   - Drag and drop your entire project folder (the folder containing index.html, styles.css, etc.)
   - Wait 30 seconds - your site will be live!

3. **Get Your URL:**
   - Netlify will give you a random URL like: `https://random-name-123.netlify.app`
   - You can change it to something custom later

## Method 2: Git Integration (Recommended for updates)

1. **Create GitHub Account** (if you don't have one)
   - Go to: https://github.com
   - Sign up for free

2. **Upload to GitHub:**
   - Create a new repository
   - Upload all your files
   - Push to GitHub

3. **Connect to Netlify:**
   - Go to Netlify dashboard
   - Click "Add new site" → "Import an existing project"
   - Connect to GitHub
   - Select your repository
   - Click "Deploy site"

4. **Auto-Deploy:**
   - Every time you update files on GitHub, Netlify automatically updates your website!

## After Deployment - Important Steps:

### 1. Update Your URLs
After getting your Netlify URL, update these files:

**In index.html, delhi-escorts.html, noida-escorts.html, etc.:**
- Change `https://yourwebsite.com` to your actual Netlify URL
- Update canonical URLs
- Update Open Graph URLs

**In sitemap.xml:**
- Change all `https://yourwebsite.com` to your Netlify URL

**In robots.txt:**
- Update sitemap URL to your Netlify URL

### 2. Custom Domain (Optional)
- In Netlify dashboard → Site settings → Domain management
- Add your custom domain (if you have one)
- Netlify will provide DNS settings

### 3. Submit to Google Search Console
- Go to: https://search.google.com/search-console
- Add your Netlify URL
- Submit your sitemap: `https://your-site.netlify.app/sitemap.xml`

## Netlify Free Tier Limits:
- ✅ 100 GB bandwidth per month (plenty for most sites)
- ✅ 300 build minutes per month
- ✅ Unlimited sites
- ✅ Free SSL certificate
- ✅ Form handling (100 submissions/month)

## Tips:
1. **Always use HTTPS** - Netlify provides it automatically
2. **Update URLs** - Don't forget to change placeholder URLs
3. **Test your site** - Check all links work after deployment
4. **Monitor analytics** - Netlify provides basic analytics

## Need Help?
- Netlify Docs: https://docs.netlify.com
- Netlify Support: Very helpful community

