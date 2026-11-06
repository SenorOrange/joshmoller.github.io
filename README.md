# joshmoller.ca

Personal mechatronics portfolio of Josh Moller, a Mechatronics Engineering student at the University of Guelph. Live at **[joshmoller.ca](https://joshmoller.ca)** and hosted on GitHub Pages.

## Structure

| Path | What it is |
| --- | --- |
| `index.html` | Main single-page site (intro, projects, about, contact) |
| `projects.json` | Project cards shown in the Projects section |
| `media/*.html` | One page per project (`hank-collage.html` is the full engineering log) |
| `images/Projects/<Project>/` | Images, videos and `.glb` 3D models for each project |
| `assets/` | Template CSS, JS and icon fonts |

## Adding or editing a project

Each entry in `projects.json` becomes a card:

```json
{
  "id": "my-project",
  "title": "Project Name",
  "description": "One-line summary.",
  "thumbnail": "images/my-project-thumb.jpg",
  "link": "media/my-project.html"
}
```

Optional flags:

- `"comingSoon": true` shows the card with a "Media coming soon" tile and doesn't link to the project page.
- `"hidden": true` removes the card from the site without deleting it.

## Credits

Based on [Prologue by HTML5 UP](https://html5up.net) (CCA 3.0). Icons by Font Awesome.
