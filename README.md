# Contribute

Want to contribute? Fork the repository first by clicking "fork" in the upper right. Then, clone your own fork to your desktop:

```bash
$ git clone https://github.com/yourgithubusername/Huizerd.github.io.git
```

Create a Markdown file with the extension `.md` and the date and a short subject indicator in the title:

```bash
$ cd Huizerd.github.io
$ touch yyyy-mm-dd-yourpost.md
```

Adhere to the following template and the general Markdown [rules](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and your post will look great!

```markdown
--
layout: post
title: "Title of your post"
date: yyyy-mm-dd
categories: maincategory subcategory
---

Bla bla bla

### Use level 3 headers as main headers in your post

Bla bla bla interesting stuff

#### And level 4+ for any subheaders
```

In case you're not sure, look at a post in the [`_posts`](https://github.com/Huizerd/Huizerd.github.io/tree/master/_posts) directory and view its raw code with the button in the upper right!

When your post is done, `add` your changes, `commit` them to your local repository, and `push` them to GitHub:

```bash
$ git add -A  # add everything
$ git commit -m "commit message here"  # commit changes
$ git push origin master  # push to GitHub
```

Next, open a pull request [here](https://github.com/Huizerd/Huizerd.github.io/pulls), and your post will be added!
