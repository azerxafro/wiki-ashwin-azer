# Ashwin Azer - Wikipedia Page

Self-hosted Wikipedia-style page for Ashwin Azer (Lucid ASH).

## 🌐 Live Site

**URL**: [wiki.ashwinazer.rocks](https://wiki.ashwinazer.rocks)

## 📁 Structure

```
wiki-ashwin-azer/
├── index.html          # Main Wikipedia page
├── css/
│   └── mediawiki.css   # Wikipedia styling
├── images/             # Images and favicon
├── CNAME               # GitHub Pages domain config
├── .nojekyll           # Disable Jekyll processing
└── README.md           # This file
```

## 🚀 Deployment

### Option 1: GitHub Pages (Recommended)

1. Create a new repository on GitHub
2. Push this folder to the repository:
   ```bash
   cd ~/wiki-ashwin-azer
   git init
   git add .
   git commit -m "Initial commit: Ashwin Azer Wikipedia page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/wiki-ashwin-azer.git
   git push -u origin main
   ```
3. Go to Repository Settings → Pages
4. Select "Deploy from a branch" → main → / (root)
5. Add CNAME record in your DNS:
   ```
   wiki.ashwinazer.rocks → YOUR_USERNAME.github.io
   ```

### Option 2: Vercel

1. Connect your GitHub repo to Vercel
2. Deploy automatically
3. Add custom domain in Vercel dashboard

### Option 3: Netlify

1. Drag and drop this folder to Netlify
2. Add custom domain

## 🔧 DNS Configuration

Add these records to your domain (ashwinazer.rocks):

| Type  | Name | Value                          |
|-------|------|--------------------------------|
| CNAME | wiki | YOUR_USERNAME.github.io        |

Or for Vercel/Netlify, use their provided CNAME values.

## 📝 Wikipedia Submission

A wikitext version is available at `wikipedia-draft.txt` for submission to Wikipedia's Articles for Creation (AfC).

### Submission Steps:

1. Go to [Wikipedia:Articles for creation](https://en.wikipedia.org/wiki/Wikipedia:Articles_for_creation)
2. Click "Submit an article"
3. Paste the wikitext content
4. Wait for review (may take several weeks)

## 📜 License

Content is licensed under [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

## 👤 Subject

**Ashwin Azer** (Ashwin Ramesh)  
Indian singer, songwriter, composer, and music producer  
Born: March 5, 2003 | Kannur, Kerala, India  
Active: 2019–present  
Label: Monadelta Productions

---

*Last updated: February 14, 2026*
