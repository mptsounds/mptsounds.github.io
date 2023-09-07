# How I made this blog
Welcome to my new blog!
I'm learning to host a blog using GitHub Pages and Jekyll. This doc only covers the *initial setup & first launch* of this blog. I hope this will be useful for those who're entirely new to GH and/or blog hosting to kickstart their own blog. Check out [my blog](https://mptsounds.github.io/) for my learning journey and posts on beautifying & adding custom features (Coming Soon™️ 😆 )

> ❗*IMPORTANT: This guide is a work in progress.*

## Before we start:
First things first, you should have a [GitHub account](https://github.com/join). Don't worry, it's free!

Next, you need to create a [repository](https://docs.github.com/en/get-started/quickstart/create-a-repo) to host all your files.


## First launch:
- Create a new *public* repository with this format: `mptsounds.github.io` (replace `mptsounds` with your username)
 - If you have a free account, the repo must be public for GitHub Pages feature to work.
- Decide which folder to host your file
 - Users can host GH pages from the root of the repo OR a separate folder named `/docs`
 - If you want to host from `/(root)`, move on to next step.
 - I chose `/docs` since I don't like files lying unorganised in the root folder.
Now, create the docs folder by add a new file named: `/docs/README.md` (this creates a subfolder named `docs` and README.md underneath it)
 - Anything you type in the document above using GitHub Markdown will be the contents of your home page.
- Inside the repo, go to Settings (top right corner) >> Pages (left-hand dropdown) >> Branch >> choose /docs >> Save >> Check puplished blog which is https://mptsounds.github.io/
<img width="500" alt="screenshot" src="https://github.com/mptsounds/mptsounds.github.io/assets/124775093/4976d855-2c76-48e2-af2a-332813253aff">

## Setting up a theme:
- Inside `/docs` folder, add a new file called `_config.yml`. This is used for defining a theme and do further styling in the blog
- See [here](https://pages.github.com/themes/) for the basic supported themes
- I went with `minima` theme for the first launch, so in that config doc, I just typed: `theme: minima`
- If you want, choose a proper theme by browsing: https://jekyllthemes.io/free

## Adding more pages:
*Writing in progress*

## Linking to other pages from the Home page:

## Resources:
- Markdown documentation: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
