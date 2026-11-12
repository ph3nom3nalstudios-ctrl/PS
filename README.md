# Phenomenal Studios — Portfolio Website

A lightweight, single-page portfolio built with **HTML, CSS and JavaScript**. No npm, framework, build step, backend or paid hosting required.

## Publish on GitHub Pages

1. Sign in to [GitHub](https://github.com), then select **New repository**.
2. Name it `phenomenal-studios` (or another name), make it **Public**, and create it.
3. Select **Add file → Upload files**. **Extract the ZIP first** and upload the files and `assets` folder **into the repository root**. Do not upload the ZIP itself, and do not put everything inside an extra parent folder.
4. Commit the uploaded files.
5. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
6. GitHub will show the public site URL under Pages after deployment. For a repo called `phenomenal-studios`, it will normally be `https://YOUR-USERNAME.github.io/phenomenal-studios/`.

### Folder structure

```
phenomenal-studios/
├── index.html                 # Website and embedded project list
├── projects.json              # Editable reference list of the 40 projects
├── assets/
│   └── phenomenal-logo.png    # Original logo
├── .nojekyll                  # Tells GitHub Pages to serve static files as-is
├── .gitignore
└── README.md
```

## Make changes

- **Project titles / categories / links:** Open `index.html`, search for `const projects =`, and edit the object fields there. Commit changes in GitHub; GitHub Pages will update the site. The `projects.json` file is a convenient *reference copy*; **editing that file alone does not update the website**.
- **Add a project:** Copy a project object in that list, give it a new unique numeric `id`, then change its `category`, `title`, `type`, and `url`; for YouTube projects, set `videoId` to the YouTube video ID.
- **Available categories:** `films`, `sports`, `livestreams`, `events`, `photography`, `production`.
- **Brand/logo:** Replace `assets/phenomenal-logo.png` with an image using the same filename.
- **Contact:** Search for `ph3nom3nalstudios@gmail.com` in `index.html`.
- **Facebook:** Search for `100095690522253` in `index.html`.

## Notes before launch

- Projects were compiled from the three provided CSV files, with duplicate links removed. Many had no descriptive titles. The generic labels and category assignments are placeholders for review.
- Some Facebook videos/posts may be blocked in embedded players by privacy settings, browser tracking protection, or Facebook restrictions. Each player includes an **Open original** link.
- The photography section links to the Google Photos gallery supplied in the embeds, rather than copying private images.
- Google Fonts, YouTube thumbnails and third-party embeds need an internet connection.
- You can preview locally by double-clicking `index.html`.

**Contact:** ph3nom3nalstudios@gmail.com
