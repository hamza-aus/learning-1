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
