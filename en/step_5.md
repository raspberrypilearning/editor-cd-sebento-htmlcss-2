<h2 class="c-project-heading--task">Style paragraph text</h2>

Add the `id` in the `index.html` file.

<h2 class="c-project-heading--explainer">Follow these instructions</h2>

## Step 1

### Tip

<div class="c-project-callout c-project-callout--tip">

- An ID is used to identify one specific element on a page.
- In HTML, it is written as id="name".
- In CSS, you target it with #name.
- Each ID value should be unique within the page.

</div>

<div class="c-project-code">
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 22
line_highlights: 24
---
			<h1>Bird Conservation</h1>

			<p id="myCoolText">
				This website is about bird conservation.
			</p>
--- /code ---
</div>

## Step 2

In `styles.css`, add a `#myCoolText` selector.


<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 50
line_highlights: 54-59
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

## Step 3

Click **Run** to see the paragraph has a new style.



<div class="c-project-output">

![output screenshot](images/step6.png)

</div>

## Now run your code

Click **Run** and check that the paragraph now has its new border, padding, and centred text.
