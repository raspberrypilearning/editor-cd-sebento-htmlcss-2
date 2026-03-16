<h2 class="c-project-heading--task">Make an image resize with the window</h2>

--- task ---
Prepare an image so you can control its size in CSS instead of using `width="..."` in HTML.
--- /task ---

--- task ---
In `index.html`, remove the `width` attribute from the barn owl image and give it `id="owly"`.
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
	    
	    <img id="owly" src="barn-owl.jpg" alt="A barn owl" /> <!-- id added, width removed -->
      <p>
        Birds are in decline for lots of reasons.
--- /code ---

</div>

<div class="c-project-output">
<p>The picture may change size slightly (depending on your CSS so far), but the big change is that CSS will control it next.</p>
</div>

--- task ---
### Test
Refresh the page and confirm the image still appears.
--- /task ---


--- task ---

Click **Run** to see the background colour change.

--- /task ---


<div class="c-project-output">

![output screenshot](images/step2.png)

</div>

