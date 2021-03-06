# ForeFlight[^1] KRNT[^2] content pack[^3]

## Disclaimer

The information on this website is for general informational purposes only. I makes no representation or warranty, express or implied. Your use of the site is solely at your own risk. This site may contain links to third party content, which we do not warrant, endorse, or assume liability for.

***The pilot in command of an aircraft is directly responsible for, and is the final authority as to, the operation of that aircraft.***

## Renton Municipal Airport Pack 1

The content pack has some useful layers that can be displade on the map.

### Whats in the content pack?

- Practice areas
  - Bainbridge
  - Enumclaw
  - Kitsap
  - Sammamish
- Range circles centered at KRNT
  - 25 NM
  - 50 NM
- VFR Checkpoints
  - Multiple checkpoints inside the 25 NM range circle

#### VFR Checkpoints

I am using the Seattle flyway chart to find those locations that have the little flag pinned to a location.  These are called *"VFR Checkpoints"*.  The underline indicates proper name of the VFR Checkpoint.  Check out the [Areonautical Chart Users' Guide - VFR Charting Products](https://aeronav.faa.gov/user_guide/20220324/cug-visual-edition.pdf) for more information.  Flyway planning charts depict flight paths and altitudes recommended for use to bypass high traffic areas. Ground references are provided as a guide for visual orientation. Flyway planning charts are designed for use in conjunction with TACs and sectional charts and are not to be used for navigation.

So why create all of these?  Well despite living in the area for most of my life, driving somewhere and flying above the same area is just different mental map, at least it is for me.  The checkpoints, unless they have a parenthesised VP* label, can't be used in ForeFlight or a Garmin GPS.  When I need to call ATC, I want to be able to tell them where I am at.

As of May 10, 2022, the checkpoints within the a 25NM radius of KRNT have been added.

## How to install this content pack

Please reference ForeFlight's page for how on [IMPORTING CONTENT PACKS](https://foreflight.com/support/content-packs/).  You will have to scroll down to the bottom 1/3 of the web page to find the different options.  Below is how to import via email in case the webpage becomes invalid.

1. Send the "Renton Municipal Airport Pack 1.zip" file as an email attachment to yourself.
2. Import the file into ForeFlight by opening the email in the Apple Mail app and tap-hold on the attachment.  After the share modal appears, scroll through the app list in the middle until you reach ForeFlight, then tap "Copy to ForeFlight".  This will open ForeFlight and add the content pack in More > Custom Content.

If there is no .zip file, you can create one by zipping the content pack directory you want (i.e.  Renton Municipal Airport Pack 1)

## How this content was made

### Setup

I can't take credit for process, I found that on reddit[^5] [here](https://www.reddit.com/r/flying/comments/9r75er/how_to_geo_referenced_sectional_charts_in_google/).  The basic process outline is as follows.

1. Install Google Earth Pro[^4]
2. Download the GEO-TIFF zip file containing the sectional or tac chart you want to mark-up.
3. Unzip the GEO-TIFF file
4. Open the .tif file in Google Earth Pro
5. Select create a super overlay from the pop-up

### Process

The rest is using Google Earth Pro to do the markup.  Use the ruler to create the circles or the practice areas.  Then save the polygons, circles, etc. as a .kml or .kmz (a zipped .kml) file.  I'm using .kml since the pack itself is zipped.

The VFR Checkpoints I put in single layer, instead of each checkpoint.

[^1]:[ForeFlight](https://foreflight.com/)
[^2]:[Renton Municipal Airport](https://rentonwa.gov/city_hall/public_works/renton_municipal_airport)
[^3]:[ForeFlight Content Packs](https://foreflight.com/products/foreflight-mobile/user-content/content-packs/)
[^4]:[Google Earth Prod on desktop](https://www.google.com/earth/versions/#earth-pro)
[^5]:[Reddit](https://www.reddit.com/)
