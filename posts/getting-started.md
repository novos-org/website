+++
title = "Getting Started"
date = 2026-02-06
tags = setup, beginner, tutorial, info
+++

## novos at a glance
novos is a static site generator (SSG), similar to Hugo, Zola, and Jekyll. It is written in Rust and uses the Tera template engine, which is similar to Jinja2, Django templates, and Liquid.

Content is written in [CommonMark](https://commonmark.org/), a strongly defined, highly compatible specification of Markdown.

novos uses pulldown-cmark to parse markup files (Markdown). It (pulldown-cmark) adds a few additional features such as parsing footnotes, Github flavored tables, Github flavored task lists and strikethrough.

SSGs use dynamic templates to transform content into static HTML pages. Static sites are thus very fast and require no databases, making them easy to host. A comparison between static and dynamic sites, such as WordPress, Drupal, and Django, can be found [here](https://dev.to/ashenmaster/static-vs-dynamic-sites-61f).

# steps to use novos
Unlike some SSGs, novos makes a default template for your site. To disable this template, use --bare.

You will be asked a few questions.

```text
What is the URL of your site? (https://example.com):
Site Title (new novos site):
Author Name (admin):
Do you want to enable Sass compilation? [Y/n]:
Do you want to enable syntax highlighting? [Y/n]:
Do you want to build a search index? [Y/n]:
Do you want to generate an RSS feed? [Y/n]:
Clean output directory before build? [Y/n]:
Minify HTML output? [y/N]:
```

