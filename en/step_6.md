<h2 class="c-project-heading--task">Style paragraph text</h2>

--- task ---

Add `id="myCoolText"` to the first paragraph, and make a new style.

--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Tip

- An ID (#) is used for one specific element.
- It should only be used once on a page.
- It lets you target that exact element in CSS.

</div>


--- task ---

Add the `id` below in the `index.html` file.

--- /task ---

<div class="c-project-code">
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 22
line_highlights: 24
---
		<section>
			<h1>Bird Conservation</h1>

			 <p id="myCoolText">
				This website is about bird conservation.
			</p>

			<p>Explore the links above to learn more</p>
		</section>
--- /code ---
</div>

--- task ---

In `styles.css`, add a `#myCoolText` block.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 52
line_highlights: 58
---
  border-color: #F5FFFA;
  border-radius: 10px;
}

#myCoolText { 
  color: #003366;
  border: 2px ridge #ccffff;
  padding: 15px;
  text-align: center;
}
--- /code ---
</div>

--- task ---

Click **Run** to see the paragraph has a new style.

--- /task ---


<div class="c-project-output">

![output screenshot](images/step2.png)

</div>