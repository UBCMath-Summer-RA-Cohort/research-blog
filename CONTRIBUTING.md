# Contributing a Post

Full instructions are in the blog itself: **[posts/how-to-contribute/index.qmd](posts/how-to-contribute/index.qmd)**

## Quick Steps

1. Install [Git](https://git-scm.com) and [Quarto](https://quarto.org/docs/get-started/)
2. `git clone` the repo
3. `git checkout -b firstname-lastname/your-topic`
4. Create `posts/your-topic/index.qmd` with proper YAML frontmatter
5. `quarto preview` to check locally
6. `git add`, `git commit`, `git push`
7. Open a pull request on GitHub targeting `main`

> **Jupyter/conda not required** unless your post has executable Python code. See the [optional setup section](posts/how-to-contribute/index.qmd#optional-adding-executable-code) if you need it.

## PR Checklist

- [ ] Branch name follows `firstname-lastname/topic` format
- [ ] Post is in its own folder under `posts/`
- [ ] YAML has `title`, `author`, `date`, `description`, and `categories`
- [ ] `quarto render` completes without errors locally
- [ ] No large binary files committed (images are fine; avoid datasets > 10 MB)
