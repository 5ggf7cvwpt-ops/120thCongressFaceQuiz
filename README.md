# 120th Congress Face Quiz

A multiple-choice quiz for learning the faces of the 120th Congress House newcomers (members-elect and candidates in undecided races as of Nov. 7, 2026). Portraits come from the 120th New Member Orientation cheat sheet.

Everything is in one self-contained file, `index.html`: no build step and no server code. Open the GitHub Pages link in a browser, or on iPhone use Share → Add to Home Screen.

Live site: https://5ggf7cvwpt-ops.github.io/120thCongressFaceQuiz/

## Put the quiz on a Squarespace (or any) page

Add a **Code** block to the page and paste:

```html
<div id="cfq"></div>
<script src="https://5ggf7cvwpt-ops.github.io/120thCongressFaceQuiz/embed.js"></script>
```

The quiz shows a loading screen while the 124 photos load from `photos/`, then runs right on the page. On Squarespace, scripts in Code blocks need the Core plan or higher.
