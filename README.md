# AI Study Planner

Study Smarter, Not Harder

A browser prototype for weekly study planning and recovery after missed sessions.

## Open locally

Open `index.html` in a modern browser. No installation, server, API key or build step is required.

## Features

- Tasks with deadlines, estimated durations and priorities.
- Available study hours and a weekly plan.
- Completed/missed sessions and individually approved recovery suggestions.
- English, Russian and Kazakh interfaces; English is the initial default.
- A prepared example plan and JPG export.
- Local task-request classification and study-time estimation.
- Feedback saved locally and exported as JSON.

## Publish with GitHub Pages

1. Create a public repository, for example `ai-study-planner`.
2. Upload the contents of this folder to the repository root, including `index.html`.
3. Open **Settings → Pages**.
4. Set **Source → Deploy from a branch**.
5. Select **main** and **/(root)**, then save.
6. Wait for GitHub to display the published website address in Pages settings.

The address normally follows `https://YOUR-USERNAME.github.io/ai-study-planner/`.
Upload extracted files, not the ZIP archive itself.

## Prototype scope

This is a one-week prototype with 30-minute planning units. The scheduler checks deadlines, available hours and conflicts. The AI component is a small local text classifier and duration regression model, with structured date/time extraction. Its initial duration examples are illustrative, not measured student results. Explicitly recorded actual times can personalize later estimates. All suggestions require review.

Plans, feedback and learning examples stay in the current browser. Opening the hosted site creates a separate browser data store from the local HTML file. No external AI service, LMS or account system is connected.

Official hosting instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
