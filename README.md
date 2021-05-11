# horiseon-seo-project

## Table of Contents
- [Description](#Description)
- [HTML](#HTML)
- [CSS](#CSS)
- [Usage](#Usage)
- [Conclusion](#Conclusion)
## Description
The goal of this project is to refactor both the HTML and CSS.

We were given a webpage with a good layout, but there still were some major problems on the back end. There was little to no semantic value, the navigation bar did not function as intended, the CSS was not in order with HTML, etc...

After refactoring the website, navigating the CSS should follow the order of the HTML. The website should load much faster. Most importantly, it will be a better expirance for the user, and an easier time for programmers to modify.


## HTML
Here are my changes to the HTML file to improve functionality and semantic value.
- Changed "div" tags as well as classes that marked major parent groups to establish a header, footer, abbr, nav, aside, article, sections within the aside and article
- Corrected the squence the header tags (h1,h2,h3,etc) go in
- Added alt text to images, as well as adding a title to the "abbr"
- Added id's to fix navigation bar, as the link was refering to an id that did not exsist
- Gave the head a title, instead of "website"
- Added spacing between major sections of HTML to help differentiate those sections from each other
- Made proper indentations to help so parent/child relation


## CSS
My goal with CSS was to reduce redundant atriutes and combine them with one another. I also had to change the tags and classes that were being targeted as I changed the parent tag to something more semantic in the HTML.
- I organized the CSS to flow with the sequence that the HTML does, so that the Header is at the top, body is in the middle, and footer at the bottom
- There were redundantcies with the CSS of classes that established sections of both the article and aside that merged together and then changed the tag to something more semantic
- Added hover atribute to nav bar


## Usage
While using the webpage, there were extremely long load times. This was due to the extremely large image files that were being displayed. In total the sum of memory of the images before resizing was approximatley 50 MegaBytes! This means that any time someone comes to this site or refreshes will have to load 50MB of data, causing over 30 seconds of load time for moblie users. Resizing the images reduced this large number down from 50 to just barely over 1MB.

I also added a hover atribute to the navigation bar to have a more responsive webpage that lets the user see that the links are clickable.

I also added comments to help explain to anyone else where they are within the HTML, and what the atributes do in CSS. Helping any other programmers maneuver the code.


## Conclusion
Overall the refactoring of this website was, in my opinion, a success. The webpage looks the same as when I initially receive it, but operates in a much more efficient manner. Load times are down. The navigation bar works. The HTML and CSS are clear and concise void of repeition. I believe I have created a better experience for both the consumer and the devolper.