### eleventy-data-pages-demo

Example of creating separate pages from a data file in Eleventy.

I wrote this for my site then ended up not needing it. For my own future sanity, I wanted to preserve this as a sample of what I did. This is all documented on [this page of the Eleventy docs](https://www.11ty.dev/docs/pages-from-data/) with the exception of this `title` part which was elsewhere in the docs (and I now can't find), in `workflows.njk`:

Setting the page title (or any other data) in a pagination setup.

```
eleventyComputed:
  title: "{{ workflow.name }}"
```