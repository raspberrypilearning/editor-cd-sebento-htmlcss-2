<h2 class="c-project-heading--task">Animate parts of your site</h2>

Create a CSS animation and apply it to an element.

<h2 class="c-project-heading--explainer">Follow these instructions</h2>

## Step 1

Update `#owly` so it animates, then add a `@keyframes` animation at the end of `styles.css`.


<div class="c-project-code">
--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 66
line_highlights: 69-82
---
#owly {
  width: 50%;
  border-radius: 100%;
  animation-name: myFirstAnimation;
  animation-duration: 2s;
  animation-iteration-count: 1;
}

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

## Step 2

Click **Run**, the image should grow from 100px to 300px.



<div class="c-project-output">

![output screenshot](images/step9.gif)

</div>

## Now run your code

Click **Run** and check that the image grows from small to large.
