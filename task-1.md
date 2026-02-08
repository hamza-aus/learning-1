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

## An h2 header
Here's a numbered list:
   1. first item
   2. second item
   3. third item  

Note again how the actual text starts at column 4 in (4 characters from the left side). Here's a code sample.

 3. Dump everything in the pot and follow this algorithm:

   ```
   find wooden spoon
   uncover pot
   stir 
   cover pot
   balance wooden spoon precariously on pot handle
   wait 10 minutes
   goto first step (or shut off burner when done)
   ```
Notice again how text always lines up on 4-space ingredients (including that last line which continues item 3 above). 
Here's a link to [a website](https://www.google.com), to a [local doc](https://www.google.com), and to a [section heading in the current doc](https://www.google.com). Here's a footnote [^1].  
Tables can look like this:  
| size | material | colour | 

---
9 leather brown 10 hemp canvas natural 11 glass transparent  
Table: Shoes, their sizes, and what they're made of  
(The above is the caption for the table.) Pandoc also supports multi-line tables:  

---
keyword text

---
red Sunsets, apples, and other red or reddish things.
green Leaves, grass, frogsand other things it's not easy being.

---
A horizontal rule follows

---
Here's a definition list:
apples
: Good for making applesauce. oranges : Citrus! tomatoes : There's no "e" in tomatoe