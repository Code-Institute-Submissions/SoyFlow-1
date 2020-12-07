# SoyFlow
![ScreenShot](/assets/images/SOYFLOW.jpg)


## Project description

This website is dedicated to users who dislike Dominican music and culture, since on other platforms you can get content, but you should know what to look for, we offer you information already prepared and ordered in such a way that with the simple fact of reading You can meet new artists and styles of music that will make you shake your hips. This website collects information from other platforms and organizes it especially for you.

Soy Flow is a static page, where it only shows the necessary data; its internal structure is designed only with HTML and CSS files.

## Navigation:
    SoyFlow contains a navigation bar composed of 3 simple tabs:

 * Home: refers to the index.HTML file; Like all index, we give ourselves the task of proudly displaying the symbol of I am flow, then we show 3 columns where we display information that summarizes the Dominican folklore. Dominican music describes what the Dominican musuca is about. As everything that begins has its history, the history of Dominican music is not left behind, that's what the second column is about, a small summary of the history of Dominican music. and the classical music with which the Dominican Republic identifies, we talk about merengue, which was known throughout the world and in these times when we talk about merengue we talk about the Dominican Republic.

 * Genres: The musical genres that predominate in the Dominican Republic; We show a menu on the left side that breaks down the titles of all the musical genres that predominate in the Dominican Republic. in the other part it will show the detailed information of the selected genre.

 * Artist: it is the third tab of this website, it is composed of two main columns, one of which displays a list of artists organized by gender, and the other column shows detailed information about each artist in particular.

 * In the latter at the end of each artist biography information we have left a table which is composed of 3 columns, the first is the subject of the altista album, in the second column we show the years in which this tree was launched and the third we show a link icon that will take you to the youtube channel so you can taste said album.

## Design:
the index of the front-end; at the top it has a very cute navbar; black with gray lettering; followed by this navbar we leave the soyflow logo with a minimum height of 400px; and followed by this with a container that has three columns.

the demar html files have the navbar and two columns within that column; In the left column we show the menus, in the other part of the column we show the details of the information of the musical genre or the artist.

the footer: it has two central columns in the first we will find the designer's information and in the second column we show two very cute icons that redirect us to the social networks that the page is using.

## Color scheme and typography:
    The predominant color on this website is black.
* Navbar: has a black background color in hexadecimal (# 000000) with light gray letters. and the font that this navbar uses is the font-family: sans-serif;
* Background-image: the background image the musical sun symbol, in gold color, with a well-known cartoonnetwork figure as jonny vrabo, this character in white and also legrates them.

* For the columns that have detailed information, we leave a white background with black letters since most of the users feel comfortable when reading; keeping the same font the font-family: sans-serif, font-family: monospace, monospace;


## Language Used

CSS3 -Cascading StyleSheets-: We use the css language to order and decorate our website; We have two .css files located in the assets/css directory;
- normalize.css :here I have placed the styles of the parts of my website such as body, div, aside, footer etc ..; the normalization of the type of letters the implementation of the background image etc. This file makes the connection to the html files through this link (<link rel = "stylesheet" href = "/ SoyFlow / assets / css / normalize.css">
) in the head of the html code.

- skeleton.css :This css file has the codes responsible for making it visible responsive on any device that the user uses. The code responsible for making this possible is @media (min-width :) that it has since it expands from 400px to 1200px   <link rel="stylesheet" href="/SoyFlow/assets/css/skeleton.css">

HTML -HyperText Markup Language-:we currently have 3 main html files; the index.html, genres.html and artstis.html; The other html files are located in the genres and artists folders, these files correspond to the tabs with the same name, we are structured this website in that way to make it simpler.

## Git and Github
### Github
I created a github repository in github
I get a name "SoyFlow"
I keep public repository
### github pages
I clicked in settings options, in the options Github pages I selecte branch master and save; this is the link for github pages https://jansgreen.github.io/SoyFlow/index.html
### Git
Before start the app, I created the directory SoyFlow.
I did git init.
I created my file readme.md
I did git remote add origin https://github.com/jansgreen/soyflow.git to add the repository remote.
Afther my web is ready I make a git push origin master. to save in github repository.

## link and library

**bootstrap 4.5.3**
- we use the bootstrap library to give better visibility to the design of our website; we have used the bootstrap dns that we put in the head of the html file.
  * <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
  *   <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js"  integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx"
    crossorigin="anonymous"></script>

**fonts.googleapis.com**
- to improve the experience of our lyrics in browsers; we have made use of google letters; Like every link, we have also pasted it in the head of our website
    *   <link href="//fonts.googleapis.com/css?family=Raleway:400,300,600" rel="stylesheet" type="text/css">

**CSS links**
- As we have already covered this topic previously we show the two connections of the css files to the html files, these were also placed in the head of each html code
  * normalize.css <link rel="stylesheet" href="/SoyFlow/assets/css/normalize.css">
  * skeleton.css <link rel="stylesheet" href="/SoyFlow/assets/css/skeleton.css">

**Favicon**
- It is a small icon (usually 16 × 16 pixels to 32 × 32px) in the dimension of a perfect square. that we use it to identify our website in the tabs of a browser, in a list of favorites, or in any other part that requires a small identification.
    * <link rel="icon" type="image/png" href="/SoyFlow/assets/images/favicon.png"> 
    - Also placed in the head of the html code.

**Icon**
- The icons used on this website are thanks to this platform to use it on our website we place it in the lower part of the body, it is customary to place the javascripts files, the scrip file of this library is
    *   <script src = "https://unpkg.com/ionicons@5.2.3/dist/ionicons.js"></script>

## Test
[validator](https://validator.w3.org/): visite esta plataforma y en la pestaña validate_by_upload, subi cada archivo html que pose esta web y le di clic en un cheque; he colocado una captura de pantalla de la prueba que le realizó una web.
![ScreenShot](/readmeimg/readme.PNG)

**Normalize.css**
<p>
    <a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="¡CSS Válido!" />
    </a>
</p>

**skeleton.css**
<p>
<a href="http://jigsaw.w3.org/css-validator/check/referer">
    <img style="border:0;width:88px;height:31px"
        src="http://jigsaw.w3.org/css-validator/images/vcss-blue"
        alt="¡CSS Válido!" />
    </a>
</p>
     

