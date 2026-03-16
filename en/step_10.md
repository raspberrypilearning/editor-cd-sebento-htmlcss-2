<h2 class="c-project-heading--task">Add a gradient and try dev tools</h2>

--- task ---
Add a gradient background for the home page and tweak a style you can also experiment with in dev tools.
--- /task ---

--- task ---
In `styles.css`, add a `#frontPage` gradient and give `#myCoolText` a background colour.
--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 1
line_highlights: 6, 7, 8, 9, 10, 11, 70
---
body {
  background-color: #7B68EE;
    font-family: "Helvetica", sans-serif;
    color: purple;
}

#frontPage { /* new: gradient only on the home page */
  background: #48D1CC;
  background: linear-gradient(#fea3aa, #f8b88b, #faf884, #baed91, #baed91, #b2cefe, #f2a2e8, #fea3aa);
}

 h1 {
    color: Azure;
    font-family: "Times New Roman", serif;
  }
...
#myCoolText {
  color: #003366;
  border: 2px ridge #ccffff;
  padding: 15px;
  text-align: center;
  background-color: #660066; /* new: easy to experiment with in dev tools */
}
--- /code ---

</div>

<div class="c-project-output">
<p>The home page should now have a colourful gradient background, and the bordered paragraph should have a filled background.</p>
</div>

--- task ---
### Test
Refresh `index.html` and confirm you can see the gradient background on the home page.
--- /task ---


--- task ---

Click **Run** to see the background colour change.

--- /task ---


<div class="c-project-output">

![output screenshot](images/step2.png)

</div>

