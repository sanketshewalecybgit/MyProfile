# Sanket Shewale — Personal Website

A static portfolio covering AI Security, Offensive Security, Threat Intelligence,
SOC operations, security automation, workshops, and community events.

## Preview and edit

Open `index.html` in a browser. There is no install or build step.

The page content, styles, and JavaScript are all in `index.html`. The portrait is
`photo.jpg`, and event images are in `assets/events/`.

To add your event descriptions, search for `NEW EVENT IMAGES` in `index.html`
and enter your text inside the corresponding empty caption:

```html
<figcaption class="event-description">Your event description here.</figcaption>
```

The three captions are intentionally blank until you add your descriptions.

## Update the existing GitHub repository

1. Open https://github.com/sanketshewalecybgit/MyProfile and select the branch
   used by your website. Check **Settings → Pages** if you are unsure.
2. At the repository root, choose **Add file → Upload files**.
3. Drag `index.html`, `photo.jpg`, and the entire `assets` folder from this
   project's innermost folder into the upload area. You can also include this
   README. If using the ZIP package, extract it first.
4. Confirm the uploaded paths begin with `index.html` and `assets/events/`.
   Do not upload the enclosing `MyProfile-main` folders or the ZIP itself.
5. Enter a commit message such as `Add AI Security focus, workshops, and event images`.
   Commit to the site's source branch if permitted. If you use a new branch,
   open and merge a pull request into the site's source branch.
6. If GitHub Pages is already configured, keep its existing publishing setup.
   Check the **Actions** tab for the deployment result, then open the live site
   from **Settings → Pages** and refresh it.

If Pages is not configured, this static site can use **Settings → Pages → Build
and deployment → Deploy from a branch**. Select the branch containing the files
(for example, `main`) and **/(root)**, then save. The default project URL would be
https://sanketshewalecybgit.github.io/MyProfile/ unless a custom domain is configured.

Expected layout at the repository root:

```text
index.html
photo.jpg
README.md
assets/
  events/
    Atlas.png
    foxxcon.png
    cybersecurity-session.jpg
    kurukshetra-collage.png
    ai-security-workshop.png
```

GitHub references:

- [Upload files to a repository](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
- [Configure GitHub Pages publishing](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
