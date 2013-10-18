* * *    	
    
    Atom Groom - Sample code for Hireology
    	
* * *  

    Designed and Built by Atom Groom - http://www.atomgroom.com
    All content, design, markup, and css (C) Atom Groom Design, Inc.
    All rights reserved.
    
* * *

# Hello Hireology Team

Thank you for the opportunity to show you a quick sample of my work.  

When I first opened the sample files, my first instinct was that I would
have to refactor all of the code from scratch.  It would take me longer
to go through all of the code line by line, than it would to see the
vision in my mind, and re-code from scratch.  So that's exactly what I did!

## Tools Used:

HTML5 Boilerplate / Initializr:
I used Initializr to get the project started.  It sets you up with Bootstrap,
Modernizr, Respond, HTML5Shiv and JQuery.  I won't get into the details on 
any of these except for my choice of using Bootstrap.  I think Modernizr,
Respond, HTML5Shiv and JQuery, are pretty self explanatory.

Bootstrap:
I chose to use Bootstrap, because it's a rock solid front-end framework
for implementing a project like this. It allows you to quickly setup the
grid for your site and also get the responsive side of the site working
fast as well. The key with Bootstrap is to break your site away from
looking like every other Bootstrap'd site out there.

Brackets:
I chose not to use any type of static site generator.  I just used Brackets
and coded everything up on my own. 

Other:
I also used Photoshop and Illustrator to generate some of the site site 
graphics to create the theme to look similar to the Hireology brand.

## Code Notes:

HTML:
I built the majority of the HTML template with HTML5 in mind, however there are some
DIVs mixed in. HTML5shiv and Respond.js will take care of IEs lack of compatibility
with HTML5 and Media Queries (I did not test IE though).

Much of the HTML and grid uses the Bootstrap classes so that the site sits correctly
in different size view ports. I then implemented seperate classes to apply the look
and feel of the Hireology brand, with my own little mix applied.  
I prefer to separate the grid and layout classes from the style classes. 

I implemented some quick icon fonts for the Settings drop-down navigation,
and the search menu.  I used base64 encoding, as this is compatible with cross-domain
requests that Firefox and other browser complain about.

For the form, I didn't get into eleborate validation, or even processing it, as that
requires server-side technologies.  Instead, I took care of the general styles and 
layout, as well as some basic validation to give you an idea of how that might look.
The form validates using a slightly older jquery plugin called Ketchup.

All of the HTML validates, except for the X-UA-Compatible meta tag.  This can be 
implemented server side, with the X-UA-Compatible meta removed from the HTML and 
then the pages will fully validate.

CSS:
Normally, I would use LESS CSS to build a site out, but since this is such a small
project, I decided against it.  I like to use LESS a lot, once you get your variables,
mixins, etc., all setup, it helps the work flow much faster.  It also helps changes 
sitewide fast as well.

I setup my style sheet to overwrite some of the default Bootstrap styles.  I did this 
so that if there are ever updates to Bootstrap, the theme CSS is completely
separate and we can update Bootstrap without having to worry about losing specific 
colors, etc.

I also setup the theme style sheet to contain all the responsive CSS.  I chose to go 
with the standard breakpoints, except for one.  I changed the first breakpoint
to a max-width of 600px, from 480px.  I chose to do this so that iPad minis and other 
similar view ports will inherit much of that smaller view port type of style.

I probably could have spent a lot more time working on the responsive side of this 
project, but for the most part I am pretty happy with it.  I like to spend a lot of 
time working with content, style, and the UX with regard to different view ports sizes. 
I would also go mobile first, I like the control with those breakpoints much better.

## Cross-Browser Testing

I did test the site in moderen browsers, however I did not spend any time doing
extensive IE testing, or device testing.  It would require a lot of extra time.
In a real-world professional development environment, I would take the time to
do extensive testing.


Thank you for your time. I look forward to your feedback and any questions you might
have regarding this project.

Best,
AG

...........................................................................................

Atom Groom
UI /UX Designer & Front End Engineer

773-454-5651
www.atomgroom.com

...........................................................................................