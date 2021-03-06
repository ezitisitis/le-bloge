---
title: "Markdown"
date: 2020-12-08T20:09:46+00:00
tags: ["test", "markdown"]
featured_image: ""
description: "This page contains some test content"
draft: false
---

Paragraphs are separated by a blank line.

2nd paragraph. *Italic*, **bold**, and `monospace`. Itemized lists look like:

  * this one
  * that one
  * the other one
  * And one more which has really-really-really long which should go in two rows, to check if everything is working fine.

Note that --- not considering the asterisk --- the actual text content starts
at 4-columns in.

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.

Use 3 dashes for an em-dash. Use 2 dashes for ranges (ex., "it's all in 
chapters 12--14"). Unicode is supported. ☺

## An h2 header

Here's a numbered list:

 1. first item
 2. second item
 3. third item

Note again how the actual text starts at 4 columns in (4 characters from the 
left side). Here's a code sample:

    # Let me re-iterate ...
    for i in 1 .. 10 { do-something(i) }

As you probably guessed, indented 4 spaces. By the way, instead of indenting 
the block, you can use delimited blocks, if you like:

~~~
define foobar() {
    print "Welcome to flavor country!";
}
~~~

(which makes copying & pasting easier). You can optionally mark the delimited
block for Pandoc to syntax highlight it:

~~~python
import time
# Quick, count to ten!
for i in range(10):
    # (but not *too* quick)
    time.sleep(0.5)
    print(i)
~~~

### An h3 header ###

Now a nested list:

 1. First, get these ingredients:

      * carrots
      * celery
      * lentils

 2. Boil some water.

 3. Dump everything in the pot and follow
    this algorithm:

    Do not bump wooden spoon or it will fall.

Notice again how text always lines up on 4-space indents (including that last
line which continues item 3 above).

Here's a link to [a website](http://foo.bar), to a [local doc](local-doc.html), 
and to a [section heading in the current doc](#an-h2-header). Here's a footnote
[^1].

[^1]: Some footnote text.

Tables can look like this:

| Name          | Size    | Material      | Color          |
| :-----------: | :-----: | :-----------: | :------------: |
| All Business  | 9       | leather       | brown          |
| Roundabout    | 10      | hemp canvas   | natural        |
| Cinderella    | 11      | glass         | transparent    |

A horizontal rule follows.

* * *

And images can be specified like so:

![example image](https://github.com/ezitisitis/le-bloge/blob/master/images/sample-image.jpg?raw=true "Image by Florian Klauer")
