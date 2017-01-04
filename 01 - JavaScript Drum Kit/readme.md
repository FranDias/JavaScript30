Some differences between wes's tutorial and my implementation:

# Speed:
Granted these are microsecond optimizations mine is about 2.6x faster (further improved to 3.6x). Wes's version actually triggers `console.timeEnd` twice. Once when the `playing` class is added & once when `playing` is removed. So, it's most accurate to just take the larger number [I think].

Keep in mind, Wes made his to teach new people how do this exercise & it's perfect for that. I just took his prompt and ran with it to see what I could do.

CSS Transition set to .001ms, 9 key presses averaged.

Mine:
```
24.319
17.154
3.674
14.654
19.370
4.677
9.842
14.848
2.860
18.928
```
13.03ms average

Wes:
```
41.329
37.010
24.789
20.532
43.381
21.861
26.026
28.381
33.912
```
30.787ms average

# Mouse:
There's stuff on the screen that looks clickable. I want to click it. Now I can.

# Error handling:
I imagined that when adding sounds you'd want to know what's working & what isn't. I added some utility to allow for that.

# CSS:
Although I still disagree with a bunch of the css that's in here
- ~~scale with `rem`~~ he accepted my PR :smile:
- disabled select on "key"
