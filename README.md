# Stanley Osondu – Personal Website

Personal academic site: research, projects, teaching and CV. Plain HTML, no build step, hosted free on GitHub Pages.

## Files

```
index.html                         ← the whole site (edit content in the <script> at the bottom)
cv.pdf                             ← add your CV here (the "Download CV" buttons link to it)
images/                           ← project cover pictures (+ optional profile.jpg headshot)
projects/power-plant-heatmap.html  ← Global Power Plant Heatmap web map
```

## Publish on GitHub Pages (about 5 minutes)

1. Sign in to GitHub as **StanLi01**.
2. Create a new **public** repository named exactly `stanli01.github.io`.
3. On the repo page click **Add file → Upload files**, drag in `index.html`, `README.md`,
   `cv.pdf` and the `projects` folder, then click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment" choose
   **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
5. After a minute or two the site is live at **https://stanli01.github.io**.

## Adding a new project or paper

1. Open `index.html` and scroll to `EDIT YOUR CONTENT HERE`.
2. Copy one `{ ... }` block in the `research`, `projects` or `teaching` list and change the text.
3. For a project with its own page (like another web map), put the HTML file in `projects/`
   and link to it: `links: [{ label: "Open live map", url: "projects/my-map.html" }]`.
4. A new `category` value automatically gets its own filter button.

You can edit files directly on GitHub (click the file → pencil icon); the site updates within a minute or two.
