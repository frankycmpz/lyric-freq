# Lyric Frequncy
A Python script that creates a tree map of an artist's most used lyrics.

# A Quick Overview
Looking at an artist's top songs, this script places their 150 most used words onto a tree map. The bigger the block, the larger the frequency. 
Below are some examples.

1. The Strokes

![The Strokes](https://user-images.githubusercontent.com/68876183/117093210-e60dee80-ad25-11eb-8f10-93021c8118a1.png)

2. Grimes

![Grimes](https://user-images.githubusercontent.com/68876183/117093242-0178f980-ad26-11eb-8f44-69dc4fc3c1a4.png)


# Some Required Packages
This program takes advantage of [LyricsGenius](https://lyricsgenius.readthedocs.io/), which makes using Genius' API in Python significantly simpler. There's also a few more dependencies, most notably [Matplotlib](https://matplotlib.org/stable/index.html) and [Squarify](https://github.com/laserson/squarify).

# The Colors
I like to use Coolors.co's gradient palette (an [example](https://coolors.co/gradient-palette/ff1b6b-45caff?number=6)), which let's you get an array of colors through its export option. 


# Programming and Language Choices
This code is not efficient, but in exchange, the code is segmented into easily digestable components, each of which allow you to curate a better tree map.

There's also two filters. One filters generic words; the other checks for some racial slurs, and makes an effort to censor such words from the generated tree map.

# Lastly...

Feel free to use this code or to shoot me a question if there's any.


## Update 10/2021
Generated image has two different features, block size and color. The block size represents how often a word is used by an artist, while the color is still random. I want the color to represent how common/rare of a word that is in general, so I need to build a database. 
