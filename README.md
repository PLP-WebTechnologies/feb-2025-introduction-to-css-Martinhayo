# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.
 - html file

 - <!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
        <meta name="description" content="computer accessories">
        <link rel="stylesheet" href="css/index.css"
        
        <nav>
            <ul class="items" type="none">
                <li class="items"><a href=index.html>HOME</a></li>
                <li class="items"><a href=about.html>ABOUT ME</a></li>
                <li class="items"><a href=>SERVICES</a></li>
            </ul>
        </nav>
        <title></title>
       
    </head>
    <body>
        <h1>WELCOME TO MY PORTFOLIO WEBSITE</h1>
        <p class="mart">Hi, I'm Martin hayo, a passionate software engineer specializing 
            in Data Analysis and Website development</p>
            <p class="mart">I have a strong foundation in coding, problem solving and creating data driven solutions.
                I am able to transform complex data into meaningful insights and building user friendly web experiences
            </p>
            <br><br>
            <p class="mart"><em>Whether you need to turn your data into business intelligence or develop Website
                from the scratch, I have the experience to help you achieve your goals
            </em></p>
            <img src="IMG20220606075619.jpg" width="300">
<br>
<h2>What I do</h2>
<dl>
    <dt>Data analysis</dt>
    <dd><p>I analyze data to identify patterns and trends, to enable me make data driven decisions and 
        provide meaningful insights from the data., with a goal of providing clear, actionable insights that
        drive business success.
        
    </p></dd>
    <br>
    <dt>Website Development</dt>
    <dd>From concept to deployment, I build dynamic, responsive and visually appealing websites tailored to your needs</dd>
</dl>
<div>
<footer>
    <p>&copy;Martin Hayo @2025</p>
    <p>Contact</p>

</footer>
</div>


    </body>
</html>

css 
body{
    background-color: blueviolet;
    
}
nav{
    display: block;
    background-color:yellow;
    padding: 0px;
    
}
.items{
    display: inline;
    padding-right: 40px;
    border-color: black;
    border-radius: 5px;
    color:blue
}
.mart{
    font-family:Arial, Helvetica, sans-serif;
    font-size: 16px;
    font-weight: bolder;
    color:black
}
img{
    padding-right: 200px;

}

Happy Coding! 💻✨
