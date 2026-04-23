<h2 class="c-project-heading--task">Create a reusable text box</h2>

Make a class that you can reuse to style text boxes in your site.

<h2 class="c-project-heading--explainer">Follow these instructions</h2>

## Step 1

Click on the `conservation.index` file.

## Step 2

Add the `stylishBox` class to **all** the sections. The first one is shown below.



<div class="c-project-code">
--- code ---
---
language: html
filename: conservation.html
line_numbers: true
line_number_start: 28
line_highlights: 31
---
        Various kinds of work are carried out in Ireland in order to protect bird species.
      </p>

      <section class="stylishBox">
        <h2>Research and monitoring</h2>
        <p>
          An essential part of bird conservation is monitoring and recording
--- /code ---

</div>

## Step 3

Add CSS code so that you have the look you want.


<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 41
line_highlights: 45-52
---
  border-top-color: #9999ff;
  padding-bottom: 20px;
}

.stylishBox {
  background-color: #87CEFA;
  color: #A52A2A;
  border-style: solid;
  border-width: 2px;
  border-color: #F5FFFA;
  border-radius: 10px;
}
--- /code ---

</div>

## Step 4

Click **Run** to see the changes. Experiment with the colours, `border-radius` until you get the look you want.



<div class="c-project-output">

![output screenshot](images/step4.png)

</div>

## Now run your code

Confirm the observable result.
