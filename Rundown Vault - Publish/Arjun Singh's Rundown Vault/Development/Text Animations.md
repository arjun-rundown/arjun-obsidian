---
title: '"Text Animations"'
draft: false
tags:
  - example-tag
---
 
The rest of your content lives here. You can use **Markdown** here :)
# Related Notes
#### Text format with different colors 
```
Innovative<span class="cyan">. <span class="white">Collaborative<span class="cyan">. <span class="white">Strategic
```

#### HTML for Auto Typing Text 
```
<script src="https://unpkg.com/typed.js@2.0.132/dist/typed.umd.js"></script>
<div class="autotyping">MOST <span class="typing_text"></span></div>

<script>
//typing text animation script
var typed = new Typed(".typing_text", {
strings: ["Innovative", "Strategic", "Collaborative"],
typeSpeed: 100,
backSpeed: 60,
loop: true,
cursorChar: '|️',
});
</script>

<style>
.autotyping{
font-family: 'Poppins', serif;
color: #FFF;
font-size:2.5em;
font-weight: 400;
}
.autotyping>span{
color: #0B7F7D;
font-size:1.2em;
font-weight: 700;
}
/*Shrinking for tablet*/
@media (min-width: 481px) and (max-width: 768px) {
.autotyping{
font-size:2.0em;
font-weight: 800;
}
.autotyping>span{
font-size:1.2em;
font-weight: 700;
}
}
/*Shrinking for mobile*/
@media (max-width: 480px) {
.autotyping{
font-size:1.9em;
font-weight: 400;
text-align: center;
}
.autotyping>span{
font-size:1.1em;
font-weight: 700;
}
}
</style>
```

# Research

# Reference Links


# Reference Videos