<h2 class="c-project-heading--task">Add hover effects</h2>

--- task ---
Make the website feel interactive by changing styles when the mouse hovers over an element.
--- /task ---

--- task ---
Add a border to all images, then add an `img:hover` rule to change the border style.
--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 80
line_highlights: 84, 86, 87, 88, 89, 90
---
img {
  border-radius: 20px;
  border: 2px solid White; /* new: default border */
}

img:hover { /* new: hover effect */
  border: 2px dashed Navy;
}
--- /code ---

</div>

<div class="c-project-output">
<p>Move your cursor over an image: the border should switch from solid to dashed.</p>
</div>

--- task ---
### Test
Hover over an image and confirm the border changes.
--- /task ---



--- task ---

Click **Run** to see the background colour change.

--- /task ---


<div class="c-project-output">

![output screenshot](images/step2.png)

</div>

