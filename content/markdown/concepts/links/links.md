---
Title: "Links"
Subjects:
  - "Developer Tools"
  - "Web Development"
Tags: 
  - "URL"
  - "GitHub"
  - "Documentation"
CatalogContent:
  - "learn-html"
  - "paths/front-end-engineer-career-path"
---

In Markdown, a link is created by enclosing the link text in square brackets `[Link text]` and then following it immediately with the URL in parentheses `(https://website-name.com)`.

```markdown
[Link text](https://website-name.com)
```

For example:

```markdown
We just launched [Codecademy Docs](https://producthunt.com) on Product Hunt!
```

The output would look like:

We just launched [Codecademy Docs](https://producthunt.com) on Product Hunt!

## Accessibility: Link Titles

A title for a link can be optionally added. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in parentheses `()` after the URL.

Links should have link titles so that screenreaders can narrate them as well as a user can <kbd>Tab</kbd> through the page.

```markdown
[Link text](https://website-name.com "Link title")
```

For example:

```markdown
My favorite Craigslist categorey is [Missed Connections](https://newyork.craigslist.org/d/missed-connections/search/mis "The best place on the internet").
```

The output would look like:

My favorite Craigslist categorey is [Missed Connections](https://newyork.craigslist.org/d/missed-connections/search/mis "The best place on the internet").

## URLs and Email Addresses

To quickly turn a URL or email address into a link, enclose it in angle brackets `<` `>`.

- `<https://www.codecademy.com/resources/docs>`
- `<hotmale@hotmail.com>`

The rendered output looks like this:

- <https://www.codecademy.com/resources/docs>
- <hotmale@hotmail.com>
