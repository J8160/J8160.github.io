# My writing site

A personal site for writing on literature, music, and philosophy. GitHub Pages builds and hosts it for free, and you don't need to install anything.

## Publish the site for the first time

1. Create a free account at [github.com](https://github.com/signup). Your username will be part of the site's address, so choose one you'd be happy for a college to see.
2. Create a [new public repository](https://github.com/new) named exactly `YOUR-USERNAME.github.io`.
3. On the new repository's page, click **uploading an existing file**. Drag in everything inside this folder, including the folders whose names start with `_`, then click **Commit changes**.
4. Go to **Settings → Pages** and check that **Source** is set to **Deploy from a branch**, with the branch set to `main` and the folder to `/ (root)`. Click **Save** if you changed anything.
5. After a minute or two, your site is live at `https://YOUR-USERNAME.github.io`.

Before you share the link, change your name and tagline in `_config.yml`, and replace every `[bracketed]` passage in `about.md`.

## Post something new

1. In your repository on GitHub, open the `_posts` folder. If it doesn't exist yet, click **Add file → Create new file** from the main page and type `_posts/` at the start of the file name.
2. Name the file with the date and a short title, in lowercase with hyphens: `2026-11-01-on-reading-middlemarch.md`. The last part becomes the piece's web address.
3. Paste in the contents of `new-post-template.md`, then fill it in.
4. Click **Commit changes**. The post appears within a minute or two.

To edit a post later, open its file on GitHub and click the pencil icon.

### The fields at the top of a post

| Field | What it does |
| --- | --- |
| `title` | The title. Keep the quotation marks. |
| `section` | Must be exactly `literature`, `music`, or `philosophy`. |
| `description` | One sentence shown in lists and in link previews. |
| `featured` | Set to `true` to list the piece under **Start here** on the home page. |

### Formatting

The files in `_drafts` show footnotes, block quotes, poems, embedded recordings, and images. Open them on GitHub to see how each is written. They never appear on the site, so you can delete them once you no longer need them.

A public repository can be read by anyone, including the `_drafts` folder. Keep unfinished work somewhere else until it's ready to post.

## Change the sections

Section names, symbols, and descriptions are in `_data/sections.yml`.
