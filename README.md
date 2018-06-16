# Live Video Processing with Max/MSP/Jitter

These are a series of Max patches intended to accompany an introductory Jitter workshop that I taught at ITP Camp 2018. The workshop syllabus and these patches are heavily based on Matt Romein's [Live Image Processing and Performance](https://github.com/mromein/lipp_itp_2018) NYU ITP course.

## Syllabus (Rough)

This is a ton of material, and it's possible that we won't get through all of it in the allotted time. That said, anything that we don't get to should be covered in the patches in this repo.

### Intro

- Why Max?
- Max vs. similar tools

### Max Basics

- layout of the patcher window
- locking and unlocking a patch
- Max console
- objects, messages, and comments
- anatomy of an object
  - name
  - arguments
  - inlets (hot vs. cold) and outlets
- data types
  - bang
  - int
  - float
  - symbol
  - list
  - audio
  - matrix
- buttons and toggles
- metro
- pack vs. pak, unpack
- order of operations
  - right to left
  - bottom to top
  - depth-first
  - trigger

### Video in Jitter

- movie playback
  - reading a file into jit.movie
  - jit.window vs. jit.pwindow
  - jit.movie and bangs
  - qmetro 33 for 30fps playback
  - reading from a directory of video files with umenu
- jit.grab
- jit.brcosa
  - $1 message syntax
- the Jitter matrix
  - planes (ARGB not RGBA)
  - data types (char vs. float32)
  - dimensions
  - jit.cellblock
  - jit.unpack
- building a random video player

### Effects
- jit.lumakey
- jit.chromakey
- jit.rota
- video feedback
- jit.matrixset

### Interfaces
- presentation mode
- presets

## Resources & Tutorials

- Matt Romein also has a really excellent series of [Youtube tutorials](https://www.youtube.com/channel/UCPWF2lJ4E_qVG7HrWRiGnhA/playlists) that cover the topics discussed in this workshop and more.
- The built-in tutorials in Max, found by navigating to Help -> Reference and then clicking on the Home icon.
- Sam Tarakajian's [Delicious Max Tutorials](https://www.youtube.com/playlist?list=PLD45EDA6F67827497)
- Federico Foderaro's [Amazing Max Tutorials](https://www.youtube.com/watch?v=5mLAxACSPLU&list=PLRc5WfOZXC4ktigvYCDhek0475hizrnM5)
- Darwin Grosse's online book [20 Objects](http://www.darwingrosse.com/20Objects/)
- Andrew Benson's Jitter Recipes
  - [Book 1 (1 - 13)](https://cycling74.com/tutorials/jitter-recipes-book-1/)
  - [Book 2 (14 - 25)](https://cycling74.com/tutorials/jitter-recipes-book-2/)
  - [Book 3 (26 - 39)](https://cycling74.com/tutorials/jitter-recipes-book-3/)
  - [Book 4 (40 - 49)](https://cycling74.com/tutorials/jitter-recipes-book-four)
  - [Recipe 50](https://cycling74.com/tutorials/recipe-50-branching)
  - [Recipe 51](https://cycling74.com/tutorials/recipe-51-scrunch)
  - [Recipe 52](https://cycling74.com/tutorials/recipe-52-dirtysignal)
  - [Recipe 53](https://cycling74.com/tutorials/recipe-53-flyover)
  - [Recipe 54](https://cycling74.com/tutorials/recipe-54-zoom)
  - [Recipe 55](https://cycling74.com/tutorials/recipe-55-mirrorhouse)
  - [Recipe 56](https://cycling74.com/tutorials/recipe-56-relief)
- [The Cycling '74 Forums](https://cycling74.com/forums/page/1)
- [Max/MSP](https://www.facebook.com/groups/961274147281218/) and [Jitter (C74)](https://www.facebook.com/groups/maxmspjitter/) Facebook groups
- [Programming Max: Structuring Interactive Software for Digital Arts](https://www.kadenze.com/courses/programming-max-structuring-interactive-software-for-digital-arts-i/info) Kadenze course

