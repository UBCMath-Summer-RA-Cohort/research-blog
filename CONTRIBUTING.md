# Contributing a Post

Full instructions are in the blog itself: **[posts/how-to-contribute/index.qmd](posts/how-to-contribute/index.qmd)**

## Quick Steps

1. `git clone` the repo
2. `conda env create -f environment.yml` (first time only)
3. `conda activate ubcmath-ra-blog`
4. `git checkout -b firstname-lastname/your-topic`
5. Create `posts/your-topic/index.qmd` with proper YAML frontmatter
6. `quarto preview` to check locally
7. `git add`, `git commit`, `git push`
8. Open a pull request on GitHub targeting `main`

## PR Checklist

- [ ] Branch name follows `firstname-lastname/topic` format
- [ ] Post is in its own folder under `posts/`
- [ ] YAML has `title`, `author`, `date`, `description`, and `categories`
- [ ] `quarto render` completes without errors locally
- [ ] No large binary files committed (images are fine; avoid datasets > 10 MB)
