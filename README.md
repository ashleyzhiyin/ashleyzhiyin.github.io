# Prerequisites

- Hugo (you can skip this if you don't need to preview on your PC before publishing)
    - Download [hugo](https://github.com/gohugoio/hugo/releases/)
    - Make sure you can call `hugo` from command lines.

# Basic Usage

## Edit home page

- Edit `hugo.toml`

## Edit about page

- Edit `content/about.md`

## Add new posts

`hugo new content posts/your-post.md`

## Build draft (skip this if you don't need a preview)

`hugo server -D` or `hugo serve`

## Build (skip this if you don't need a preview)

`hugo`

## Publish

```
git pull
git add .
git commit -m "daily updates"
git push
```
