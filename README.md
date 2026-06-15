# Design Portfolio

Static portfolio site for GitHub Pages.

## Project Structure

- `docs/index.html` - public home page
- `docs/CSS/style.css` - site styles
- `docs/img` and `docs/assets` - portfolio images
- `.github/workflows/pages.yml` - GitHub Pages deployment workflow

## Deploy With GitHub Actions

1. Create a new repository on GitHub.
2. Push this project to the repository.
3. Open the repository on GitHub.
4. Go to `Settings` > `Pages`.
5. Under `Build and deployment`, set:
   - Source: `GitHub Actions`
6. Click `Save`.
7. Go to the `Actions` tab.
8. Open `Deploy Portfolio to GitHub Pages`.
9. Wait for the workflow to finish.

Your site URL will look like:

```text
https://your-username.github.io/your-repository-name/
```

## Update Workflow

1. Edit files inside `docs`.
2. Commit the changes.
3. Push to the `main` branch.
4. GitHub Actions deploys the portfolio automatically.
