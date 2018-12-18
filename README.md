# Burning Man

**Version 1.0.0**

Burning Man was an easy choice of topic to pick for my first project. The ever growing popular festival
situated in the middle of the Nevada desert that prides itself on self expression and self reliance sees
thousands of people from around the globe descend on the very baron location to create what can only be
described as a huge city full of joy, opportunity, madness, taboos, art, culture and many crazy ideas,
which in turn create something mindblowing and only something that can really be explained through going
and seeing it for yourself for 7days a year.

This site tries to give you a brief insight into what goes on there, how things work and are run there.
What to expect and how to get involved yourself. It includes photos and videos to check out to see the 
typical day to day madness the place offers. As it is such a popular event, many places around the world
feel they need a piece of Burning Man too, which through creativity and ideas have allowed people to create
regional events on a slightly lower scale to the main event in Nevada. There were far too many to list, but 
on my Global Burners page, i have listed a couple of the biggest regional events.

## UX

 - This website can be used to help people understand Burning Man and how it works.
 - Users can learn about the origins and history of the event and how it has gone from a small gathering on a 
   San Francisco beach to a massive event in the Nevada desert.
 - Users can learn about the 10 Principles the event lives by which is the backbone of how the event is so popular.
 - Users can learn about regional events that are put on globally incase the trip to Nevada is too much to make for them.
 
### Existing Features

Each page includes a header with the same image of a sunsetting at Burning Man.
They all also include a dropdown NavBar to direct you to each page.
They then include a footer which have social links to direct you to their social pages.

The Home page explains to the user What the festival is about and how things work there.
It also includes two youtube videos of the event, one from 2013 and the other from 2017.

The History page allows the user to understand the origins and history behind the event and the ever lasting
popularity behind it.
It has a very old youtube video of the history of Burning Man, and it also has a picture of the timeline showing
the different effigies built from the very beginning and how it has grown over the years.

The 10-Principles page helps the user understand the core rules of thumb to live by whilst at Burning Man,
from the Radical-Inclusion and Gifting, to the Participation and Immediacy which makes the place so special.

The Global Burners page allows users to learn about regional events around the world that follow the Burning Man 
way. As there are around 100 low key events all over the world, i decided to focus just on two of the larger ones,
Afrikaburns situated in South Africa, and Burning Seed situated in New South Wales, Australia.
The page also includes a photo from each event of their respected effigies built.

### Features left to implement

 - an option to purchase tickets for the event or any of the regional events around the globe
 - a Live page to be able to watch the event happening Live
 - a page dedicated to real-life stories and appraisals from the event
 - As words only let you imagine the event to a certain extent, i would add a gallery of photos and videos
   because seeing is believing
 - an option to sign up to the site for future emails regarding all things Burning man from information 
   of the event and its regional events to all the fundraising events being done to raise money to make the 
   events even possible in the first place.

## Technologies Used

In this project, there were several frameworks and languages used ...

 - Bootstrap (https://stackpath.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css)
   Bootstrap was used to help lay out the content in a grid system i felt would allow the user to have a clear and simple
   way to guide themselves through each page with easy to read and understanding of the content layout.
 - Font Awesome (https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css)
   Font Awesome was used in this project to allow the users to be able to easily locate links to the Burning Man social pages,
   through stylish icons located in the footer of each page.
 - HTML5 was used to provide the structure of the web pages and help describe the content on each page.
 - CSS was used to present the content and style it to specifically the way i intended it to be styled.


## Testing

Each page has been looked over several times to make sure it looks and functions how i want it to, from the Youtube videos,
to the hovering over the social links in the footer, to the Menu Navbar to drop down and allow the user to go between each
page effortlessly.

While testing the pages the menu bar at the very top would follow down which i wanted it to, but it would end up being underneath
all my information in the main body. I overcame this problem by adding a Z-index to its style of a very high number like 999
which then made it prominent over everything else on the pages.

On my history page i found it hard to line up my image to the Youtube video because of the bootstrap used. I overcame this 
problem by adding a bootstrap to just the image of col-md-6 which allowed me to do what i wanted to to the image.

On my Global Burners page i couldnt manage to centre my images due to the pages bootstrap, but after adding
text-align: centre; to the CSS of each image, they were then placed exactly where i wanted them.

After testing my so-called finish code on https://validator.w3.org/#validate_by_input, i had a couple of errors and warnings,
 
 - I had to add the language to english in the <head> on each page
 - I needed to add a title to the head element on each page
 - Timeline image needed an alt attribute on the History page
 - I had an unclosed section element
 - There was an attribute height not allowed on line 39 of the Global Burners page
 - There was a stray end tag div on line 77

After testing my CSS code on https://jigsaw.w3.org/css-validator/#validate_by_input, i had one error.

 - On my home page section at line 185 i had a value error, position: center; was not allowed so it was changed
   to inherit.

## Deployment

I deployed my project to Github whenever i felt i needed to add something which i had done that was important by adding
it to the staging area then committing it to my Github - https://github.com/lynnthomas/project_1_burning_man.

### Content

The text for the last paragraph on the Home page was copied from - https://burningman.org/culture/history/art-history/perspectives-on-playa-art/art-cars-on-the-playa/

The text for the three paragraphs on the History page were copied from - https://www.designboom.com/art/burning-man-a-brief-history-of-the-desert-festival-and-black-rock-city/

The text for the first paragraph on the History page was copied from - https://en.wikipedia.org/wiki/Burning_Man

The text for the 10-Principles page was copied from - https://burningman.org/culture/philosophical-center/10-principles/

The tesxt for the AfrikaBurn section on the Global Burners page was copied from - https://www.afrikaburn.com/about

The text for the Burning Seed section on the Global Burners page was copied from - http://burningseed.com/about/what/

### Media

The photos used in this site were obtained from...
 - https://s-i.huffpost.com/gen/2055172/images/o-BURNING-MAN-PHOTOS-facebook.jpg (This is the sunset image placed in the header section on each page)
 - https://www.burn.life/history-of-burning-man.html (image placed on History page)
 - https://blog.junkmail.co.za/afrikaburn-art-music-and-performances/27785 (image placed on Global Burners page)
 - https://allevents.in/matong/burning-seed/196965754065235 (image placed on Global Burners page)

The videos used in this site were obtained from...
 - https://www.youtube.com/watch?v=5pUTKNGpu1s (video placed on Home page)
 - https://www.youtube.com/watch?v=uq60IH6hzHY (video placed on Home page)
 - https://www.youtube.com/watch?v=TNv93IgQymA (video placed on History page)

### Acknowledgements

I received inspiration for this project from attending the festival back in 2014. It was by far the best place i have 
ever experienced, and after having left there, i have been massively intrigued to dig deeper into every aspect of the 
place and what it has to offer.



     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


Hi there! Welcome to Cloud9 IDE!

To get you started, create some files, play with the terminal,
or visit http://docs.c9.io for our documentation.
If you want, you can also go watch some training videos at
http://www.youtube.com/user/c9ide.

Happy coding!
The Cloud9 IDE team# project_1_burning_man
# project_1_burning_man
