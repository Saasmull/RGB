# RGB

First define your HTML tag with the class `RGB`:
```HTML
<div class="RGB">YOUR_TEXT</div
```
Then chose the declaration for the element with the class `RGB` to your CSS:
```CSS
.RGB{
   background-color: red;
   width: 100%;
   height: 100%;
   animation-name: RGB;
   animation-duration: 20s;
   animation-iteration-count: infinite;
}
```
At the last add the animation to your CSS like this:
```CSS
@keyframes RGB{
   0%{background-color:red;}
   33.3%{background-color:yellow;}
   66.6%{background-color:blue;}
   100%{background-color:red;}
}
```

[Here](https://saasmull.github.io/info/repo/rgb/example.html) can you view this example.
