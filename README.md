# enovuh documentation

this repository contains the official documentation for the enovuh discord bot, built using [mintlify](https://mintlify.com).

## local development

to run the documentation locally:

1. install mintlify cli:

```bash
npm i -g mintlify
```

2. run the development server:

```bash
mintlify dev
```

the documentation will be available at `http://localhost:3000`.

## documentation structure

- `/overview` - general information about enovuh
- `/commands` - detailed command documentation
- `/protection` - security feature documentation
- `/configuration` - server configuration guides
- `/features` - detailed feature documentation
- `/integrations` - external service integrations
- `/common-issues` - troubleshooting guides

## adding new pages

1. create a new `.mdx` file in the appropriate directory
2. add the page to `docs.json` in the navigation section
3. use proper frontmatter:

```md
---
title: "page title"
description: "page description"
icon: "icon-name" # optional
---

content goes here
```

## formatting standards

- use all lowercase for titles and headings
- use code blocks for command examples
- organize commands in tables with consistent columns
- use cards and accordions for better organization
- include usage examples for all commands

## deployment

the documentation is automatically deployed when changes are pushed to the main branch. changes typically take a few minutes to appear on the live site.

## contribution guidelines

- ensure all command documentation is accurate and updated
- follow the lowercase style guide
- test any changes locally before pushing
- use consistent formatting across all pages

for any questions or assistance, please contact the enovuh team in our [support server](https://enovuh.lol/support).
