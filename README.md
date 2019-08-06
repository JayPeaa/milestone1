# Milestone Project 1 - Build a site to promote a rock band.

The project is based on promoting a band to showcase HTML and CSS skills learned so far as part of the code institute online diploma. 

## UX

The project has been designed with the end user in mind.  The end user being members of the public (fans or potential fans) who either wish to purchase tickets or book the band for a private event.
The flow of the site has been created in a traditional style with clear navigation and a large 'call to action' button (Get Tickets) placed in the header of the home screen.  This call to action button occupies prime real estate in order to drive ticket sales and contains a hover effect to drive the 'click through rate' and increase conversions.  This aspect of the site recognises its commercial nature whilst enhancing the user experience by making it easy to acquire tickets within a couple of clicks.

A user may wish to perform the following actions:

* reach out to the band via social media.
* subscribe to regular updates.
* book tickets via the site.
* contact the band via the contact form.
* contact the band via more traditional means (post/phone/email)

The site provides all these options to the end user and is very easy to utilise and navigate.

As mentioned, the site is intentionally styled in a bespoke 60's theme with the font style also being reflective of the design principles.  The intention is to create a visually appealing fun site with engaging animation and original ideas such as the spinning disks in the music section to enhance the user experience.

Wireframes for this project are available here https://github.com/JayPeaa/milestone1final/blob/master/Milestone1.pdf

# Features

The main features of the site are:

* Ticket bookings
* Email subscription to build mailing lists as part of a marketing strategy
* Social Media for marketing and engagement purposes
* Contact Form for ease of communication
* Animation to enhance user experience, drive engagement, increase click-through and drive conversions and sales

Additional social media channels such have been included in the footer for discussion with the client for additioanl value. This can be easily removed if not required.

## Future development

Future features may include the use of the google maps API for each of the venues in the tour section which can be used in conjunction with google Maps for navigation and additional UX benefits.
The flashing down arrow in the header section (indicating more content below) will include some additional JavaScript code to enable the user to click the icon to be taken to the next section with a scroll effect.

In addition pluging this theme into a fully content managed system such as Joomla or Wordpress would make updating its content easier and more efficient for the band to manage.

# Technologies

The site is built using HTML and CSS and any CDN / Library usage is documented below:

* CDN Usages

The following CDNs have been used to create this site.

https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css
https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css
https://cdnjs.cloudflare.com/ajax/libs/hover.css/2.3.1/css/hover-min.css
https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js

* Libraries

https://code.jquery.com/jquery-3.2.1.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"

# Testing

Testing has been conducted using google dev tools. Thorough testing in all the various mobile devices along with general responsiveness (responsive mode) has concluded
that this site works well in all modern-day browsers and mobile devices. As part of the testing process each page has been reviewed systematically to ensure all links
work as intended and the pages display correctly.  

This testing has confirmed that users will be able to utilise the site as intended on any device (in landscape or portrait mode) to achieve their goals whilst enjoying the experience and customer journey.

At this stage any forms are front end only in line with the project scope and currently do not function. These forms have only been tested for responsiveness and field qualities (e.g. Place holder text appears, Prompt for required fields are correctly displayed) at this stage.

All user forms display correctly and as intended on various displays / devices.

Autoprefixer was used to ensure CSS is compatible in multiple browsers: https://autoprefixer.github.io/

Browser Compatibility Testing:

### Issues Encountered

Internet explorer did not support certain formatting options and rendered the background body image too bright.  In order to resolve this issue, the wallpaper image was edited and darkened without the need to use the CSS code. The contrast was adjusted until the end result was suitable Internet Explorer and the other browsers.

The Video on the 'Tour Dates' page was not responsive but this was a quick fix to change the Max-width property from PX to a relative % measurement.

Time was invested at the start of the project to ensure HTML code was working well before reusing the code for subsequent pages which saved some time.

HTML and CSS Validators were used to clear any errors. 

# Deployment

Throughout the projects regular git commits were made to ensure any working files were backed up. In excess of 20 commits have been logged on the main branch in GitHub.
The project has been successfully deployed on GitHub pages.  There is only one main branch in GitHub for this project.

AWS cloud9 has been used throughout this project as the IDE of choice.  

GitHub Pages Address: https://jaypeaa.github.io/milestone1/

# File Structure

The project has been organised in the following structure:

* milestone1final (Project Folder)
* assets (folder)
    * vendor (folder)
        * audio (folder)
        * images (folder)
        * video (folder)
    * css
        
The HTML files, Main.css and README.md are located within the main project folder.

The vendor folder contains any 3rd party assets such as photos, video and audio materials for which proper approval has been sort for reuse prior to posting.

# Credits

Dummy text about the Monkees has been taken from Wikipedia and may not be particularly relevant in terms of its content or how it relates to the page
being viewed as the site is for educational purposes only.

About Us Section: Text from Wikipedia: https://en.wikipedia.org/wiki/The_Monkees
User profiles: Text from Wikipedia

* Davy Jones Profile: https://en.wikipedia.org/wiki/Davy_Jones_(musician)
* Mickey Dolenz Profile: https://en.wikipedia.org/wiki/Micky_Dolenz
* Michael Nesmith Profile: https://en.wikipedia.org/wiki/Michael_Nesmith
* Peter Tork profile: https://en.wikipedia.org/wiki/Peter_Tork
    
 Information relating to tour dates was taken from https://www.songkick.com/artists/485568-monkees as the Monkees are currently touring.

Content on the contact section is fictional e.g. address, tel and email.

Dummy text about the Monkees from Wikipedia may not be particularly relevant in terms of its content or how it relates to the page
being viewed as the site is for educational purposes only.

# Images and Media

All images and media used on this site have been labelled for reuse / non-commercial and are for educational purposes only.  Google images licensing tools
have been utilised in sourcing content where content has not been provided by the code institute specifically.
