### 2.Create an external stylesheet and change the color and font size of the heading and paragraph elements from the earlier exercise. Also, change the background color of the body.

* Use different selectors to select different elements.
//ex-2.html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8"/>
        <meta name="viewport" content="width=device-width,initial-scale=1.0"/>
        <title>Hello World</title>
        <link rel="Stylesheet" href="style1.css">
       
    </head>
    <body>
        <h1>Hello World</h1>
        <p class="design">To create the simple structure of the page,</br>we use HTML and in a similar way for styling purpose, we use CSS (Cascading Style Sheet).</br>
        It can be said that if HTML is drywall then CSS is beautiful paint on the walls.So to style any element</br> we need to target   that particular element and define what property of that element need to be styled.</br>
        And for this purpose we have selectors, properties and values in CSS.</p>
       <div id="name">Shalini</div>
    </body>
</html>

//style1.css
h1{
    
    color:blueviolet;
    font-size:80px;
}
.design{
    
    color:brown;
    font-size:36px;
    background-color: cornsilk;
}
#name
{
    color:greenyellow;
    font-size:38px;

}