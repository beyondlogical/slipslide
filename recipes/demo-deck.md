# Builds a single deck, producing build/demo-deck.html and build/demo-deck.md
# These will be overwritten each time your generate the file, so once you have
# a version you'd like to save, it's recommended to move them to decks/

@ file: demo-deck
@ title: Slipslide Demo
@ template: default

# These are all files in the modules/ subdir, .md extension assumed
welcome-to-slipslide
# Comments will be ignored
# glue/ modules are just some useful standard slides
glue/blank
test-1
glue/fin


@ file: demo-deck-2
@ title: Slipslide Demo #2
# @template remains the same until set again
welcome-to-slipslide
test-2
glue/fin

