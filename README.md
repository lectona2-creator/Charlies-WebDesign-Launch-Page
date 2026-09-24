# Charlie

A simple static website for the Charlie brand.

## GitHub Pages publishing

This project is ready to be published as a GitHub Pages site because it is a static HTML site in the repository root.

### Deploy steps

1. Push this folder to a GitHub repository.
2. Open the repository in GitHub.
3. Go to Settings → Pages.
4. Under Source, choose "Deploy from a branch".
5. Select the main branch and the / root folder.
6. Save.
7. GitHub will generate a live URL such as:
   https://<your-username>.github.io/<repository-name>/

### Local preview

You can preview the site locally with a simple HTTP server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

This site is intentionally lightweight and works well with GitHub Pages without a build step.