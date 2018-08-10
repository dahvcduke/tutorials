---
title:  StoryMapJS
description: This tutorial introduces the interface of and techniques for using Knight Lab's StoryMapJS
updated: August 10, 2018
authors: Hannah Jacobs, Beth Fischer
---

## What is StoryMapJS?
StoryMapJS ([https://StoryMap.knightlab.com/](https://storymap.knightlab.com/)) is an [open source](https://opensource.org/osd) [web application](https://en.wikipedia.org/wiki/Web_application#Definition_and_similar_terms) created by the [Knight Lab](https://knightlab.northwestern.edu/) at Northwestern University.

With StoryMapJS, authors can quickly create simple but powerful spatial narratives. StoryMapJS narratives are made up of [slides (individual events or parts of a narrative)](#anatomy-of-a-storymap-slide). Each slide is connected to a specific point in space. This narrative "space" may be either geographic or cartesian: slides may be connected to points on a [geo-referenced map](https://en.wikipedia.org/wiki/Georeferencing) (such as Open Street Maps) or points on an image the author provides. 

The location-based stories created in StoryMapJS may also be time-based, _but they do not have to be_. There is no explicit timeline feature, so the ordering of the narrative is up to the author. These stories can then be published via StoryMapJS, shared, and embedded on other websites. 

## Possible Use Cases
StoryMapJS is a free, easy-to-learn, and visually appealing tool that could be used for teaching or research. It could be used to explore data, develop a project prototype, or present a variety of humanities arguments. The following are just a _few_ ideas for how StoryMapJS might be used in teaching and research.

### In the Field 
Use StoryMapJS for quick visualization:
*   Document site-specific media you wish to return to later.
*   Test an idea for a spatial interactive narrative.
*   Record and view a series of location-based events quickly.
*   Annotate an image.

Examples:

*   DH@WCU: [http://digitalhumanities.wcu.edu/digital-humanities-tools/StoryMapjs/](http://digitalhumanities.wcu.edu/digital-humanities-tools/storymapjs/) 

### In the Classroom 
Develop class projects in which students are asked to:
*   Create a photo essay.
*   Analyze a series of historical events.
*   Use StoryMapJS as a study tool for learning places, dates, and associated facts.
*   Explore interactive digital storytelling as a communications medium.
*   Publish a visual analysis of a single image.

Examples:

*   ["Teaching with Tumblr and StoryMapJS."](https://historyblogger.net/2014/12/26/teaching-with-tumblr-and-storymapjs/comment-page-1/) _History Blogger_. (December 26, 2014)

*   Hackman, Meg. ["How we mapped pumpkin spice lattes to teach students digital storytelling skills"](http://www.storybench.org/how-we-mapped-pumpkin-spice-lattes-to-teach-students-digital-storytelling-skills/) (November 12, 2015)

### In a Publication or Presentation 
StoryMapJS can be embedded in other web pages, so it's possible to use it in a digital publication or as part of a conference presentation. You can also publish a link to a StoryMap in a print essay. Visualize a narrative important to your argument. Annotate an image. Add a spatial narrative that includes multimedia gathered or created as part of your research.

## Create a StoryMap 
### What's your story? 
A StoryMap's primary purpose is to promote new knowledge and understanding of a particular topic. Every StoryMap is made up of individual events woven together to form a narrative that guides viewers to that knowledge and understanding

To begin developing your story, consider answers to these questions: 

*   What is your story about?
*   Why is this person, place, thing, or event significant?
*   What is the most important piece of information that viewers should learn from the story?
*   How does space or location matter to your story?

Then create a list, storyboard, or sketch. Based on your answers to these questions, what are the significant moments or events that make up your story? Use any method that works for you, but do this outside of StoryMapJS. 

### Gather Media Content 
You content may be your own, or it may be gathered from other sources. Keep in mind:

*   Depending on the content type, media may be uploaded (images) or hosted elsewhere (audio, video, etc.). 
*   Keep in mind that each StoryMap slide is set up for only one media item. If you want to add extras, you'll insert them in the HTML editor.
*   Make sure to attribute your images in the credit textbox that accompanies each media item. 

**Media Types**
The following media types can be embedded in a StoryMapJS slide using the url from each application's "share" feature:

*   DailyMotion
*   Flickr
*   Google Doc
*   Google+
*   Any iframe-formatted* content 
*   Instagram
*   SoundCloud
*   Storify
*   Twitter
*   Vimeo
*   Vine
*   Wikipedia
*   Youtube
*   And more...try something! You can also upload an image of your own and embed that without having it hosted online separately. 

\**An iframe is actually an HTML Embed Code that allows you to embed another document or media type in your page, not a media type itself. An iframe in a StoryMap could show another StoryMap, for example.*


### Create & Edit a StoryMap 

StoryMapJS requires a Google account. If you do not have a Google account you can navigate to [https://accounts.google.com/](https://accounts.google.com/) and click "Create an Account" to set up a Google account.


1.  Navigate to [https://StoryMap.knightlab.com](https://storymap.knightlab.com).
1.  Click the green "Make a StoryMap now" button.  
1.  Click "Login with your Google account."
1.  In the "Your StoryMaps" popup, click "New." *Once you've created a StoryMap, a list will appear in this popup window every time you access StoryMapJS.*
1.  Give your new StoryMap a name and click "Create".
1.  You'll be redirected to the StoryMap editing page. This area has a very simple structure: ![StoryMap page guide](images/layout.png#right#60)  


    1.  Map viewing window.
    1.  List of slides/events. 
    1.  Slide editing area.
    1.  StoryMap options.
    1.  Preview.
    1.  Share.
 1.  Use your StoryMap outline/storyboard/sketch to begin creating slides.
    
1.  The first screen is your title slide. Enter a title for your project (in the "headline" field), attributions, and an overview of what users will find in the StoryMap. As you create additional slides, this title slide will update to show all the points you have marked on your other slides.
    1.  Create additional slides for each event or point in your narrative by clicking the "add slide" button on the left. 
1.  Associate a location with each slide. There are three methods: ![marker on map](images/marker.png#right#50)
    1.  Drag and drop the marker on the map.
    1.  Enter a street address in the search box.
    1.  Enter geographic coordinates in the search box. *You can get coordinates from Google Maps by navigating to the place you want to mark in Google Maps, right clicking on it, and choosing "what's here?" from the menu. A card will pop up that includes latitude and longitude. ![box showing geographic coordinates](images/coordinates.png#right#50)In the example to the right showing Durham, the coordinates are approximately 36, -78.91.* 
1.  Add details as described in "Anatomy of a StoryMap Slide" below.
1.  Save your work frequently. 
1.  When you're ready, click "Share" to get a public URL for your StoryMap, send it to social media, or grab an embed code to place the StoryMap on a web page.

### Anatomy of a StoryMap Slide 

Every slide must have a title (called a headline) and a location. It can also have descriptive text and visual or audio content such as images, video, sound clips, and other interactive content.


**Descriptive text** can be typed or pasted into the textbox below the headline field. The bold and italics buttons can be used to format the text, and urls can be added with the link button. Further text customization and structuring can be done in the HTML Editor.

**Media** can be uploaded from a local file, linked to via URL, or embedded using an HTML iframe:

*   Use the "Upload an Image" button to upload images in .jpg, .jpeg, .png, or .gif formats.
*   To embed via URL, locate the media's "share" button and use the URL from that. *In many cases, the URL in the browser window will not work.* 
*   To embed media via **iframe**, you will need to locate a string of HTML code in the media's share menu (look for an "Embed" field or tab). The code for an iframe will look something like:  ```<iframe width="420" height="315" src="https://www.youtube.com/embed/NEsBHHXW9FQ" frameborder="0" allowfullscreen></iframe>```  
*Note that an iframe is _always_ bookended by "<iframe\>" HTML tags.*


Always include a media credit in the "Credit" field (unless the media is in the public domain) and consider including a caption.

### Sharing your StoryMap 

When you are ready to share your StoryMap with the world, you can share via URL, social media, or embedded iframe:

1.  Click the "Share" button.![Share window](images/share.png#right#50)
1.  Copy/paste the link or click a social media icon to share on Twitter, Facebook, Google+, or Reddit. 
1.  To embed your StoryMap as an iframe in another web page, scroll down to the "Embed" textbox.
1.  Select all of the text (HTML code) in the Embed textbox, including the <> tags at the beginning and end. Paste this code into the HTML editor on another website.

## Saving your StoryMap


StoryMapJS stores your StoryMaps on an Amazon server as long as you wish to keep it--and as long as the tool continues to exist. However, you should keep a separate archive of your StoryMaps so that you can recreate it if needed.

Items to include in a StoryMapJS Archive:



*   Outline/storyboard
*   Descriptive text
*   HTML*
*   Media Files, URLs, and embed codes
*   Slide locations (street addresses, geographic coordinates)
*   "ReadMe" text file of custom settings
*   Optional: Screenshots of the StoryMap

\**You can save the code for your StoryMap by navigating to it in your browser, then saving the page to your computer or a cloud location. Make sure to select "web page **complete**" as your option to save all the code together. This may be saved in several files; either move them to one folder or create a zip archive to keep them together.* 


## Beyond the Basics: Customizations 

### HTML Editing 

In the slide description textbox, click the `</>` icon to enable HTML editing. StoryMapJS accepts HTML5 tags and inline CSS (though some specific HTML5 tags & CSS attributes may be stripped). This means you can include secondary media using `<img>` and `<iframe>` tags. Other media tags may be supported — try them out and let us know!

![menu with html editor highlighted](images/htmledit.png#right)Before typing or pasting in HTML, _make sure_ that you have selected the HTML editor by clicking the editor button icon `</>`. When you are in HTML editing mode, the editor button will be highlighted in white, as in the example on the right. Pasting code into the rich text editor may cause HTML tags to be stripped and you will have to retype or repaste your code.

Always save custom HTML in text files outside of StoryMapJS.


### Styling a StoryMap

**Customize your overall StoryMap** in the "Options" popup window: set the StoryMap's size, choose a Language and Font pairings, include a "Call to Action" on the introductory slide, and choose your map type.

**Customize individual slides** in the "Slide Options" popup window: change a slide's background color or add a background image to the slide. 

**Using background images: **Choose background colors and images that support rather than detract from text or other media in your slides. The slides are semi-transparent, so some part of the map will always be visible behind the background. In addition, use high resolution images for the background. It's recommended that background images be at least 750 pixels wide. StoryMapJS adjusts its size depending on screen & browser size, so images may be cut to fit the slide. This means you should choose background images for which it isn't necessary to see visual information at images' edges.


###Choosing a Base Map 


StoryMapJS offers a number of open source base maps. There are satellite views available as well as schematic views. Choose a base map based on the style and kind of information you wish your users to see.  

To select a new base map, click "options." On the "display" tab (which should be the first one to load), edit the choice in the "Map Type" dropdown box. 


### Adding a Custom Map 

It is possible to add a custom map to StoryMapJS. This can be useful if you have a specific map style you wish to use that is not available in StoryMapJS. It can also be useful for including historical map layers on top of present day maps.

StoryMapJS accepts [XYZ map tiles](https://en.wikipedia.org/wiki/Tiled_web_map) for basemaps. One free tool for creating custom basemaps in this format is Mapbox ([https://www.mapbox.com/](https://www.mapbox.com/)). Mapbox provides [extensive tutorials](https://www.mapbox.com/help/getting-started-mapbox-studio-1/) on creating custom maps.


To use a Mapbox map as a StoryMapJS base map:



1.  In Mapbox, choose the Style you wish to use. On the Style's page, click "Share, develop & use" (right column).
1.  Locate the "Use style in GIS apps" block. Select "CartoDB" and copy the URL in the textbox. ![mapbox interface](images/mapbox.png#right#60)
1.  In the StoryMapJS Options, select "Mapbox" in the "Map Type" field.
1.  Paste the Mapbox URL into the URL field under "Map Type" in StoryMapJS.
1.  Close the popup window to save your changes and test the base map.

If you are using a non-Mapbox tiled map as a custom StoryMapJS base map: 

1. Put your tiles on a server. Currently, it is possible to use Box this way, but you will need to put the folder with the image tiles in a public folder and get the url from the "share" link. **Do not use the link in the browser window.**
1. Choose "Options" and select "custom" in the "Map Type" menu.
1. Enter the url from the "share" tool in the url window below the "Map Type" menu.


### Using a Gigapixel Image 

Rather than using a map as the base and creating a geospatial narrative, you might wish to annotate an image or create a (non-geo)spatial narrative using an image other than a base map. This can be done using a [gigapixel image](https://en.wikipedia.org/wiki/Gigapixel_image). Here's an example: [https://StoryMap.knightlab.com/examples/bosch-garden/](https://storymap.knightlab.com/examples/bosch-garden/). 

StoryMapJS provides instructions for several methods for creating the gigapixel image tiles that are required to use the image in a StoryMap: [https://StoryMap.knightlab.com/gigapixel/](https://storymap.knightlab.com/gigapixel/). We recommend following the instructions for exporting a "Zoomify" image from Photoshop that can be found in the "show me how" link.


## Resources 

*   Get more answers & how-tos: [https://StoryMap.knightlab.com/#help](https://storymap.knightlab.com/#help) 
*   Follow StoryMapJS latest issues & news: [http://knightlab.northwestern.edu/tag/StoryMapjs/](http://knightlab.northwestern.edu/tag/storymapjs/) 
*   Access the code: [https://github.com/NUKnightLab/StoryMapJS](https://github.com/NUKnightLab/StoryMapJS)
*   Video Tutorials:

    *   [Introduction to StoryMapJS](https://youtu.be/T-C64JO7lMg). September 30, 2015.
    *   [How to create an immersive Gigapixel image in StoryMap.](https://youtu.be/Nbk5yc3ybUg) April 28, 2014.
*   A list of other interactive storytelling tools: [https://wp.nyu.edu/digitalgallatin/tools/storytelling/](https://wp.nyu.edu/digitalgallatin/category/all-tools/storytelling/). 

*   Research on StoryMapJS & Interactive Storytelling:
    *   Huffman, Suzanne and Katherine Perdue. "The Interactive Experience: Exploring Technologies for Creating Touchscreen Exhibits." _MARAC Conference_, Roanoke, VA. October 7-10, 2015. [http://drum.lib.umd.edu/handle/1903/18488](http://drum.lib.umd.edu/handle/1903/18488).
    *   Mellon, Christopher J. "Combat Stories: creating a web-based geospatial interface to record combat stories for validation and other research purposes." _Naval Postgraduate School Capstone Project_. June 2015. [http://calhoun.nps.edu/bitstream/handle/10945/45906/15Jun_Mellon_Christopher.pdf?sequence=1&isAllowed=y](http://calhoun.nps.edu/bitstream/handle/10945/45906/15Jun_Mellon_Christopher.pdf?sequence=1&isAllowed=y). 
    *   Niederstadt, Leah, Jade Werner, Domingo Ledezma, and Jenni Lund. "Mapping in the Humanities Classroom: An Assessment of Tools and Strategies." _Blended Learning in the Liberal Arts Conference_. May 19, 2016. [http://repository.brynmawr.edu/blended_learning/2016/2016/18/](http://repository.brynmawr.edu/blended_learning/2016/2016/18/)  

<!-- GD2md-html version 1.0β11 -->