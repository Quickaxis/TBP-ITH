# Slow Down Hero Slideshow

Slow down the hero slideshow interval from 500ms to 2000ms (2 seconds per photo) and smooth out the slide transition animation (0.4s to 0.6s).

## Proposed Changes

### [index.html](file:///c:/Users/chitr/Downloads/my%20websites/inthehills/index.html)

#### [MODIFY] [index.html](file:///c:/Users/chitr/Downloads/my%20websites/inthehills/index.html)

- **Slideshow Interval**: Change `setInterval(next, 500);` to `setInterval(next, 2000);` (line 2032).
- **CSS Transition**: Change `transition: transform 0.4s ...` to `transition: transform 0.6s ...` (line 1116).
- **JavaScript Transitions**: Update transition durations in the `next()` function (lines 2023 and 2027) from `0.4s` to `0.6s` to match the CSS.

## Verification Plan

### Manual Verification
1.  Open `index.html` in the browser.
2.  Observe the hero slideshow; verify each photo stays for 2 seconds.
3.  Verify the slide transition is smooth and slightly slower (0.6s) as requested.
