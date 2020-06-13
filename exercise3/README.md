## 1. Create a simple page with the heading 'Hello World'.

<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8"/>
        <title>Hello World</title>
       
    </head>
    <body>
        <h1>HELLO</h1>
        <p>Here you go !</p>
        <a href="About.html">Click me</br></a>
        <a href="https://webrux.in/"target"_blank">Webrux</a>
    </body>
</html>
//About.html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8"/>
        <title>Hello</title>
    </head>
    <body>
        <h2>Webrux</h2>
        <p>Here you can find generic information about webrux </p>
    </body>
</html>

Below heading Provide two links. Say A. About and B. WebWurx: https://webwurx.in/.

A. Use relative to connect to about page.

B. Use absolute path to connect to the google website and open in a new window or tab. - 10 mins (Mandatory)

## 2.Create a website with multiple pages(home, about, contact).
//3(b).html
!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8"/>
        <meta name="viewport" content="width=device-width,initial-scale=1.0"/>
        <link rel="Stylesheet" href="Aboutmestyle.css">
        <title>HELLO</title>
    </head>
    <body id="homepage">
        <h2>Hi I am Shalini Kumari</h2>
        <p>I created this web page so that I can help</br>you in any form.I know many of you are civil Service Aspirants.</br>I know
        the biggest problem you face is how and which subject to choose for optional paper.</br>Since I am also preparing for UPSC, I 
       thought to help you all my dear friend.</br> So here are some information about me</p>
       <a href="Aboutme.html">Who am I?</br></a>
       <a href="home.html">Where am I from?</br></a>
       <a href="Contact.html">How can you Contact me?</a>
     </body>
</html>

//Aboutme.html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8"/>
        <meta name="viewport" content="width=device-width,initial-scale=1.0"/>
        <link rel="StyleSheet" href="Aboutmestyle.css">
    </head>
    <body class="aboutstyle">
        <h2>Who am I ?</h2>
        <p>I am Shalini Kumari, Shalini for short. I am a BTECH student</br>just enrolled to second year. I am from Indira Gandhi Delhi Technical University 
        for Women, IGDTUW for short. </br> I have learnt C, C++ and Java. I have done my Schooling from DAV public School</br>
        I am also a civil Service Aspirant. Well I think this is all about me.</p>
    
        <a href="ex-3(b).html">Home page</br></a>
        <a href="home.html">Where am I from?</br></a>
        <a href="Contact.html">How can you Contact me?</a>
 </body>
</html>
//Aboutmestyle.css
h2{
    color: brown;
    background-color: pink;
    font-size: 70px;
}
#homepage
{
    color: crimson;
    background-color:lightblue;
    font-size: 40px;
}
.aboutstyle{
    color: blue;
    background-color: pink;
    font-size: 30px;

}


#styleaddress
{
    color: orange;
    background-color: gainsboro;
    font-size: 30px;
}
#contactstyle
{
    color: black;
    background-color: yellowgreen;
    font-size: 30px;
}
//home
DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8"/>
        <meta name="viewp<!ort" content="width=device-width,initial-scale=1.0"/>
        <link rel="Stylesheet" href="Aboutmestyle.css">
    </head>
    <body id="styleaddress">
        <h2>Where am I from ?</h2>
        <p>
            I am basically from Muzaffarpur, a district in Bihar. So, Bihar is my Birth-place</br> and I am proud of that. I have lived in
            Kota Rajasthan for 1 year while </br> I was preparing for IIT, which I could not make to  happen reality.Currently I live in</br>
             DELHI.
        </p>
        <a href="ex-3(b).html">Home page</br></a>
        <a href="home.html">Where am I from?</br></a>
        <a href="Contact.html">How can you Contact me?</a>
    </body>
</html>


//contact
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8"/>
        <link rel="Stylesheet" href="Aboutmestyle.css">
    </head>
    <body id="contactstyle">
        <h2>How can you Contact me ?</br></h2>
        <p>Contact no- 876543210</br>
        Alternate Contact no-123456789</p>
        <a href="mailto: skarmintome@gmail.com">Email-id - Send Email</br></br></a>
        <a href="ex-3(b).html">Home page</br></a>
        <a href="home.html">Where am I from?</br></a>
        <a href="Contact.html">How can you Contact me?</a>
    </body>
</html>

- Each page must be having a navigation link to connect to the other pages of the website.
- And each page must have one heading and one paragraph.
- There must be a different background color for each page.
- Use external stylesheet to apply styles. - 25 mins (Mandatory)
