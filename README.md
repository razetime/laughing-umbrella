# Welcome to The Laughing Umbrella.

What drink would you like?

Jokes aside, this is a golfing language that I made a concept for in a desperate attempt to overcome programmer's block. This is a B-language, akin to a B-game, where many different and possibly ill-fitting things are put together into one single project, which I hope will end up in a language that is fun to use. 

Laughing Umbrella's quite a huge name, so let's call it LU for short.

## Paradigm
For now i definitely don't want this to be stack based. So I chose the Splay tree as the primary storage method for now.

The problems i need to solve now are:
- How to access arbitrarily deep elements
- What comparison method the tree will use
- how tree elements are consumed as the program executes

The programs will be in a concatenative style, single char per command unless something else really strikes me as cool.

## Semantics
Laughing umbrella will be a modal language. Commands will mean different things based on the current mode of the program, leading to about 256 sets of commands. This will probably never happen, but I can guarantee you'll have more than 1 command to work with in this language.

## Codepage
ASCII. I have no dreams of this being competitive in CGCC or any other place, but I do believe in interesting languages, and making languages is fun.

## Implementation
I'll be using [Nial](https://www.nial-array-language.org/) for developing this language. I'll start making this when i have an idea for what a simple program in it will look like.