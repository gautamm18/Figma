# Ex08 Event Registration Web Application
## Date:27-12-2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
page-1

index.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="back-figma" src="img/back-figma-1.png" />
      <img class="sec-logo" src="img/sec-logo-1.png" />
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="text-wrapper">login</div>
      <div class="text-wrapper-2">username</div>
      <div class="text-wrapper-3">password</div>
      <img class="whatsapp-image" src="img/whatsapp-image-2025-12-27-at-9-13-39-AM-1.png" />
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}

button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .back-figma {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.66;
  object-fit: cover;
}

.iphone-pro-max .sec-logo {
  position: absolute;
  top: 249px;
  left: 116px;
  width: 225px;
  height: 225px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone-pro-max .rectangle {
  top: 570px;
  left: 52px;
  width: 336px;
  height: 59px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .div {
  top: 675px;
  left: 55px;
  width: 333px;
  height: 60px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 499px;
  left: 52px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #0c0c0c;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 577px;
  left: 142px;
  width: 131px;
  font-family: "Indie Flower-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 674px;
  left: 142px;
  font-family: "Indie Flower-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .whatsapp-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 93px;
  aspect-ratio: 4.97;
  object-fit: cover;
}


Page-2

index.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="screenshot" src="img/screenshot-2025-12-27-093050-1.png" />
      <div class="text-wrapper">EVENTS</div>
      <div class="div">BADMINTON</div>
      <div class="text-wrapper-2">FOOTBALL</div>
      <div class="text-wrapper-3">KABADDI</div>
      <div class="text-wrapper-4">TABLE TENNIS</div>
      <div class="text-wrapper-5">RELAY</div>
      <img class="polygon" src="img/polygon-1.svg" />
      <img class="img" src="img/polygon-2.svg" />
      <img class="polygon-2" src="img/polygon-3.svg" />
      <img class="polygon-3" src="img/polygon-4.svg" />
      <img class="polygon-4" src="img/polygon-5.svg" />
      <img class="whatsapp-image" src="img/whatsapp-image-2025-12-27-at-9-13-39-AM-4.png" />
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.53;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 157px;
  left: 131px;
  width: 146px;
  font-family: "Bowlby One-Regular", Helvetica;
  font-weight: 400;
  color: #840606;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 257px;
  left: 55px;
  font-family: "Bowlby One-Regular", Helvetica;
  font-weight: 400;
  color: #141313;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 359px;
  left: 55px;
  font-family: "Bowlby One-Regular", Helvetica;
  font-weight: 400;
  color: #9a7d2e;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 450px;
  left: 55px;
  width: 167px;
  font-family: "Bowlby One-Regular", Helvetica;
  font-weight: 400;
  color: #871476;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 550px;
  left: 55px;
  font-family: "Bowlby One-Regular", Helvetica;
  font-weight: 400;
  color: #28de1b;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 630px;
  left: 55px;
  font-family: "Bowlby One-Regular", Helvetica;
  font-weight: 400;
  color: #9068c5;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .polygon {
  top: 273px;
  position: absolute;
  left: 3px;
  width: 37px;
  height: 26px;
}

.iphone-pro-max .img {
  top: 646px;
  position: absolute;
  left: 3px;
  width: 37px;
  height: 26px;
}

.iphone-pro-max .polygon-2 {
  top: 558px;
  position: absolute;
  left: 3px;
  width: 37px;
  height: 26px;
}

.iphone-pro-max .polygon-3 {
  top: 461px;
  position: absolute;
  left: 3px;
  width: 37px;
  height: 26px;
}

.iphone-pro-max .polygon-4 {
  top: 367px;
  position: absolute;
  left: 3px;
  width: 37px;
  height: 26px;
}

.iphone-pro-max .whatsapp-image {
  position: absolute;
  top: 4px;
  left: 0;
  width: 440px;
  height: 93px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

Page-3

index.html


<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="element" src="img/3rd-1.png" />
      <div class="where-sportsmanship">Where Sportsmanship <br />Meets Adrenaline&#34;.</div>
      <img class="whatsapp-image" src="img/whatsapp-image-2025-12-27-at-9-13-39-AM-3.png" />
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 955px;
  position: relative;
}

.iphone-pro-max .element {
  position: absolute;
  top: 1px;
  left: 1px;
  width: 440px;
  height: 955px;
  aspect-ratio: 0.75;
  object-fit: cover;
}

.iphone-pro-max .where-sportsmanship {
  position: absolute;
  top: 363px;
  left: 21px;
  width: 397px;
  font-family: "Bona Nova SC-Regular", Helvetica;
  font-weight: 400;
  color: #151414;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .whatsapp-image {
  position: absolute;
  top: 1px;
  left: 0;
  width: 440px;
  height: 93px;
  aspect-ratio: 4.97;
  object-fit: cover;
}


Page-4

index.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="whatsapp-image" src="img/whatsapp-image-2025-12-27-at-9-13-39-AM-2.png" />
      <img class="sports" src="img/sports-1.png" />
      <div class="text-wrapper">Registration form</div>
      <div class="rectangle"></div>
      <img class="img" src="img/rectangle-5.svg" />
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-2">Full name</div>
      <div class="text-wrapper-3">Email ID</div>
      <div class="text-wrapper-4">Mobile no.</div>
      <div class="text-wrapper-5">Department</div>
      <div class="text-wrapper-6">Gender</div>
      <div class="text-wrapper-7">Register no.</div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-8">SUBMIT</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .whatsapp-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 93px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.iphone-pro-max .sports {
  position: absolute;
  top: 93px;
  left: 0;
  width: 440px;
  height: 863px;
  aspect-ratio: 0.7;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 171px;
  left: 9px;
  font-family: "JejuHallasan-Regular", Helvetica;
  font-weight: 400;
  color: #2a1e1e;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 249px;
  left: 30px;
  width: 378px;
  height: 72px;
  background-color: #d9d9d9;
}

.iphone-pro-max .img {
  position: absolute;
  top: 260px;
  left: 30px;
  width: 378px;
  height: 535px;
}

.iphone-pro-max .div {
  position: absolute;
  top: 627px;
  left: 30px;
  width: 378px;
  height: 72px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 531px;
  left: 30px;
  width: 378px;
  height: 72px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 435px;
  left: 30px;
  width: 378px;
  height: 72px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 339px;
  left: 30px;
  width: 378px;
  height: 72px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 255px;
  left: 52px;
  font-family: "JejuHallasan-Regular", Helvetica;
  font-weight: 400;
  color: #322929;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 735px;
  left: 52px;
  font-family: "JejuHallasan-Regular", Helvetica;
  font-weight: 400;
  color: #322929;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 639px;
  left: 52px;
  font-family: "JejuHallasan-Regular", Helvetica;
  font-weight: 400;
  color: #322929;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 543px;
  left: 52px;
  font-family: "JejuHallasan-Regular", Helvetica;
  font-weight: 400;
  color: #322929;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 351px;
  left: 52px;
  font-family: "JejuHallasan-Regular", Helvetica;
  font-weight: 400;
  color: #322929;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 447px;
  left: 52px;
  font-family: "JejuHallasan-Regular", Helvetica;
  font-weight: 400;
  color: #322929;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 801px;
  left: 41px;
  width: 357px;
  height: 77px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-8 {
  position: absolute;
  top: 819px;
  left: 118px;
  font-family: "JejuHallasan-Regular", Helvetica;
  font-weight: 400;
  color: #665252;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}


```

## OUTPUT:
![alt text](<Screenshot 2025-12-27 115644.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
