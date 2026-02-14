# GitHub Wiki Setup Instructions

## Initializing the Wiki

GitHub wikis must be initialized through the web interface before you can push to them.

### Step 1: Create First Page via Web UI

1. Go to: https://github.com/azerxafro/wiki-ashwin-azer/wiki
2. Click **"Create the first page"**
3. Add a placeholder title: "Home"
4. Add placeholder content: "Wiki initializing..."
5. Click **"Save page"**

### Step 2: Clone and Replace

Once initialized, run these commands:

```bash
cd ~/Documents/github
git clone https://github.com/azerxafro/wiki-ashwin-azer.wiki.git
cd wiki-ashwin-azer.wiki

# Copy prepared wiki pages
cp ~/Documents/github/wiki-ashwin-azer/wiki/*.md .

# Push to wiki
git add -A
git commit -m "Complete wiki pages for Ashwin Azer"
git push
```

### Step 3: Verify

Visit: https://github.com/azerxafro/wiki-ashwin-azer/wiki

---

## Wiki Pages Included

| File | Description |
|------|-------------|
| `Home.md` | Main landing page with quick facts |
| `Biography.md` | Early life and education |
| `Career.md` | Musical career and Monadelta |
| `Discography.md` | Albums, EPs, and singles |
| `Personal-Life.md` | Personal information |
| `External-Links.md` | All official links |

---

## Alternative: Wiki in Main Repo

The wiki content is also available in the `/wiki` folder of this repository.
