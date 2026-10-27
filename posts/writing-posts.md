This post exists for two reasons: to show how the blog is put together, and to act as a copy-paste reference whenever I write something new. If you're reading it on the live site, it's also a preview of how formatting renders.

## Adding a new post — three steps

1. **Write the post** as a Markdown file in the `posts/` folder, for example `posts/my-new-post.md`. Don't put the title inside the file — that comes from the next step.
2. **Add an entry** to `posts/posts.json` with the slug (the filename without `.md`), title, date, category, a short excerpt, and tags.
3. **Push to GitHub.** GitHub Pages rebuilds the site and the post goes live. No build tools to run.

New entries go at the **top** of `posts.json`, since the list shows posts in that order.

## Formatting you can use

Standard Markdown works. Here's the quick tour.

You can **bold** text, *italicize* it, and link to [anything](https://github.com/Logan722). Inline `code` looks like this.

### Lists

- Bullet points
- Work the way you'd expect
- As many as you need

And numbered steps:

1. First
2. Second
3. Third

### Code blocks

```
# A fenced code block keeps its formatting
nmap -sV -p- 10.0.0.5
```

### Quotes

> Pull out a key line, a quote, or a takeaway with a blockquote.

### Images

Drop an image into the repo and reference it by filename:

`![alt text](my-screenshot.png)`

---

That's the whole system. Replace this post (and the intro) whenever you're ready — they're just here to get things started.
