*Foreword:* **ThePost** is just at the beginning of its development; bugs may happen, display may be a bit odd.  

# What is ThePost?
**ThePost**, or rather `thepost.io`, can be seen as a blog engine, but it's more subtle than that.  
It's a publishing playground where the authors keep full control and ownership of their work. **How?** Simple, we don't store your content, actually, we don't even cache it!

## What do you mean?
ThePost relies on **Github**, if you publish your articles in a certain ways there, they show up here, with a nice display, nice URL to share, SEO support, etc. Note that ThePost is by no means associated with GitHub, it just uses some of its features.

# How do I make content available on ThePost?
Here is the basics, we'll get into the details later:
1. Fork [this repo](https://github.com/thepostio/thepostworkspace) (keep the name `thepostworkspace`, it's important)
2. Create a folder in `articles/` for your fist article, using only lowercase letters and dashes instead of spaces
3. Create a `config.json` inside the folder you've just created (or copy-paste the one from the `getting-started` article)
4. Edit the fields of your fresh `config.json`
5. Create a `index.md` in the same folder
6. Write your article in `index.md`, using the Markdown syntax
7. Update the file `thepost.json` in the root folder of this repo, by adding the name of your article's folder on top of the `article` property. Also, update the `authors`.
7. Commit and push that on your GitHub repo
8. Visit `https://thepost.io/YOUR_GITHUB_USERNAME/YOUR_ARTICLE_TITLE_SLUG`

**Example:** if your username on GitHub is `johnnybravo` and the folder name of your article (lowercase + dashes) is `my-fabulous-article`, then you can see and share your article at:  
`https://thepost.io/johnnybravo/my-fabulous-article`
