# Ex09 Event Registration Web Application
## Date:06.10.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
page 1
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="image" src="img/image-1.png" />
      <div class="text-wrapper">HOSTEL FEST</div>
      <div class="rectangle"></div>
      <div class="div">REGISTER</div>
    </div>
  </body>
</html>

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

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 497px;
  min-height: 1080px;
  position: relative;
}

.iphone-pro-max .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 497px;
  height: 1080px;
  aspect-ratio: 0.66;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 354px;
  left: 95px;
  width: 415px;
  font-family: "Jacques Francois Shadow-Regular", Helvetica;
  font-weight: 400;
  color: #f70707;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 489px;
  left: 76px;
  width: 346px;
  height: 81px;
  background-color: #8c7e7e;
  border-radius: 7px;
}

.iphone-pro-max .div {
  position: absolute;
  top: 506px;
  left: 145px;
  font-family: "Jacques Francois-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}
page 2
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="image" src="img/image-2.png" />
      <p class="MEHANDI-FACE">
        MEHANDI<br /><br />FACE PAINTING<br /><br />SOLO DANCE<br /><br />GROUP DANCE<br /><br />RAMP&nbsp;&nbsp;WALK<br /><br />GIBBERISH
        SINGING<br /><br />MUDINJA KANDUPUDI
      </p>
      <div class="text-wrapper">EVENTS</div>
    </div>
  </body>
</html>

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

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.iphone-pro-max .MEHANDI-FACE {
  position: absolute;
  top: 172px;
  left: 31px;
  width: 412px;
  font-family: "Jacques Francois-Regular", Helvetica;
  font-weight: 400;
  color: #f01b1b;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 48px;
  left: 78px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #dc1313;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

page 3
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="text-wrapper">REGISTRATION FORM</div>
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">NAME</div>
      <div class="text-wrapper-3">NUMBER</div>
      <div class="text-wrapper-4">EMAIL ID</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-5">SUBMIT</div>
    </div>
  </body>
</html>

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

.iphone-pro-max {
  background-image: url(./img/iphone-16-pro-max-4.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 51px;
  left: 22px;
  font-family: "Hanalei Fill-Regular", Helvetica;
  font-weight: 400;
  color: #df1414;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle {
  top: 156px;
  left: 7px;
  width: 426px;
  background-color: #867d7d;
  position: absolute;
  height: 79px;
  border-radius: 7px;
}

.iphone-pro-max .div {
  top: 251px;
  left: 7px;
  width: 426px;
  background-color: #867d7d;
  position: absolute;
  height: 79px;
  border-radius: 7px;
}

.iphone-pro-max .rectangle-2 {
  top: 346px;
  left: 7px;
  width: 426px;
  background-color: #867d7d;
  position: absolute;
  height: 79px;
  border-radius: 7px;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 171px;
  left: 126px;
  width: 187px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 261px;
  left: 90px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 356px;
  left: 90px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-3 {
  top: 478px;
  left: 74px;
  width: 291px;
  background-color: #cc1515;
  position: absolute;
  height: 79px;
  border-radius: 7px;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 488px;
  left: 134px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

page 4
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="image" src="img/image-3.png" />
      <div class="CONTACT-US">CONTACT&nbsp;&nbsp;US</div>
      <div class="secfest-gmail-com">secfest@gmail.com<br /><br />9977654666<br /><br />9952685666</div>
    </div>
  </body>
</html>

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

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.71;
  object-fit: cover;
}

.iphone-pro-max .CONTACT-US {
  position: absolute;
  top: 57px;
  left: 25px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #eb0a0a;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .secfest-gmail-com {
  position: absolute;
  top: 227px;
  left: 46px;
  width: 428px;
  font-family: "Kdam Thmor Pro-Regular", Helvetica;
  font-weight: 400;
  color: #e80b0b;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}
```

## OUTPUT:

![alt text](<Screenshot 2025-10-06 141838.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
