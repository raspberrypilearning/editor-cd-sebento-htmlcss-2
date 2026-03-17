<h2 class="c-project-heading--task">Challenge: glowing links</h2>

--- task ---

Create a “glowing link” style and apply it to links on your website.

--- /task ---

--- task ---

Add `class="niceLinks"` to any link on your site. It will need to be in the `<a>`

--- /task ---

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 77
line_highlights: 82
---
	<ul>
				<li>Home</li>
				<li><a class="niceLinks" href="birds.html">Protected Birds</a></li>
				<li><a class="niceLinks" href="conservation.html">Conservation</a></li>
				<li><a class="niceLinks" href="sanctuaries.html">Bird Sanctuaries</a></li>
			</ul>

--- /code ---

--- task ---

Add a `.niceLinks` class in `styles.css`.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 77
line_highlights: 82
---
img:hover {
  border: 2px dashed Navy;
}

.niceLinks { 
  text-decoration: none;
  color: #FFFAF0;
}

.niceLinks:hover { 
  color: #00FF7F;
}
--- /code ---
</div>

--- task ---

Click **Run** to see your links should change colour when you hover over them.

--- /task ---


<div class="c-project-output">

![output screenshot](images/step11.png)

</div>

