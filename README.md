# 10.responsive-image
## program:
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="#styles.css">
    <title>Document</title>
    <style>
body{
    background-color: #777;
    background-image: url("https://gratisography.com/wp-content/uploads/2024/01/gratisography-cyber-kitty-800x525.jpg");
    background-repeat:no-repeat;
    background-position: center;
        
}
h2{
    background-color: blueviolet;
    display: grid;
    place-items: center;
    color:white;

}
@media (max-width:111px) {
    body{
        image-resolution: 1rem;
    }
    h2{
        font-size: 1.5rem;
    }  
}
    </style>

    
    
</head>
<body>
    <h2>background example in CSS</h2>

</body>
</html>
```
#output:
![WhatsApp Image 2024-07-14 at 22 38 57_5abc8a7f](https://github.com/user-attachments/assets/a7e1bde5-4135-4bfd-a6b2-ffb3ef68d523)
