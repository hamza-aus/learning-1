```
{
    # Leet me re-iteratee ...
    for 1 in 1 .. 10 { do-something(i) }
}
```

As you probaboly guessed, indented 4 spaces. By the way, instead of indenting the block, you can use delimited blocks, if you like: 

```
define foobar() {
    print "Welcome to flavour country!";
} 
```
(which makes copying and pasting easier). You can optionally mark the delimited block for the Pandoc to syntax highlight it:

```
import time
# Quick, count to ten!
for i in range(10):
    # (but not *too* quick)
    time.sleep(0.5)
    print i
```
### An H3 header

Now a nested list:
1. First, get these ingredients:
   - carrots 
   - celery
   - lentils
2. Boil some water.

# An h1 header
Paragraphs are seperated by a blank line.

2nd paragraph. *Italic*, **bold**, and `monospace`. Itemized lists look like:

   - this one
   - that one
   - the other one

Note that --- not considering the asterisk --- the actual text content starts at 4-columns in.

> Block quotes are written like so  
> They can span multiple paragraphs, if you like.  

Use 3 dashes for an em-dash. Use 2 dashes for ranges (ex., "it's all in chapters 12--14"). Three dots ... will be converted to an ellipsis. Unicode is supported. :joy: