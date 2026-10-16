# Agents at Home

Source for my personal blog about building self-hosted AI agents. It's a plain Jekyll site that GitHub Pages builds automatically.

## Writing a new post

1. Add a file to `_posts/` named `YYYY-MM-DD-short-title.md`.
2. Start it with front matter:

   ```yaml
   ---
   layout: post
   title: "Post title"
   subtitle: "Optional one-liner"
   description: "One sentence for search results and link previews."
   date: 2026-10-16
   tags: [hermes-agent, claude]
   mermaid: true   # only if the post has ```mermaid diagrams
   ---
   ```

3. Write in Markdown. Fenced `mermaid` blocks render as diagrams.
4. Commit and push. The site updates in a minute or two.

## Preview locally (optional)

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
