# UBC Math Summer Research Blog

A Quarto blog for summer research assistants in the [UBC Department of Mathematics](https://www.math.ubc.ca/), supervised by [Khanh Dao Duc](https://kdaoduc.com/).

🌐 **Live site:** https://ubcmath-summer-ra-cohort.github.io/research-blog/

---

## For RAs: Writing a Post

Full instructions are in the blog itself (see the *How to Contribute* post), but here's the quick version:

1. **Clone the repo**
   ```bash
   git clone https://github.com/UBCMath-Summer-RA-Cohort/research-blog.git
   cd research-blog
   ```

2. **Set up the environment** (first time only)
   ```bash
   conda env create -f environment.yml
   conda activate ubcmath-ra-blog
   ```

3. **Create your branch**
   ```bash
   git checkout -b firstname-lastname/your-topic
   ```

4. **Add your post** — create a folder and file:
   ```
   posts/your-topic/index.qmd
   ```

5. **Preview locally**
   ```bash
   quarto preview
   ```

6. **Push and open a PR** targeting `main`

See [CONTRIBUTING.md](CONTRIBUTING.md) for the full checklist.

---

## Repo Structure

```
posts/          # One folder per post (each with index.qmd)
assets/         # Shared images and files
_includes/      # HTML partials (UBC header)
_quarto.yml     # Site configuration
environment.yml # Conda environment
```

## Deployment

Pushes to `main` automatically render and deploy the site to GitHub Pages via GitHub Actions. PRs trigger a render-only check (no deploy).

---

Maintainer: [Riddhi Battu](mailto:riddhi.battu@ubc.ca)
