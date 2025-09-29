# Alex Ortiz — Data Science Portfolio

This repository contains a static portfolio website (landing, about, gallery, contact) built with plain HTML, CSS and a little JavaScript.  
Designed for GitHub Pages.

## Live site
(When deployed) https://<your-username>.github.io/<repo-name>  
Replace `<your-username>` and `<repo-name>` accordingly.

## What’s inside
/
├─ index.html # Landing / home
├─ about.html # About page
├─ gallery.html # Projects gallery (search + filters)
├─ contact.html # Contact form (client-side simulation)
├─ assets/ # CSS, JS, images (if present)
└─ README.md


## How to add a new project (gallery)
There are two easy ways:

**A — Centralized (recommended)**
Open `gallery.html` and in the `projects` array add an object:
```js
projects.push({
  name: "New Project",
  summary: "Short description",
  highlights: ["Highlight 1", "Highlight 2"],
  stack: ["Python","Flask"],
  featured: false,
  repo_url: "https://github.com/...",
  live_url: "https://..."
});

