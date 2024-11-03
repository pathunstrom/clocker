# Clocker

Clocker (Clock Tracker) is a digital clock tracker for Forged in the Dark games.
It is a single page application with no dependencies.
You can use it locally by downloading index.html and opening it with your web browser of choice.
Or you can check it out on github pages.

If you have python on your computer you can also go the directory with index.html and then run:

    python3 -m http.server
    python3 -m webbrowser http://localhost:8000

## Features

A simple form on the left side of the screen allows you to enter a title (optional),
a number of segments,
and whether the clock is "positive" or "negative".

This creates a clock card.
Hit increase to add to the segments.
Press Reduce to erase a segment.
When you're done with a clock, hit delete to remove it from the ui.

## TODO

1. Mobile layout. Currently optimized for desktop use.
2. Clock Export
3. Clock Import