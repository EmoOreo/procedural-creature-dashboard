# procedural-creature-dashboard

**Live dashboard tracking trending procedural creature generation tools on GitHub & Reddit.**

Features live API data for nmagarino & wanghaisheng projects, feature comparisons (limbs, heads, Godot support), visual gallery, and interactive Godot 4 integration checklist. Built for Project Genesis / Sanctuary Site-04.

**Features:**
- Live GitHub API data for monitored repositories
- Search for new procedural creature tools
- Visual reference gallery (SDF, Spore-style, Godot concepts)
- Interactive Godot 4 integration checklist (persists in browser)
- Feature comparison table (limbs, heads, engine support, Godot readiness)
- Recent Reddit activity highlights
- Alerts & monitoring section

## Deploy to Vercel (Recommended)

### Easiest from Phone or Desktop

1. Go to [vercel.com](https://vercel.com) and sign in with GitHub.
2. Click **"Add New..." → Project**.
3. Choose **"Import Third-Party Git Repository"** or create a new repo.
4. Upload / push this folder (or just the files) to GitHub.
5. Import the repo on Vercel — it will auto-deploy as a static site.

### Alternative: Direct Drag & Drop on Vercel
- On Vercel dashboard, you can sometimes drag a folder directly when creating a new project.

After deployment you'll get a URL like:
`https://your-project.vercel.app`

The dashboard works fully on mobile too.

## Local Preview
Just open `index.html` in any browser. All live features use the public GitHub API.

## Tech Notes
- Single-file static site (Tailwind via CDN)
- Client-side GitHub API calls (public, rate-limited)
- Images are local relative files
- Godot checklist uses localStorage

Built for game developers working on procedural creature systems (especially Godot 4).

---

**Original project by Grok • Expanded June 2026**