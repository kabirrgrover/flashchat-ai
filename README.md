# FlashChat AI - Website Files for GitHub Pages

This folder contains the website files needed for your A2P 10DLC campaign verification.

## Files Included:
- `index.html` - Main landing page explaining the service
- `terms.html` - Terms of Service
- `privacy.html` - Privacy Policy

## How to Deploy to GitHub Pages:

### Step 1: Create a GitHub Account
If you don't have one, go to https://github.com and sign up (it's free).

### Step 2: Create a New Repository
1. Click the `+` icon in the top right → "New repository"
2. Name it: `flashchat-ai` (or any name you want)
3. Make it **Public** (required for GitHub Pages)
4. Don't initialize with README
5. Click "Create repository"

### Step 3: Upload Files
1. On your new repository page, click "uploading an existing file"
2. Drag and drop all 3 HTML files:
   - index.html
   - terms.html
   - privacy.html
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to your repository Settings
2. Scroll to "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 1-2 minutes for deployment

### Step 5: Get Your URL
Your site will be live at:
```
https://[your-username].github.io/[repository-name]/
```

For example: `https://johndoe.github.io/flashchat-ai/`

## Important: Update Before Submitting Campaign

### In `index.html`:
Replace `[YOUR TWILIO NUMBER]` with your actual Twilio phone number.

Example: Change this:
```html
<div class="phone-number">
    [YOUR TWILIO NUMBER]
</div>
```

To this:
```html
<div class="phone-number">
    +1 (555) 123-4567
</div>
```

## Testing Your Site
Once deployed, test all links:
- ✅ Main page loads
- ✅ Terms of Service link works
- ✅ Privacy Policy link works
- ✅ All pages look correct on mobile

## URLs You'll Need for Campaign:
After deployment, you'll use these URLs in your Twilio campaign:

1. **Main page:** `https://[your-username].github.io/[repo-name]/`
2. **Terms:** `https://[your-username].github.io/[repo-name]/terms.html`
3. **Privacy:** `https://[your-username].github.io/[repo-name]/privacy.html`

## Next Steps:
Once your site is live, update your Twilio campaign "Message Flow/Call to Action" with the new information (see the updated text provided separately).

## Need Help?
GitHub Pages documentation: https://pages.github.com/
