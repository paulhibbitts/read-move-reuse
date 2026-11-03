---
title: 'Meet Grav 2'
section_number: '2'
description: 'A free, open-source flat-file CMS: Markdown files in, a website out – no database.'
child_type: section-page
side_box: 'Grav''s own site, with themes, plugins and downloads: [getgrav.org](https://getgrav.org/?target=_blank).'
---

[Grav](https://getgrav.org/?target=_blank) is a free, open-source **flat-file CMS** – a website system that stores content as plain Markdown files instead of a database. Grav 2 is its new version, now a [stable release](https://getgrav.org/blog/grav-2-stable-released?target=_blank).

```mermaid
flowchart LR
  accTitle: How Grav 2 works
  accDescr: Markdown files, edited in Admin 2 or any editor, go into Grav 2, which produces web pages and Markdown versions.
  A[Markdown files] --> B[Grav 2]
  B --> C[Web pages]
  B --> D[Markdown versions]
  E[Admin 2 or any editor] --> A
```

This diagram is written as plain text, with the free [Mermaid](https://hibbittsdesign.org/cost-free-grav-projects.html?target=_blank#mermaid-plugin) plugin – and math works the same way with [LaTeX Math](https://hibbittsdesign.org/cost-free-grav-projects.html?target=_blank#latex-math-plugin), like $E = mc^2$.

What's new in Grav 2:

- **Admin 2** – a modern editing panel, rebuilt from scratch, for writing and organizing pages in the browser
- **A Markdown version of every page** – add `.md` to a page's address to get its Markdown ([Grav 2.1 release notes](https://getgrav.org/blog/grav-2-1-released?target=_blank))
- **Faster under the hood, and still just files** – [twice as fast in Grav 2.2](https://getgrav.org/blog/grav-2-2-released?target=_blank), by the Grav team's measurements, and a site that's simple to back up, copy and move

![The Admin 2 Pages screen, showing this guide's six parts plus Topics and Resources in columns, with this page selected and its details beside them](grav-2-admin-2-pages.webp)

*Admin 2: this guide's pages*

![The Admin 2 editor with this page open, showing its What's new list as Markdown, beside a Page Info panel](grav-2-admin-2-editor.webp)

*This page, open in the Admin 2 editor*

![This page in a browser, beside its Markdown version at the same address with .md added – the same text, with the diagram written as plain text](grav-2-page-and-markdown.webp)

*This page, and its Markdown version*

What Grav has always had:

- **Free and open source** (MIT license), with over 15,000 stars on [GitHub](https://github.com/getgrav/grav?target=_blank)
- **Themes and plugins** for search, feeds, forms, several languages and more
- **Runs on a standard web host** – no special server setup

**Coming from WordPress?** Much of it will feel familiar:

| In WordPress | In Grav 2 |
|---|---|
| Dashboard | Admin 2 |
| Pages and posts | Pages, each a Markdown file in its own folder – with a blog page for posts |
| Block editor | Markdown, with shortcodes for extras like callouts and embeds |
| Database | None – just files |
| A backup plugin | Copy the site's folder |

For a detailed look, including when WordPress is the better pick, see [Grav vs WordPress: An Honest Comparison](https://getgrav.org/blog/grav-vs-wordpress?target=_blank) by Grav's creator.

[hideifembedded]
Try the Admin 2 panel: read-only demos for [Open Publishing Space](https://try.hibbittsdesign.org/grav-skeleton-open-publishing-space/admin?target=_blank) and [Open Course Hub](https://try.hibbittsdesign.org/grav-skeleton-course-hub/admin?target=_blank) (the sign-in details are on their sign-in screens).

See this page [as Markdown](/grav-2/meet-grav-2.md?target=_blank), and compare the diagram with the text that draws it.
[/hideifembedded]
