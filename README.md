[README.md](https://github.com/user-attachments/files/32317543/README.md)
# Markdown Speedrun

A browser typing game that teaches Markdown in 26 levels. Each level shows one rule and a target. You type Markdown, watch your preview update as you go, and move on as soon as your output matches.

**Play it:** https://nkostelnik.github.io/markdown-speedrun/

## How it works

- A stopwatch starts on your first keystroke.
- A match earns **+100 points**, plus a speed bonus for solving a level quickly.
- **Show answer** fills in the solution (−50) and waits for you to click **Next level**.
- **Skip level** and **Go back** let you move freely, and your work on each level is saved.
- A pixel sports car drives toward the finish line as you progress.
- At the end you get a cheat sheet of every level.

## What you'll learn

| Basics | Lists & links | Blocks | Extras |
|---|---|---|---|
| Headings | Bulleted lists | Inline code | Tables |
| Paragraphs | Numbered lists | Code blocks | Column alignment |
| Line breaks | Nested lists | Blockquotes | Footnotes |
| Bold / italic | Task lists | Divider lines | Escaping symbols |
| Strikethrough | Links, bare links, reference links | Multi-paragraph list items | Images |

The last level combines everything.

## Run it locally

It's a single file with no build step. Download `index.html` and open it in a browser. You need an internet connection because it loads fonts from Google Fonts and the Markdown renderer ([marked](https://github.com/markedjs/marked)) from cdnjs.

## Notes

- Matching compares the rendered structure, not your exact keystrokes. For example, `*italic*` and `_italic_` both count.
- Images are shown as labeled placeholders instead of loading the picture.
- Footnote support is built into the game, because marked doesn't include it.
