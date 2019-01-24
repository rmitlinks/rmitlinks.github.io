# Contributing

We've done our best to make RMIT Links as easy as possible to contribute to. To add changes to RMIT Links, you first need to fork the repository (on desktops, you can use the fork button on the top right) to your own account. Once you submit changes to your own repository, you can then submit a pull request. See [Submitting changes](#submitting-changes) below.

## Contents

- [Adding links or a new page](#adding-links-or-a-new-page)
- [Submitting changes](#submitting-changes)

## Adding links or a new page

Here is an example page:

```yaml
---
layout: links-page
title: An example page
sections:
    - type: standard
    body:
        - name: "A link"
        url: https://google.com
        width: 1-1
        colour: blue

        - text: "This is a link to google.com."

    - type: small
    body:
        - text: "This is small text."
---
```

You can easily specify your own sections in the `sections` sequence, and each item in a section can be either a button or text.

To make your own page, create a folder with your intended link path as the name, and add a file called `index.html` with a layout similar to the example above.

### Types

You can have a `small` section, a `narrow` section, or a `standard` section (this is the default; you don't have to specify it)

## Submitting changes

To submit a new page, please open a pull request via the `New pull request` button in your repository, with the changes that you intend to submit. Please describe what you are adding - what links, what the page is for, etc.
