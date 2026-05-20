# Cancellation of Self-Sensing Due to Ego-Motion of Vibration Based Mechanosensors

**A 14-Week Research Portfolio**

## About This Project

This portfolio documents a research project investigating how ego-motion (self-induced movement) causes unwanted vibration artefacts in mechanosensors, and how these can be cancelled using signal processing techniques.

## Live Site

> Once deployed: https://[YOUR-GITHUB-USERNAME].github.io/[REPO-NAME]/

## Project Structure

```
portfolio/
├── index.html        ← Home page with 14-week progress overview
├── about.html        ← Research background and researcher bio
├── project.html      ← Detailed weekly updates (update each week!)
├── service.html      ← Methodology and technical approach
├── contact.html      ← Contact form
├── css/              ← Stylesheets
├── js/               ← JavaScript
├── lib/              ← Animation libraries
└── img/              ← Images
```

## How to Update Weekly

1. Open `project.html` in any text editor (Notepad, VS Code, etc.)
2. Find the card for the current week (look for `← Current Week`)
3. Change the class from `active` to `done` when the week is complete
4. Change the next week's class from `future` to `active`
5. Add your findings in the paragraph text
6. Save, commit, and push to GitHub (see below)

## Deploying to GitHub Pages (Step by Step)

### First Time Setup

1. Go to [github.com](https://github.com) and create a free account
2. Click the **+** button → **New repository**
3. Name it: `mechsensor-research` (or anything you like)
4. Set it to **Public**
5. Click **Create repository**
6. Upload all these files using the **"uploading an existing file"** link
7. Go to **Settings** → **Pages**
8. Under "Source", select **main** branch → **/ (root)** → **Save**
9. Your site will be live at: `https://[username].github.io/mechsensor-research/`

### Every Week (Updating Your Site)

1. Edit `project.html` with your new weekly update
2. Go to your GitHub repository in the browser
3. Click on `project.html` → click the **pencil (edit) icon**
4. Make your changes → scroll down → click **Commit changes**
5. Site updates automatically within ~1 minute!

## Research Topic

- **Vibration-based mechanosensors** — sensors that detect external mechanical stimuli via vibration
- **Ego-motion** — self-induced movement of the sensor platform (walking, reaching, etc.)
- **Self-sensing problem** — ego-motion vibrations contaminate the sensor output
- **Cancellation methods** — adaptive filtering, reference subtraction, frequency domain analysis

