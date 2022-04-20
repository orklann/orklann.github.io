---
layout: post
title: More About Caprice
---

{{ page.title }}
================

<p class="meta">20 April 2022</p>

Tonight, before going to my guitar practice routine, I feel it's good to write 
down some notes about Caprice. I love PDF, it's an elegant document format, and 
I like to learn more about PDF standards. While I am learning PDF, I am also
improving Caprice.

After implementing the foundations and writing relevant unit tests, it's time for
some text showing functionality, now the skeleton of Caprice is done. 

Here is a snippet on how to use Caprice to create PDF.

```python
from caprice.document import Document

doc = Document()
page = doc.add_page()
page.draw_text(0, 0, "Hello Caprice!")
doc.save("hello.pdf")
```

But this is only the beginning of the story of Caprice, let's keep going, and 
keep improving it.
