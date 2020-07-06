---
title: My compiled SQL has a lot of spaces and new lines, how can I get rid of it?
---
This is known as "whitespace control".

Use a minus sign (`-`, e.g. `{{- ... -}}`, `{%- ... %}`, `{#- ... -#}`) at the start or end of a block to strip whitespace before or after the block (more docs [here](https://jinja.palletsprojects.com/en/2.10.x/templates/#whitespace-control)). Check out the [tutorial on using Jinja](using-jinja#use-whitespace-control-to-tidy-up-compiled-code) for an example.

Take caution: it's easy to fall down a rabbit hole when it comes to whitespace control!