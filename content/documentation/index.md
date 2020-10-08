---
title: "Documentation"
_build:
    list: false
---

## Step 0: Verify Hugo is installed

```
$ hugo version
Hugo Static Site Generator v0.75.1-A4A7BAB7/extended linux/amd64 BuildDate: 2020-09-15T06:57:20Z
```

## Step 1: Create a new site

```bash
$ hugo new site hugo-site
$ cd hugo-site
```

You should have a new Hugo site scaffolded out:

```
.
├── archetypes
│   └── default.md
├── config.toml
├── content
├── data
├── layouts
├── resources
│   └── _gen
│       ├── assets
│       └── images
├── static
└── themes
```

## Step 2: Create content

```bash
$ hugo new posts/lorem.md
$ hugo new posts/ipsum.md
...
```

## Add static files

## Copy reference layouts

Copy `reference/index.html` > `layouts/index.html`
Copy `reference/list.html` > `layouts/list.html`
Copy `reference/page.html` > `layouts/single.html`

## Move common layout features to baseof.html
