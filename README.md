<div align="center">
    <h1>Bubble background</h1>
    <img height="300px" src="./assets/BubbleDemonstration.png">
</div>

<br/>

# What's that
Bubble background is a tiny library for make a bubble effect in the canvas, the code is resumed in a class that just need be instantiated receiving the correct arguments. The bubble effect is like in the image above, circles growing up and shirinking until disappear from canvas, the background color, bubble's color, bubble's radius and bubble's spawn rate is programmable.


# How to use
First of all, you need import the BubbleAnimation.js to your .html file and then run the following commands in a script above:

```html
    <!--Importing the animation file-->
    <script src="./BubbleAnimation.js"></script>
    <script>
        // Get canvas element
        let canvas = document.getElementById("target_canvas");

        /* Call the animation class properly, passing
        the canvas element, all possible colors of bubbles,
        max bubble's radius, growing step of bubbles, bubbles's
        spawn rate and then the background color*/
        new BubbleAnimation(target, ["#47a025", "#ffffff", "#9000b3", "#007ea7"], 20, 0.2, 200, "#1d1e2c");

        // The program should run now :)
    </script>
```