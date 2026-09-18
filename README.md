# Amajuoyi Chinekwu Francis, cybersecurity lab portfolio

Static one page site. No build step, no dependencies. Just HTML, CSS and a little vanilla JavaScript.

```
index.html
assets/            screenshots (cropped evidence)
Amajuoyi_Chinekwu_Francis_CV.pdf
```

## Before you deploy

1. Replace `Amajuoyi_Chinekwu_Francis_CV.pdf` if the CV changes. The hero and contact section both link to that exact filename.
2. Confirm the phone number and the "Sound the Alarm" credential ID, then update them.
3. After hosting, put the live URL into the CV (it appears in the header line and in the Cybersecurity Projects section).

## Hosting options, all free

### Netlify Drop, fastest
Go to app.netlify.com/drop and drag this whole folder in. You get a live URL in about thirty seconds. Rename the site under Site settings to something like `chinekwu-cyber`.

### Render static site
1. Push this folder to a public GitHub repo.
2. Render dashboard, New, Static Site, connect the repo.
3. Build command: leave empty. Publish directory: `.`
4. Deploy. The URL looks like `https://chinekwu-cyber.onrender.com`.

### GitHub Pages
Push to a repo, then Settings, Pages, Deploy from branch, `main` and `/root`.

## Custom domain later
Any of the three hosts accept a custom domain from the dashboard. A `.com.ng` is the cheap option, a `.com` reads better on a CV.

## Editing content
All copy lives in `index.html`. Each lab is one `<article class="lab">` block: copy an existing one, change the domain label, title, bullets, command block and image path to add a new project.
