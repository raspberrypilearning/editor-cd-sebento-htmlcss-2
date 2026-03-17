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
line_number_start: 34
line_highlights: 84, 86, 87, 88, 89, 90
---
img {
  border-radius: 20px;
  border: 2px solid White; 
}

img:hover { 
  border: 6px dashed Navy;
}

.topDivider { 
--- /code ---
</div>

--- task ---

Click **Run** and move your cursor over an image. The border should switch to dashed.

--- /task ---


<div class="c-project-output">

![output screenshot](images/step10.gif)

</div>

