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

## License

Licensed under the BSD 0-Clause license, available in the LICENSE.TXT file and reproduced below.

> THE SOFTWARE IS PROVIDED “AS IS” AND THE AUTHOR DISCLAIMS ALL
WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES
OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE
FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY
DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN
AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT
OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

Software copyright Piper Thunstrom 2024

## TODO

1. Mobile layout. Currently optimized for desktop use.
2. Clock Export
3. Clock Import