# Custom Glow Text Effect

Text Glow effect useing only **HTML** & **CSS**


## Installation

Download project or copy/paste by this code.

---

### HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="style.css">

    <title>Text Effect</title>
</head>
<body>
    
<h2><span>I</span>m <span> Jakub200</span></h2>

</body>
</html>
```

---

### CSS

```css
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #000;
}

h2 {
    font-size: 6em;
    font-weight: 500;
    color: #222;
    letter-spacing: 5px;
    cursor: pointer;
}

h2 span {
    transition: 1s;
}

h2:hover span:nth-child(1) {
    margin-right: 10px;
}
h2:hover span:nth-child(1):after {
    content: "'";
}


h2:hover span:nth-child(2){
    margin-left: 40px;
}

h2:hover span{
    color: #fff;
    text-shadow: 0 0 10px #fff,
    0 0 20px #fff,
    0 0 40px #fff,
    0 0 80px #fff,
    0 0 120px #fff,
    0 0 160px #fff;
}
```
---

## Support 

I will be happy if you support me follow on the mem instagram where I give you the regular content regarding WEB Development 
[CLICK HERE --> @jakub200_cz](https://www.instagram.com/jakub200_cz/)
