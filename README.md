# csPortfolio
  <details><summary><strong>NEW PORTFOLIO</strong></summary>
    <p>
      <a href="https://alexejosh.github.io/compsciportfolio/">Link<a>
    
  >This was an extremely interesting project to work on. I enjoyed this topic and learning HTML and CSS.
    </p>
  </details>
  <details><summary><strong>First Web Page</strong></summary>
    <p>
      <a href="https://alexejosh.github.io/portfolio/firstPage/">Link<a>
    
  >This project was a learning experience for me and an introdution to webpage creation. This allowed me to experiment in many ways and say I created my first webpage.
    </p>
  </details>
  <details><summary><strong>Lightning</strong></summary>
    <p>
     <a href="https://alexejosh.github.io/lightning2/">Link<a>
       
   >Lightning allowed me to learn more about positioning, randomWalk, and creating an animation in processing.
    </p>
  </details>
  <details><summary><strong>Dice</strong></summary>
    <p>
     <a href="https://alexejosh.github.io/dice3/">Link<a>
           
   >Dice taught me OOP (Object Oriented Programming) techniques and creating an appealing interface.
    </p>
  </details>
  <details><summary><strong>Chemotaxis</strong></summary>
    <p>
      <a href="https://alexejosh.github.io/chemotaxis/">Link<a>
            
   >Chemotaxis showed me the immense uses of positioning and randomWalk, and its purpose in the making of many games.
    </p>
  </details>
  <details><summary><strong>StarField</strong></summary>
    <p>
      <a href="https://alexejosh.github.io/starfield/">Link<a>
            
   >StarField was an expierence. This project was a place for me to use many of the techniques I have learned over the tri and experiment with them all in my own way. StarField also taught me more about interfaces and inheritance.
    </p>
  </details>
  <details><summary><strong>College Presentation</strong></summary>
    <p>
      <a href="https://alexejosh.github.io/collegePresi/file.html">Link<a>
            
   >College Presentation was a project I completed to learn more about the computer science field at the *University of Michigan Ann Arbor*.
    </p>
  </details>

# DR. R's Questions and Jalex's Answers


1. Reflect on all your portfolio projects.  
>>In drop downs for each lab.

2. What is one or two things that are a source of pride in your programming development?  
>>My official [Portfolio](https://alexejosh.github.io/compsciportfolio/).
3. Identify them, write about why they are accomplishments, how you did it and what you learned.  Be sure to submit a code snippet along with your writing on the readMe file in your repo.
>>My Portfolio was an accomplishment for me because of the amount of *HTML* and *CSS* that I was able to learn and become confident using. I used brackets to be able to see my webpage changes in real time. Using this method I was able to quickly learn *HTML* as I used it and become more comfortable with my *CSS* skills. Being a quite intriuguing topic for me, I was  constantly googling and learning both of the languages. With my approach of learning, I earned a healthy knowledge of many modern uses of both languages. 
The code below shows the differing styles I used on my links and buttons.

```Java
        .Button{
                    border: 3px solid white ;
                    color: white;
                    font-family: sans-serif;
                    font-size: 1vw;
                    text-align: center;
                    font-style: bold;
                    border-radius: 6px;
                    margin: auto;
                    width: 150px;
                    padding-left: 0px;
                    padding-right: 0px;
                    height:auto;
                }
                .Button:hover {
                    background-color:white;
                    color: rgb(11, 137, 146);
                }
                a:link {
                    color: rgb(11, 137, 146); 
                    background-color: transparent; 
                    text-decoration: none;
                }
                a:visited {
                    color: rgb(11, 137, 146);
                    background-color: transparent;
                    text-decoration: none;
                }
                a:hover {
                    color: darkblue;
                    background-color: transparent;
                    text-decoration:inherit;
                }
                a:active {
                    color: darkorange;
                    background-color: transparent;
                    text-decoration: inherit;
                }
```
4. Identify the most significant hurdle you encountered last trimester.  Write about what it was and how it was resolved.
>>Last trimester I was creating my [first modern site](https://alexejosh.github.io/portfolio/firstPage/). It was extremely difficult to create a background that was fixed while the rest of the site floated over it. I had to size the image properly to every screeen size and keep the navigation in a fixed position while all other sections of the site looked as if they floated over the picture. I resolved this after many, many google searches and reading multiple manuveres around this issue to find the solution that suited my understandings. I had to make sure I understood this code and be able to properly implement it into my code. This learning allowed me to reproduce this effect from my intuition and work my other code to use this effect. 
5. Once you are ready to submit your writing and code examples, study markdown (language used on github to format text).
>>Shown through this *README* file.
6. Describe the incremental and iterative development process of your included code, focusing on two distinct points in that process. Describe the difficulties and/ or opportunities you encountered and how they were resolved or incorporated. In your description clearly indicate whether the development described was collaborative or independent. At least one of these points must refer to independent program development
>>I found great incremental and iterative issues throughout my code when I tried to make the navigation bar change colors when scrolled and when creating the layout of the navigation bar. 
>>1. I experienced a multitude of problems when trying to create a variable color navigation bar. I first had to learn how to introduce *JavaScript* into an *HTML* file. This became very difficult because for a long time I had invalid *JS* code and did not realize that the *JS* was implemented into the *HTML* but had invalid code. To solve this issue I searched the internet furiously but to no avail. I, independently, found the solution by learning *JavaScript* from [W3 Schools JS Tutorial](https://www.w3schools.com/js/default.asp). 
```Java
		<head>
		    <title>Jalex CompSci Portfolio</title>
		    <link rel="stylesheet" type="text/css" href="style.css">
		    <link rel="shortcut icon" href="favicon.ico">
			<link rel="icon" sizes="16x16 32x32 64x64" href="favicon.ico">
			<link rel="icon" type="image/png" sizes="196x196" href="favicon-192.png">
			<link rel="icon" type="image/png" sizes="160x160" href="favicon-160.png">
			<link rel="icon" type="image/png" sizes="96x96" href="favicon-96.png">
			<link rel="icon" type="image/png" sizes="64x64" href="favicon-64.png">
			<link rel="icon" type="image/png" sizes="32x32" href="favicon-32.png">
			<link rel="icon" type="image/png" sizes="16x16" href="favicon-16.png">
			<link rel="apple-touch-icon" href="/favicon-57.png">
			<link rel="apple-touch-icon" sizes="114x114" href="favicon-114.png">
			<link rel="apple-touch-icon" sizes="72x72" href="favicon-72.png">
			<link rel="apple-touch-icon" sizes="144x144" href="favicon-144.png">
			<link rel="apple-touch-icon" sizes="60x60" href="favicon-60.png">
			<link rel="apple-touch-icon" sizes="120x120" href="favicon-120.png">
			<link rel="apple-touch-icon" sizes="76x76" href="favicon-76.png">
			<link rel="apple-touch-icon" sizes="152x152" href="favicon-152.png">
			<link rel="apple-touch-icon" sizes="180x180" href="favicon-180.png">
			<meta name="msapplication-TileColor" content="#FFFFFF">
			<meta name="msapplication-TileImage" content="/favicon-144.png">
			<meta name="msapplication-config" content="/browserconfig.xml">

		    <script>
			var h = window.innerHeight;

			//var LandingHeight = document.getElementById('LandingHeight').clientHeight;
			/*
			var AboutHeight = document.getElementById('About').offsetHeight;
			var CompSciHeight = document.getElementById('CompSci').offsetHeight;
			var PhotoHeight = document.getElementById('Photo').offsetHeight;
			*/

			window.onscroll = function() {navTrans()};
			function navTrans() {
			    if (document.body.scrollTop > h-50 || document.documentElement.scrollTop > h-50) {
				document.getElementById("nav").className = "NavigationScroll";
			    } else {
				document.getElementById("nav").className = "Navigation";
			    }
			}
		    </script>
		  </head>
```
>> 2. When trying to create a layout of my navigation bar, I encountered many issues in trying to get all the *divs* to line up horizontally and sizing them to all window sizes. I overcame this issue through multiple searches in the W3 Database to find *display: inline-block*. After fixing the horizontal issue I needed to space the divs out properly and make them all apealling in all window sizes. This was solved by the *plug and check* method by trying all different *padding, margins, and borders* until I found a pleasing look.
```
		div.Subset{
			    border: 2px solid black;
			    border-radius: 6px;
			    margin-left: 5px;
			    margin-right: 5px;
			    margin-top: 11px;
			    margin-bottom: 8px;
			    padding-top: 0px;
			    padding-bottom: 0px;
			    padding-left: 5px;
			    padding-right: 5px;
			    line-height: auto;
			    width: auto;
			    height: 35px;
			    position: relative;
			    float: right;
			    font-family: 'Montserrat', sans-serif;
			    letter-spacing: 0.2em;
			    text-transform: uppercase;
			    text-align: center;
			    display: inline-block; 
			    color: black;
			}
			.SubsetText{
			    vertical-align:middle;
			    padding-top: 18px;
			    padding-bottom: 25px;
			    margin-top: 0;
			    margin-bottom: 0;
			    padding-left: 5px;
			    padding-right: 5px;
			}
			.Subset:hover{
			    border-color: rgb(216, 156, 104);
			    color: rgb(216, 156, 104);
			    /*border-color: rgb(11, 137, 146);
			    color: rgb(11, 137, 146);*/
			}
```
