*Foreword:* **ThePost** is just at the beginning of its development; bugs may happen, display may be a bit odd.  

# What is The Post?
**ThePost**, or rather `thepost.io`, can be seen as a blog engine, but not exactly.  
It's a publishing platform but not a writing platform: you write your articles on your mac or pc, in your favourite text editor, you push that on GitHub, and then they show up on [thepost.io](https://thepost.io) !  

# How do I make content available on ThePost?
1. Fork this repo (keep the name `thepostworkspace`, it's important!)
2. Create a folder in `articles/` for your fist article, using only lowercase letters and dashes instead of spaces
3. Create a `config.json` inside the folder you've just created (or copy-paste the one from the `getting-started` article)
4. Edit the fields of your fresh `config.json`
5. Create a `index.md` in the same folder
6. Write your aticle in `index.md`, using the Markdown syntax
7. Push that on your GitHub repo
8. Visit `https://thepost.io/YOUR_GITHUB_USERNAME/YOUR_ARTICLE_TITLE_SLUG`

If your username on GitHub is `johnnybravo` and the folder name of your article (lowercase + dashes) is `my-fabulous-article`, then you can see and share your article at:  
`https://thepost.io/johnnybravo/my-fabulous-article`


Code test:  
```js
let someVar = 12

function someFunc(arg){
  return arg * 2
}
```

![](footer.jpg)
