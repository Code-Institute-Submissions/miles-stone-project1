<a href="top"></a>
# Mile Stone 1 Project.
## "Thomas Dodson Photography."

*Links to both the live website and GitHub repository.*
- <a href="https://twdstudent.github.io/miles-stone-project1/">Link to live website.</a>
- <a href="https://github.com/twdstudent/miles-stone-project1#top">Link to GitHub Repository.</a>

*Please use the links below to navigate this README.md file.*

- <a href="#External-Frame-Works">External Frameworks</a>
- <a href="#The-CSS">The CSS</a>
- <a href="#Images">Images</a>
- <a href="#Video/Audio">Video/Audio</a>
- <a href="#Media-Queries">Media Queries</a>

The brief was to create a website for a band but I have built one for a photography
website.

My wire frames are located in the "wire-frames" folder.

Including the home/index page, it's a 4 page website linked together via the 
navigation buttons on top of each page.

#### Nav Bar Layout.
As you'll see when reviewing my wire frames, the nav lay out is different
on the home page than it is to the other pages within the site. This is deliberate 
as I wanted to explore with the bootstrap grid system. The home page doesn't
have a link to the home page either as you are already on the home page.

The *profile picture* at the top of the page (in a circle) is also linked to the 
home page to help aid better user experience so they can always "find there way home".


<a name="External-Frame-Works"></a>
### External Frame Works.
I used external frame works quite extensively on the site, see below what was used;

-I used the the *Bootstrap grid system* quite heavily for the general layout of each
page and also to make the site responsive to device capabilities.
This you'll notice effects the layout of the navigations buttons. 
This is so the nav links are easy to use even on small devices like mobile phones.
The image gallery layout and the footer sections are also built with this in mind.
The gallery goes to single rows for mobile devices otherwise the images would be too small 
to view.


-*FontAwsome* was used on the social media links at the bottom of the page and styled 
individually with CSS, same goes for the download icon for "download my business card"
*Bootstrap glyphicons* were also used for the navigation buttons.

-*hover.css* was used for the navigation buttons.
On line 114 of *style.css* and line 109 of *style-other.css* the "hvr-sweep-to-bottom" class
dimensions are 3px smaller than the button itself. This was because the hover was bleeding over
the borders of the buttons them selves and quite simply looked sloppy, adjusting the dimensions
solved this.

-*Google fonts* was used too, linked within the css pages. Font I chose was "Courgette"
with "Roboto" as a back up.

<a href="#top">Back to top</a>

<a name="The-CSS"></a>
### The CSS.
-*2xcss style sheets*-I've used 2 css style sheets for this site, the reason being is 
due to the navigation layout being different on the home page to all the other pages.
I did this to avoid having to use a lot of duplicated coding and use of additional wrappers
which would have made it harder for me to keep track of and debug if needed.
I know that scss and sass would be a way round this, but at the time I wasn't at on
that section of the course so wasn't comfortable using it. This I thought was a safe and
simple solution for me to use to get round this.

<a href="#top">Back to top</a>

<a name="Images"></a>
### Images.
-*Images*-lesson I've learned here is how image size can effect the download speed of your
page. First I loaded them up at 2mb each and the page took quite a bit time to load-longer
on mobiles! So images were resized down to approx 500kb, except for the image used on
the background on the home page "canal-dock-homepage", that was set to a slightly higher 
resolution as it takes up more screen space and thus pixelated.

<a href="#top">Back to top</a>

<a name="Video/Audio"></a>
### Video.
The video within the website is meant to be a video tour of a studio,
however for the purpose of the exercise I've loaded a simple video from 
my phone *NOT A ACTUAL STUDIO TOUR* and styled it with css.

### Audio File.
The brief stated that a audio file had to be included, however as this is a photography
website, a audio file is not relevant *BUT* on line 60 of *"studio.html"* I've entered
a audio element and commented it out so it doesn't render on the live web page.
This was simply to demonstrate I could add an audio file and style it with css. The 
code is as follows

        <div class="audio-wrapper">
            <marquee behavior="scroll" direction="left" class="song-title">Nickelback - How You Remind Me</marquee>
            <audio controls>
              <source src="assets/images/audio/How-You-Remind-Me.mp3" type="audio/mp3">
              <source src="assets/images/audio/How-You-Remind-Me.ogg" type="audio/ogg">
              <track label="English" kind="title" srclang="en" src="assets/images/audio/How-You-Remind-Me.mp3" default>
                Your browser does not support the audio tag.
            </audio>
        </div>
        
        and the css;
        
        .song-title {
             margin-top: 5px;
             margin-bottom: 0;
             padding-bottom: 0;
             width: 30%;
            } 

        .audio-wrapper {
             margin-left: auto;   
             margin-right: auto;
             height: 80px;
             margin-top: 20px;
             margin-bottom: 40px;
             width: 70%;
             background-color: #f1f3f4;
             padding: 0;
             border: 4px solid black;
             border-radius: 20px;
             overflow: hidden;
             box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.5);
            }

         audio {
             width: 100%;
             padding-bottom: 5;
             margin: 0;
            }
        
        

<a href="#top">Back to top</a>

<a name="Media-Queries"></a>
### Media Queries.
-*Media Queries*-Towards the end of building this page I used media queries to help aid
the responsive design aspect, I noticed when testing the site to try and brake it using 
*chrome tools* and even simply inspecting the site on my own phone. I noticed that even
though the navigation buttons and social media links laid out the way I expected, they 
were quite small and not so easy to use and often missed pressed the wrong link.
Media queries to the rescue, these were used to make the buttons bigger on smaller devices.
Also it makes the site more aesthetically pleasing when using on mobile devices.
Other small aspects were changed too;

-*Profile Picture increases in size slightly on mobile devices.*

-*Images within the gallery have a larger gap between them on smaller devices as they*
*were too tightly packed on smaller screens.*

-*Increased space between social media links, again accompanied with the increased size*
*it helps make it more user friendly and helps avoid pressing the wrong link.*

-*Download icon was increased in size for smaller devices for the same reason as the* 
*social media links.*

<a href="#top">Back to top</a>

