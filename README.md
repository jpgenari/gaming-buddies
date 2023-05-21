# Gaming Buddies

Gaming Buddies is a website born to help gamers in Dublin and surroundings to find other gamers with either similar or different interests to chat about their favourite games, consoles, new releases and most important, to play together in a healthy and respectful environment - no console-war is allowed here :smiley: - creating a friendly and supportive local community.

Its idea came around with the release on the newest Nintendo game, Zelda Tears of The Kingdom, when our founding-member Joao could not find among his friends anyone who is a gamer to play or at least talk about it.

We do value our online gaming buddies, however, we also want to meet out buddies in person, come play with us!

![Responsive Mockup](/assets/images/gaming-buddies-mockup.png) 

## Features

### Existing Features

- __Navigation Bar__

  - A full responsive navigation bar including links to the Logo and the main elements Home, Who We Are, Join Us! and Meet up - navigation elements responsive when hovering over.

  - The bar fixed at the top of the page allowing easy navigation when users scroll through the page elements across all devices, with a responsive design.

![Logo and Nav Bar](/assets/images/gaming-buddies-logo-and-nav.png)

- __The landing page image__

  - The landing page features a photograph representing the core idea behind the website showing friends playing together and having fun.

  - It also includes a text overlay allowing users to reinforce the website purpose.

![Landing Page](/assets/images/gaming-buddies-hero-image.png)

- __Who We Are section__

  - The Who We Are section allows the users to see the website gaming community purpose and what they will find when joining the community. They will also see quick steps to join and a challenging question in order to engage them.

  - The section also features an image showing a fliperama control board to captivate them to play games on site.

![Who We Are Section](/assets/images/gaming-buddies-who-we-are.png)

- __Want To Join Us section__

  - This section will allow users to get signed up to Gaming Buddies to join the gaming community. Users will be able to provide their video game platform - console - which should facilitate matching gamers for discussions and game play. Users will also be providing full name and email address.

  - The section also features an image showing a man and a woman playing together to incentivize all ages to participate.

![Want to Join Us Section](/assets/images/gaming-buddies-want-to-joinus.png)

- __Meet Up section__

  - This section will allow users to know about regular meet ups for community including dates, time and location. There will also see an embedded Google Maps containing the location for easier navigation.

  - This section contain a background image showing a portable video-game, this image alongside all the previous images intend to promote diversity for games and players.

![Meet Up Section](/assets/images/gaming-buddies-meet-up.png)

- __The Footer__

  - The footer section includes links to the relevant social media sites for Gaming Buddies. The links will open to a new tab to allow easy navigation for users.

  - The footer will is fixed to the bottom of the page to keep default standard layout following fixed header. This feature is removed for mobile placements for optimization of users view point.

  - The footer will be valuable to users as it will encourage them to keep connected via social media.

![Footer Section](/assets/images/gaming-buddies-footer.png)

### Features Left to Implement or Future Features

- __Gallery page / section__

    - This future feature will feature photographies shot from community meet ups.

- __New Games page / section__

    - This future section or page - as the scope grows the website main layout may require review - will contain information about all game releases for upcoming months.

- __Game Offers page / section__

    - This future section or page will contain local and online game and accessories offer available to help gamers - the section could also become a future income source for website maintenance.

- __Forum page / section__

    - This future section or page will allow users to discuss and find help online, also working as a Wiki for discussed information - storing discussions online.

## Testing

The website has been tested for its functionalities working as expected on multiple browsers and devices (mobile tested using Inspect tool).

### Workflow testing

- __Functionalities__
  
    - Website opens showing its header with both logo and menu nested inside it and landing page;
    - Hovering over menu items an underline shows up to indicate to the user button is clickable actionable;
    - Clicking on "Home" button leads to landing page and hero image section centralized to the viewpoint;
    - Clicking on "Who We Are" button leads to the who we are section centralized to the viewpoint;
    - Clicking on "Join Us!" button leads to the join us section centralized to the viewpoint;
      - Hovering over the text boxes should turn their boarders red to indicate action;
      - Hovering over the "START" or send button turns it into red to indicate button is clickable and actionable;
      - When clicking on the "START" or send button with boxes unfilled or filled with incorrect information (email address) or dropdown unselected, a warning message pops up on the first missing information item - preventing form to be submitted with missing information;
      - After clicking on the "START" or send button user is led to sign up confirmation page from Code Institute dump form showing submitted information.
    - Clicking on "Meet Up" button leads tp the meet up section centralized to the viewpoint;
    - On the embedded Google Maps, clicking on "Vier Larger Maps" opens a window leading to Google Maps with the address selected where the users can view directions to the meet up place.
    - Clicking on any social network icon nested inside footer opens a new window leading to the specific social network;
    - Scrolling down and up instead of clicking on menu buttons will move the viewpoint throughout the sections;
    - When navigating on the page either through navigation buttons or scrolling on desktop or tablet, both header and footer should stay fixed at the top and bottom respectively to facilitate navigation. On mobile, for viewpoin optimization the footer changes to relative position hidding when scrolling up.

- __Layout and Design__

[Am I Reponsive?](https://ui.dev/amiresponsive?url=https://jpgenari.github.io/gaming-buddies/index.html) shows all availble common layouts.

- __Tested Browsers and Devices__

    - Desktop:
      - Google Chrome
      - Mozilla Firefox
      - Apple Safari
    - Tablet *tested through Google Chrome Inspector*:
      - *iPad Air*
      - *iPad Mini*
      - *Surface Pro 7*
      - *Google Nest Hub* 
    - Mobile *tested through Google Chrome Inspector*:
      - iPhone 13 Pro (Google Chrome, Mozilla Firefox and Apple Safari)
      - *iPhone SE*
      - *iPhone XR*
      - *Pixel 5*
      - *Samsung Galaxy S8+*
      - *Samsung Galaxy S20 Ultra*

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjpgenari.github.io%2Fgaming-buddies%2Findex.html).
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjpgenari.github.io%2Fgaming-buddies%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en).
- Accessibility
 - No error  were found when passing through the official [WAVE evaluation tool](https://wave.webaim.org/report#/https://jpgenari.github.io/gaming-buddies/);
 - Scored 100 for Accessbility when passing through Google Chrome Inspector Lighthouse
![Lighthouse](/assets/images/gaming-buddies-lighthouse.png)


### Bugs

When developing the website multiple minor bugs came up specially, most of them related to making images fit and applying proper styling. However, two bugs stood up out as in order to fix them it was needed to make to the html structure alongside css.

__Solved Bugs__

- __Padding__
  - After achieving final design state and styling, when deploying the website it was noticed an extra white board withing the images while some of the text boxes where hitting the end of viewpointwith 100% width in mobile layout - the bug was not noticeable on desktop. With Inspect tool, it was flagged the bug was being caused by a 15px padding applied to the boxes only, pushing other content 15px from right side - removing the padding caused the text boxes to lose the padding between text and edge of borders also breaking the design.

    - Code example with bug:
  
    ```
    <section>
        <div id="image"></div>
        <div id="text-box" class="size positioning padding">
            <h2>text</h2>
        </div>
    </section>
    ```

    - Code example fixed:
  
    ```
    <section>
        <div id="image"></div>
        <div id="text-box" class="size positioning>
            <div class="padding">
                <h2>text</h2>
            </div>
        </div>
    </section>
    ```

  - A new div element was created inside the first div and the padding was applied to the enclosed div, making the padding to contained inside the parent div and respecting its size.
  
- __Google Maps iframe__
  - When running HTML checker W3C validator, the solution applied to make the iframe dynamic by applying its width and height to 100% - in order to force it to fit its div wraper - an error returned where % values were not valid.
  - Before applying the value 100% it had been tried to remove values from HTML and apply CSS rules, which did not work. After extra online research, the article [How to Create a Full-screen iFrame with 100% Height](https://www.tutorialrepublic.com/faq/how-to-create-a-full-screen-iframe-with-100-percent-height.php#:~:text=You%20can%20simply%20set%20the,height%20and%20width%20of%20100%25.) showed a solution which fixed the bug.
  
    ```
    .map-wrapper { /*div enclosing iframe*/
        width: 30%;
        height: 70%;
        top: 12%;
        left: 7%;
    }
    iframe {
        display: block; /*tag display: block made the width and height set on CSS control the iframe dimensions*/
        height: 100%;
        width: 100%;
    }
    ```

### Unfixed Bugs

  - On final development stage, it was tried to add a favicon to the website. When running the code either local or with CodeAnywhere preview it works as expected, however, when deployed on GitHub Pages it does not work. A few solutions have been tried without fixing the bug.

```
<link rel="shortcut icon" type="image/x-icon" href="/assets/images/favicon.ico">
```

## Deployment

- The website was deployed to GitHub pages. Follow below the stops taken:
  - In the GitHub repository, navigate to the Settings tab;
  - Go to the Pages settings, and under Source select on the drop-down menu, select the Main Branch and save;
  - After saving, hold on a little bit and the page will automatically refresh with the available url and a button to visit site.

The live link can be found here - <https://jpgenari.github.io/gaming-buddies/>

## Credits

### Content

- The webside base code was created based on the [CI Love Running](https://github.com/Code-Institute-Solutions/Love-Running-Solutions) project, with the 

### Media
