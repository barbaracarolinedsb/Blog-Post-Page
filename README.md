# MyBlog — Semantic HTML Blog Post Page

A single-page blog post built with semantic HTML5, focused on structure and accessibility rather than styling.

Project based on the [Blog Post Page](https://roadmap.sh/projects/blog-post-page) challenge from [roadmap.sh](https://roadmap.sh).

## Live demo

https://barbaracarolinedsb.github.io/myblog/

## How to run locally

No dependencies or build step required. Just open the file directly in your browser:

1. Clone the repository:
   ```bash
   git clone https://github.com/barbaracarolinedsb/myblog.git
   cd myblog
   ```
2. Open `index.html` in your browser (double-click the file, or):
   ```bash
   open index.html      # macOS
   xdg-open index.html  # Linux
   start index.html     # Windows
   ```

## Project structure

```
myblog/
├── index.html
├── assets/
│   └── mountain.jpg
└── README.md
```

## What this project covers

- Semantic page regions: `<header>` with the site name and navigation, `<main>` containing a single `<article>`, and `<footer>` with closing content.
- One `<h1>` for the post title, with `<h2>` used for real subsections — no skipped heading levels.
- Real text elements: `<p>` for paragraphs, `<ul>` for lists, `<blockquote>` with `<cite>` for quoted text, and `<code>`/`<pre>` for inline code and code blocks.
- Meaningful emphasis: `<em>` for stress emphasis and `<strong>` for importance — not used purely for visual styling.
- Descriptive link text on every link (no "click here" or "read more").
- A `<figure>` with a descriptive `alt` on the `<img>` and a `<figcaption>`.
- Head metadata: `<title>`, `<meta charset>`, `<meta viewport>`, and a meta description summarizing the post.

## License

Free to use for study purposes.
