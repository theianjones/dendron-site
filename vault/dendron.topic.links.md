---
id: 3472226a-ff3c-432d-bf5d-10926f39f6c2
title: Links
desc: ''
updated: 1606549317302
created: 1595003088839
stub: false
---
# Links

Dendron supports multiple types of links and formats. 

- `[markdown links](./dendron.md)`
- `[[wiki links]]`
- `[[labelled|wiki links]]`
- `![image links](https://foundation-prod-assetspublic53c57cce-8cpvgjldwysl.s3-us-west-2.amazonaws.com/assets/logo-256.png)`
- links to `[local files](assets/think.pdf)` (eg. pdfs, psds, etc)

## Wiki Links
Wiki links support **autocomplete**. To initiate:
- create wikilink brackets and start typing
- link to specific sections of notes using the `[[wiki link#header]]` syntax. Note: these links don't work in preview or when exported through a pod (yet) but do work in a published vault. 
- use the vscode [intellisense shortcut](https://code.visualstudio.com/docs/editor/intellisense#_key-bindings) to trigger the autocomplete

![](https://foundation-prod-assetspublic53c57cce-8cpvgjldwysl.s3-us-west-2.amazonaws.com/assets/images/links-autocomplete.gif)

## Backlinks

Dendron has a backlink panel which shows all notes with links to the current note. 

![](https://foundation-prod-assetspublic53c57cce-8cpvgjldwysl.s3-us-west-2.amazonaws.com/assets/images/links.backlink.jpg)

## Other Links
For links to a file format Dendron does not support, you can use the highlight the link and use `> Dendron: Open Link` to open the file using your operating system default for that file.

<a href="https://www.loom.com/share/01250485e20a4cdca2a053dd6047ac68"><img src="https://cdn.loom.com/sessions/thumbnails/01250485e20a4cdca2a053dd6047ac68-with-play.gif"> </a>
