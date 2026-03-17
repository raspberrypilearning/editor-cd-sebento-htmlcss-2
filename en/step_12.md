<h2 class="c-project-heading--task">More challenges</h2>

--- task ---

Add more animations to make the `#owly` image roll around.


<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: false
---
#owly:hover {
  
  animation-name: rollOver;
  animation-duration: 1s;
  animation-iteration-count: 1;
}

@keyframes rollOver {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(-360deg);
  }
}
--- /code ---
</div>

--- /task ---


--- task ---

Try adding some `rainbowGlow` animations to your `myCoolText`.

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: false
---
#myCoolText {
  color: #003366;
  border: 2px ridge #ccffff;padding: 15px;
  text-align: center;animation-name: rainbowGlow;
  animation-duration: 1.5s;
  animation-iteration-count: 1;
  }

@keyframes rainbowGlow {
  0% {
    color: #FFD700;
    }
  50% {
    color: #663399;
    }
  100% {
    color: #FFD700;
    }
  }

--- /code ---
</div>

--- /task ---


