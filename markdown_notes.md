---
layout: page
title: "Notes"
---

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/rchurro/dubs/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/rchurro/dubs/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.


### Creating Posts
- under the _posts folder, create the file
```
touch $(date +"%F")-whatever-you-want.md
```
- add meta data
```
layout: post
title: "POST TITLE"
date: YYYY-MM-DD hh:mm:ss -0000
categories: CATEGORY-1 CATEGORY-2
```

### Useful links about jekyll
https://michaelsoolee.com/jekyll-post-pag
https://davan690.github.io/2022-02-08-jekyll-information/
https://ddewaele.github.io/running-jekyll-in-docker/


# how to remove everything from privategpt api

```
for i in `curl -X GET localhost:8001/v1/ingest/list| jq -r '.data[].doc_id'`; do curl -X DELETE loca
lhost:8001/v1/ingest/$i; done
```

