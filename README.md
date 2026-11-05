# ActPrune — Project Page

Project website for **"ActPrune: Action-Grounded Visual Token Pruning for Efficient Vision-Language-Action Models."**

## Contents

```
index.html                    # the project page (HTML + CSS in one file)
static/images/                # figures pulled from the paper
  idea.png                    # key idea (Fig. 1)
  method.png                  # framework overview (Fig. 2)
  libero_ex.png               # LIBERO task examples
  robot-1.png                 # real-robot task examples
static/videos/
  ICRA2027_video_V6.mp4       # video overview
```

## Publish with GitHub Pages

1. Push these files to the `gh-pages` branch of the `actprune` repository (so `index.html` sits at the top level).
2. On GitHub, go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, pick the `gh-pages` branch and the `/ (root)` folder, then **Save**.
4. After a minute, the site is live at:

```
   https://ewha-mmai.github.io/actprune/
```

## Things to update before sharing

- **arXiv / Code links** — in `index.html`, the `arXiv` button points to a placeholder and `Code` is marked *SOON*. Replace the `href` once the URLs are available.
- **BibTeX** — update the citation block once the official entry is assigned.
- **Meta tags** — update `og:url` and `og:image` in `<head>` to the final domain.

## Editing

Everything (HTML and CSS) lives in a single `index.html`, so you can open it directly in a browser to preview changes — no build step.
