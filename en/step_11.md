## More challenges

Add more animations to make the `#owly` image roll around.

## Step 1

```css
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
```

## Step 2

Try adding some `rainbowGlow` animations to your `myCoolText`.

```css
#myCoolText {
  color: #003366;
  border: 2px ridge #ccffff;
  padding: 15px;
  text-align: center;
  animation-name: rainbowGlow;
  animation-duration: 1.5s;
  animation-iteration-count: infinite;
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

```

## Now run your code

Click **Run** and check that the owl rolls when you hover over it and that `myCoolText` changes colour again and again.
