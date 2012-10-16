# UIColor+KECrayons

by Ian Perkins


## What is it?

A really simple category for the `UIColor` class which adds all of the colours found in the crayons palette. All, that is, except magenta, which already exists as one of the built-in `UIColor` instances. It does however include licorice and snow even though these are just fancy names for black and white.

The crayons palette is the one at the far right of the toolbar in the font colour chooser used by pretty much any OSX app which allows font colours to be changed, for example, Xcode.


## How do I use it?

Add the `.h` and `.m` to your project, import the `.h` and the 47 crayon colours will appear in the `UIColor` auto-completion list. 

The colour names are those which appear if you click a colour in the OSX chooser.

Even though it peeved me just a tiny bit, I decided to use the US spelling of the word 'colour' in the instance names so they didn't jar with the built-in colour names.