# Distraction Maze: an attentional control simulation

A browser-based classroom activity. Students solve mazes under three conditions (**no distractions**, **auditory distractions**, and **auditory + visual distractions**), compare their results, and answer four reflection questions. They then copy everything into a Canvas assignment.

**▶️ Play it:** https://jon-dyhr.github.io/distraction-maze/

**📓 Notebook version:**
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jon-dyhr/distraction-maze/blob/main/Distraction_Maze.ipynb)

> This is a classroom awareness activity, not a clinical or diagnostic tool. It can only hint at what living with ADHD is like.

## What students do

| Trial | Maze | Condition |
|---|---|---|
| 1 | Small | No distractions |
| 2 | Medium | No distractions |
| 3 | Small | Auditory |
| 4 | Medium | Auditory |
| 5 | Small | Auditory + visual |
| 6 | Medium | Auditory + visual |
| 7–9 *(optional)* | Large | None, auditory, auditory + visual |

- **Auditory:** background narration, random sound clips and notification dings.
- **Auditory + visual:** the same sounds, plus pop-up notifications, moving shapes, stray "thought" bubbles and a tempting flashing button.
- **Fair comparison:** within each size, all three mazes are the same maze, flipped or rotated. They have the same route length and the same dead ends, so differences come from the distractions rather than luck. Because the calm round always comes first, a little practice effect is possible.
- **Optional large mazes:** students can choose them before they begin, or add them from the results screen.
- **Saved progress:** results and answers are saved in the student's browser, so a refresh or a closed tab doesn't lose their work. This only works on the same computer and browser.

## Submitting to Canvas

On the results screen, students:

1. Type answers to the four reflection questions.
2. Click **Copy results & answers**.
3. Open the Canvas assignment, click **Start Assignment**, choose **Text Entry**, and paste with Ctrl+V on Windows or Chromebook, or ⌘+V on Mac. The results paste as a table, followed by the questions and answers.
4. Click **Submit Assignment**.

If copying is blocked, they click **Download results** and submit the `.txt` file using **File Upload**.

**Canvas assignment settings:** set *Submission type* to **Online**, and tick both **Text Entry** and **File Upload**.

## For teachers

### Distraction intensity

Add `?level=low`, `?level=medium` (the default) or `?level=high` to the link. Add `&large=1` to tick the optional large mazes in advance. For example:
`https://jon-dyhr.github.io/distraction-maze/?level=high`

### Embed in a Canvas page

In the page editor, switch to the HTML editor (`</>`) and paste:

```html
<iframe src="https://jon-dyhr.github.io/distraction-maze/"
        width="100%" height="900" style="border:0;"
        allow="autoplay; clipboard-write" allowfullscreen
        title="Distraction Maze"></iframe>
```

## Files

| File | What it is |
|---|---|
| `index.html` | The whole activity in one file, including the sounds. |
| `Distraction_Maze.ipynb` | A notebook version for Google Colab or Jupyter. |
| `README.md` | This page. |

## Credits and license

Adapted from [ADHD_simulator](https://github.com/sayanthsai/ADHD_simulator) by **sayanthsai**, which is released under CC0 1.0. This version reuses the original project's narration and sound clips and its moving-shape distractions, and adds the maze, the three-condition design, extra distraction types and the reflection questions.
