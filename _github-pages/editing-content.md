---
title: Editing Content
date: 2017-03-28 19:24:00 Z
---

This page includes very general guidelines for editing the content of GitHub Pages site, agnostic of the [Jekyll editor](/github-pages/editors/) you might be using. Your project's README and your editor's documentation may include more specific information.

### :pencil2: Learning Markdown

Markdown is the syntax Jekyll uses to add text formatting, links, and images to plain text files, which typically have the extension `.md` to indicate that they’re Markdown files.

1. [GitHub's guide to Mastering Markdown](https://guides.github.com/features/mastering-markdown/) is a great place to get started if you’re new to Markdown.
2. [The official Markdown documentation](https://daringfireball.net/projects/markdown/) includes a full reference of all of the standard features.
3. Advanced users might also be interested in the non-standard features supported by GitHub Pages, including emoji, syntax highlighting, and footnotes, which are part of [GitHub Flavored Markdown](https://help.github.com/articles/about-writing-and-formatting-on-github/) and [Kramdown](https://kramdown.gettalong.org/quickref.html).

If you have a Google or Microsoft Word document that you want to publish on GitHub Pages, check out Ben Balter's [Word to Markdown Converter](http://word-to-markdown.herokuapp.com).

### :memo: Adding Pages

A very simple GitHub Pages site might only have one page, which is usually saved as `index.md` in the root directory of the repository. This is the home page.

To add more pages, simply save new files with an `.md` extension. By default, the URL of the published web page will match where you save the file, so a file named `team.md` saved in an `about-us/` folder will be published as `/about-us/team.html`.

Each `.md` file must start with a title between lines of three hyphens. For example:

```
---
title: About Us
---

This the **Markdown** content of the About Us page.
```

That's all you need to know to get started, but it only scratches the surface of what Jekyll can do. For more information, refer to the [Jekyll docs](https://jekyllrb.com/docs/home/).

* ["Creating pages" from Jekyll](https://jekyllrb.com/docs/pages/)

### :camera: Adding Images

Images added directly to a GitHub Pages repository can be referenced from Markdown files using their file path. For example, an image saved to `images/project.jpg` can be added to a Markdown page with `![Project Image](/images/project.jpg)`.

:warning: **IMPORTANT: Please resize photographs before you upload them!** Most images downloaded directly from a camera should be downsized so that the file is no larger than 500 kilobytes. The image files you add will be downloaded in full when someone visits your site on a cellular connection, so be kind and resize!

You can also reference images hosted at another URL, or embed video and other media by copying and pasting the HTML embed code from sites such as from YouTube or SlideShare.

* ["Including images and resources" from Jekyll](https://jekyllrb.com/docs/posts/#including-images-and-resources)