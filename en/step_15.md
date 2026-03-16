<h2 class="c-project-heading--task">Challenge: glowing links</h2>

--- task ---
Create a “glowing link” style and apply it to links on your website.
--- /task ---

--- task ---
Add a `.niceLinks` class in `styles.css`, then add `class="niceLinks"` to one or more `<a>` links in your HTML.
--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 77
line_highlights: 82, 83, 84, 85, 86, 87, 88, 89, 90
---
img:hover {
  border: 2px dashed Navy;
}

.niceLinks { /* new: link styling for the challenge */
  text-decoration: none;
  color: #FFFAF0;
}
.niceLinks:hover { /* new: glow colour on hover */
  color: #00FF7F;
}

--- /code ---

</div>

<div class="c-project-output">
<p>Your links should change colour when you hover over them (after you add the class to your links in HTML).</p>
</div>

--- task ---
### Test
Add `class="niceLinks"` to a link, refresh the page, and confirm the link colour changes on hover.
--- /task ---


--- task ---

Click **Run** to see the background colour change.

--- /task ---


<div class="c-project-output">

![output screenshot](images/step2.png)

</div>

