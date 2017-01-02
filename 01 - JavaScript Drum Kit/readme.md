Some differences between wes's tutorial and my implementation:

Speed:
Granted these are microsecond optimizations mine is about x% faster. Wes's version also (somehow) seems to fire the end time twice. I'm only taking the slower of the two times:

Mine:

Wes:


Mouse:
There's stuff on the screen that looks clickable. I want to click it. Now I can.

Keyboard:
In Wes's version if you hold a key it will eventually freeze and stay there. Mine always removes the class.

Error handling:
I imagined that when adding sounds you'd want to know what's working & what isn't. I added some utility to allow for that.

css:
Although I still disagree with a bunch of the css that's in here
- scale with `rem`
- disabled select on "key"
