# Lucas Off Script — site starter

## What's here
- index.html — hero with scroll-driven dandelion bloom + seeds that drift down the page
- frames/wide/ — 90 WebP frames, 1280px (desktop/tablet)
- frames/small/ — 50 WebP frames, 720px (phones)

## Put it online (all from an iPad)
1. github.com → New repository → name it `offscript-site`, Public, Create.
2. "uploading an existing file" → unzip this on the iPad in Files, then upload
   index.html, README.md, and the whole `frames` folder. Commit.
3. vercel.com → Add New → Project → import `offscript-site` → Deploy.
   No framework, no build command, no settings to change.
4. Buy the domain, then add it under Project → Settings → Domains.

## To edit later
Open the repo at github.dev (or Codespaces) in Safari — a full code editor
in the browser. Commit, and Vercel redeploys on its own.

## Knobs
- Hero scroll length: `.hero { height: 320vh }` — lower = faster bloom.
- Seed count/behavior: COUNT_SEEDS and the `seeds.push({...})` line in the script.
- Headline and subhead: in the `.hero__type` block.
