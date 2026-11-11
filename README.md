# Distraction Maze: a focus simulation

A browser-based classroom activity. Students solve two mazes of equal difficulty, first in calm and then with distractions (sounds, pop-up notifications, moving shapes and stray "thoughts"). They then compare their results and reflect on how distraction affected their focus.

**▶️ Play it:** https://jon-dyhr.github.io/distraction-maze/

**📓 Open the notebook version in Google Colab:**
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/distraction-maze/blob/main/Distraction_Maze.ipynb)

> This is a classroom awareness activity, not a clinical or diagnostic tool. It can only hint at what living with ADHD is like.

## How to play

1. Turn your sound on 🎧.
2. Choose a maze size and distraction level, then click **Start round 1**.
3. Move the blue dot to the gold star using the **arrow keys** or **W A S D**. On a phone or tablet, use the on-screen arrows or swipe.
4. After round 2, read your results, answer the reflection questions, and click **Copy results** to paste them into your assignment.

## For teachers

### Preset the settings with the link

Add these to the end of the link to choose the settings for your class:

| Setting | Options | Example |
|---|---|---|
| `size` | `small`, `medium`, `large` | `?size=small` |
| `level` | `low`, `medium`, `high` | `?level=high` |
| `skipcalm` | `1` skips the calm round | `?skipcalm=1` |
| `lock` | `1` stops students changing the settings | `?lock=1` |

Combine them with `&`, for example:
`https://jon-dyhr.github.io/distraction-maze/?size=medium&level=high&lock=1`

### Embed it in a Canvas page

In the Canvas page editor, switch to the HTML editor and paste:

```html
<iframe src="https://jon-dyhr.github.io/distraction-maze/?size=medium&level=medium"
        width="100%" height="900" style="border:0;"
        allow="autoplay; clipboard-write" allowfullscreen
        title="Distraction Maze"></iframe>
```

## Files

| File | What it is |
|---|---|
| `index.html` | The whole activity in one file, including the sounds. |
| `Distraction_Maze.ipynb` | A notebook version for Google Colab or Jupyter, with a reflection cell. |
| `README.md` | This page. |

## Credits and license

Adapted from [ADHD_simulator](https://github.com/sayanthsai/ADHD_simulator) by **sayanthsai**, which is released under CC0 1.0. This version reuses the original project's narration and sound clips and its moving-shape distractions, and adds the maze, the calm-versus-distracted comparison, extra distraction types and the reflection questions.
