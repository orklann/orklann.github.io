---
layout: post
title: More On Caprice
---

{{ page.title }}
================

<p class="meta">20 April 2022</p>

Tonight, before going to my guitar practice routine, I feel it's good to write 
down some notes about Caprice. I love PDF, it's an elegant document format, and 
I like to learn more about PDF standards. While I am learning PDF, I also am 
improving Caprice.

After implementing some foundation and writing relevant unit tests, it's time for
some text showing functionality, now the skeleton of Caprice is done. 

Here is a snippet on how to use Caprice to create PDF.

```python
from caprice.document import Document

doc = Document()
page = doc.add_page()
page.draw_text(0, 0, "Hello Caprice!")
doc.save("hello.pdf")
```
But the story of Caprice just begins, I will keep working on it.
