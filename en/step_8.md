<h2 class="c-project-heading--task">Style the image</h2>

--- task ---

Change the front page image with css.

--- /task ---

--- task ---

First, in `index.html` remove the `width` attribute from the barn owl image and give it `id="owly"`.
--- /task ---

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 25
line_highlights: 29
---
			<p>Explore the links above to learn more</p>
		</section>

	<img id="owly" src="barn-owl.jpg" alt="A barn owl" /> 
		
		<section>
			<p>Threats to birds:</p>
			<ol>
--- /code ---

</div>


--- task ---

In `styles.css`, add a `#owly` rule that sets its width to `50%` and changes the `border-radius` so it is a round shape.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 67
line_highlights: 73, 74, 75, 76, 77, 78
---
#frontPage {
  background: #48D1CC;
  background: linear-gradient(#fea3aa, #f8b88b, #faf884, #baed91, #baed91, #b2cefe, #f2a2e8, #fea3aa);
}

#owly { 
  width: 50%;
  border-radius: 100%;
}
--- /code ---

</div>

--- task ---

Click **Run** to test. Move the output window and see the image change size.

--- /task ---


<div class="c-project-output">

![output screenshot](images/step8.png)

</div>