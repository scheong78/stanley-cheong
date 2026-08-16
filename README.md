# Stanley Cheong — Portfolio

This folder is ready to publish directly with GitHub Pages.

## Repository structure

The important point is that `index.html`, `styles.css`, `script.js`, `assets/`,
and the CV files must all sit at the **top level of the repository**.

```text
stanley-cheong/
├── index.html
├── styles.css
├── script.js
├── .nojekyll
├── Stanley-Cheong-CV.pdf
├── Stanley-Cheong-CV.docx
└── assets/
    ├── stanley-cheong.jpg
    ├── projects/
    ├── community/
    ├── freelance/
    └── operations/
```

Do **not** upload a parent folder named `stanley-cheong-github-pages`
inside the repository. Upload the contents of this folder.

## GitHub Pages settings

In GitHub:

1. Open the `stanley-cheong` repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Branch: `main`
5. Folder: `/ (root)`
6. Save.

The site should then be available at:

`https://scheong78.github.io/stanley-cheong/`

## If replacing an existing version

Delete the old website files from the repository first, then upload all of the
files and folders in this package. Make sure the `assets` directory is present.

GitHub Pages can take a few minutes to update after a commit.
