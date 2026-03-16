<h2 class="c-project-heading--task">Animate an element with CSS</h2>

--- task ---
Create a simple CSS animation and apply it to an element.
--- /task ---

--- task ---
Update `#owly` so it animates, then add a `@keyframes` animation at the end of `styles.css`.
--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 71
line_highlights: 75, 77, 78, 79, 122, 123, 124, 125, 126, 127
---
#owly {
  width: 100px; /* changed: fixed start width for the animation */
  border-radius: 100%;
  animation-name: myFirstAnimation; /* new animation settings */
  animation-duration: 2s;
  animation-iteration-count: 1;
}

...
@keyframes myFirstAnimation { /* new animation */
  from {
    width: 100px;
  }
  to {
    width: 300px;
  }
}
--- /code ---

</div>

<div class="c-project-output">
<p>When you refresh the page, the image should grow from 100px to 300px.</p>
</div>

--- task ---
### Test
Refresh `index.html` and watch the image animate once.
--- /task ---


--- task ---

Click **Run** to see the background colour change.

--- /task ---


<div class="c-project-output">

![output screenshot](images/step2.png)

</div>

