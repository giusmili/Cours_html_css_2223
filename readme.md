# Cours html et css

> Introduction au html et css

Exemple de structure html :
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="">
    <title>Cours html</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0" />
    <link rel="stylesheet" href="./css/style.css">
</head>
<body>
    <!-- ici le contenu -->
</body>
</html>
```
## Reset css
```css
    /* reset css */
    html{
    /* 16px mult 100% = 10
    font-size: 16px; /* for size  rem root em */
    font-size: 62.5%;
    }
    body{
        font: 1.6rem sans-serif; /* for font  16px */
        margin: 0;
    }
    h1,
    h2,
    h3,h4,p,ol{ /* contexte css */
        margin: 0;
        padding: 0;
    }
    button{
        background-color: transparent;
        border: 0;
        font-size: inherit;
    }

```