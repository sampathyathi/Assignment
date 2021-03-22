---
layout: demo
title: Tables
---


# {{page.title}}

You can create tables by using the Pipe (\|) character. Hyphen's create the header row while Pipe character separates colums. Example table shows below.

| Header | Another header | Yet another header |
|--- |--- |--- |
| row 1 | column 2 | column 3 |
| row 2 | row 2 column 2 | row 2 column 3 |


Another table example:

{% for item in site.data.Sample %}

|{{ item.LoremIpsum }}| {{ item.LoremIpsum1 }}|

{% endfor %}
