---
layout: post
title: "From Markdown to a Website"
date: 2026-10-22
---

A GitHub Pages site connects three familiar pieces: files, commits, and a build.

1. **Markdown files hold the content.** `index.md` is the homepage. Files in
   `_posts` become dated blog posts.
2. **YAML holds the settings.** `_config.yml` chooses the theme and site title.
   The front matter at the top of a page sets its layout, title, and date.
3. **A commit records an update.** Pushing the change to the publishing branch
   starts a build, and a successful deployment updates the public website.

Git's detailed history makes it possible to inspect what changed between versions.
That is useful when a page stops building or when an earlier explanation needs
to be recovered.

For the homework report, the same publishing idea will apply to a site generated
by the analysis pipeline. This tutorial contains practice material only.
