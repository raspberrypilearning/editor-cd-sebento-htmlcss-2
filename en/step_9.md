<h2 class="c-project-heading--task">Add hover effects</h2>

Make the website feel interactive by changing styles when the mouse hovers over an element.

<h2 class="c-project-heading--explainer">Follow these instructions</h2>

## Step 1

Add a border to all images, then add an `img:hover` rule to change the border style.


<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 34
line_highlights: 38-40
---
img {
  border-radius: 20px;
}

img:hover { 
  border: 6px dashed Navy;
}

.topDivider { 
--- /code ---
</div>

## Step 2

Click **Run** and move your cursor over an image. The border should switch to dashed.



<div class="c-project-output">

![output screenshot](images/step10.gif)

</div>

## Now run your code

Click **Run**, move your cursor over an image, and check that its border changes to a dashed line.
