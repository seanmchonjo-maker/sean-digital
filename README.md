# Sean Digital

The landing site for **Sean Digital**, an initiative by **Sean Makoi**. Learning digital by building real solutions. It introduces the initiative and its first project, **School Tools**, with its two variations, Study and Score.

## Files

```
index.html
README.md  LICENSE  .gitignore
```

A single page, no build step.

## Run locally

Open index.html in a browser, or serve the folder.

```
python3 -m http.server 8000
```

## Deploy on GitHub Pages

1. Push this folder to a new GitHub repository.
2. In the repo, open Settings, then Pages.
3. Set Source to "Deploy from a branch", branch main, folder /root, and save.
4. The site goes live at https://YOUR-USERNAME.github.io/REPO-NAME/

Render also works as a static site with the publish directory set to the repo root.

## Linking the two tools

The two buttons on the page ("Open Study" and "Open Score") use a placeholder link (href="#"). Once each tool is deployed, open index.html, find the two lines marked with a comment "Replace href once ... is deployed", and set href to the live address of each tool, for example:

```
<a class="btn" href="https://YOUR-USERNAME.github.io/school-tools-study/">Open Study</a>
<a class="btn" href="https://YOUR-USERNAME.github.io/school-tools-score/">Open Score</a>
```

Then remove the small "Add your deployed link here." lines under each button.

## Credits

Sean Digital, an initiative by Sean Makoi. Licensed under MIT.
