# Band Website 
[Here it is](https://johnkuang022.github.io)

### I wanted to make a website for my band

### So I made one

### Here are the steps

# Step 1:
I used the website example in the ITP repository [template](https://rdwrome.github.io) for the initial template of my website. I then deleted the elements I did not need, such as the mp3 bar, and the graphic at the bottom of the website. 

I then copied the .css file from this website as well, and I used the css resources from [W3Schools](https://www.w3schools.com/css/default.asp) to make a few changes. 


To change the background color, I just used the hex color generator from Google and copied it into the .css file from the template website. 

To add a topnav, I used a code from [W3Schools](https://www.w3schools.com/css/default.asp):

```<div class="topnav">
  <a class="active" href="#home">Home</a>
  <a href="about.html">About</a>
  <a href="archive.html">Archive</a>
</div>```

Then, I used the same resrouces to make cosmetic changes to the navigation bar in the .css file: 

```/* Add a black background color to the top navigation */
.topnav {
  background-color: ##ff2965;
  overflow: hidden;
}

/* Style the links inside the navigation bar */
.topnav a {
  float: left;
  color: #e0d3d7;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

/* Change the color of links on hover */

.topnav a:hover 
  background-color: #e0d3d7;
  color: black;
}

/* Add a color to the active/current link */
.topnav a.active {
  background-color: #4894db;
  color: #e0d3d7;
}```

Adding the topnav bar made me realize that I have to make a separate .html file for each of the pages, and reference them as the source in the index.html file that is essentially the "home page."

Before getting to the other pages, I finished updating the information on the home page first. I used the [HTML Cheat Sheet](https://websitesetup.org/wp-content/uploads/2019/08/HTML-CHEAT-SHEET.png) found in the class repository and it helped me understand headings, containers, paragraphs, etc. A particular code that was essential to forming the home page was the ```alight-"center"``` that I would put in every paragraph so that the text is centered. An alternative way I found on [W3Schools](https://www.w3schools.com/css/default.asp) was to do it through the .css file with ```text-align: center;``` that allowed me to do the same to the headings. 

Then, I basically just input all the information into the parts of the code; such as links to band camp, instagram, and a list of touring locations and dates. There was very little work I had to do here since a lot of the coding was already part of the template website.

# Step 2

My next step was to create the .html files of the other pages of my website. It followed a pretty similar precedure as the home page, where I copied the html and css template from [here](https://rdwrome.github.io) and deleted almost all the contents except for the bare-bones structure. 

I then converted a video to a .gif file, then I wanted to set that file as the background of the page. [This particular thread](https://stackoverflow.com/questions/21590343/how-to-display-a-gif-fullscreen-for-a-webpage-background) on stackoverflow was very helpful. It was very simple because all I had to do was use the url to reference the .gif file's name, and position it in the center with the right ratios.

```body {
    background:url('aboutpage.gif') repeat-y 100% 100% fixed;
	background-position: center center;
    height:100%;
    width:100%;
}```

I then copied our band's EPK, and used ```<marquee>``` to make it run across the screen. I then just copied it a bunch of times so that it covers the entire screen.
	
To get the mirrored text, I just googled [reverse text generator](https://www.textfixer.com/tools/reverse-text-generator.php).

# Step 3

The last page I wanted to make for my band was a flyer archive page. This was the easier page to make out of all three. The html file followed exactly what I did for the other pages, except that I only had one paragraph in the body, and used ```<br>``` to break apart the flyer images. I used ```<img src="...">``` to reference the images I had uploaded into the folder. 

I then used a random photo I took that I thought fit the aesthetic and set it as the background of the page, using what I learned in step 2. I then used ```background-repeat:``` to make the image repeat and used ```background-size:``` to resize the image. I learned how to do all of this in the [W3Schools](https://www.w3schools.com/css/default.asp) CSS resources.

# Step 4

My last steps were to add some cosmetic changes to the home page. I first added the image that is probably the first thing you will notice on the page, and also I added my own custom fonts to the web page.

I really like Imago, so I downloaded the .ttf file from the internet and put it in the folder of my website. Then, I used this code from [W3Schools](https://www.w3schools.com/css/css3_fonts.asp) to change the fontface:

```@font-face {
  font-family: myFont; /* set name */
  src: url(sansation_light.woff); /* url of the font */
}```

# Conclusion

I think by making this webiste, I've found that coding is not as scary as I thought it would be, espcially with so many resources one click away. I barely did any "real" coding and the most work I've done is copying lines of code and trying out different values to make my website look better. However, I do have a better understanding of a website's structure and the structure of HTML 5. 


