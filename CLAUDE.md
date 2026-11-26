# Working on rendlune.com

This repository is the website of Rendlune, a Windows desktop app by QuantumStream Ventures Ltd. (Canada): one nature clip
in, an hours-long YouTube Master, Shorts and square clips with on-screen text, AI-written titles, and a Delivery folder per
platform. The site is a single page (`index.html`) on GitHub Pages (`CNAME` = rendlune.com), with `404.html`,
`robots.txt`, `sitemap.xml` and `images/`.

## Start of every session
- The app's own repository, `124lcw/cascade-studio`, holds the notes that say what is done and what is next. Read its
  `NEXT_STEPS.md` first, then `HISTORY.md` (newest first) when you need detail. If it is not attached to the session,
  attach it with `add_repo`; the GitHub file tools can read just those two files, so no full clone is needed.
- Then look at this repository's recent merged pull requests to see what already changed on the site.

## The owner
- Not a programmer. Write plainly and briefly; say what changed on the site, not how the code works.
- Work goes through a pull request into `main`. Merge only when the owner says "merge". Never force-push.

## Rules for this site
- `version.json` does not exist yet and is only created or changed at an app release, last, once the download works.
  Don't add or touch it otherwise. The installed app asks for `https://rendlune.com/version.json` once a day; a missing
  file is handled quietly.
- App screenshots come from `124lcw/cascade-studio`, branch `main`, folder `branding/screenshots/` (`01_compose.jpg` to
  `06_any_clip_shape.jpg`). Keep the file names and the sizes the page uses (`03_review.jpg` is 1919x1008 on purpose, so
  it isn't cropped). Never use the old site `124lcw/infinireel-website`.
- After any change to a page, look at it at phone width (about 390 px) and PC width (about 1440 px): nothing scrolls
  sideways and every picture loads. Say plainly which pages changed.
- Buy and Download stay "Coming soon" until the store (Polar) and the first installer exist.
- Site wording, marketing and legal text are written in the owner's claude.ai Project; code sessions here do the code.
  Don't invent claims, prices or legal text: use what the owner passes on.
- Describe every change in the pull request in plain words (which pages changed, what was checked).
