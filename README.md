# Ex08 Event Registration Web Application
## Date: 19-12-25

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
PAGE 1

index.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-mini">
      <img
        class="pngtree-hand-painted"
        src="img/pngtree-hand-painted-cool-volleyball-sports-club-poster-background-material-picture-image-1127055-1.png"
      />
      <img class="sav" src="img/sav-1.png" />
      <img class="sav-log" src="img/sav-log-1.png" />
      <div class="text-wrapper">SPORTS DAY REGISTRATION</div>
      <div class="rectangle"></div>
      <div class="div">Login</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">@ AKILA S (25018659)</div>
    </div>
  </body>
</html>

global.css

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
  outline: 2px solid #4a90e2 ;
  outline: -webkit-focus-ring-color auto 5px ;
}
a {
  text-decoration: none;
}

style.css

.iphone-mini {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 375px;
  min-height: 812px;
  position: relative;
}

.iphone-mini .pngtree-hand-painted {
  position: absolute;
  top: 0;
  left: 0;
  width: 371px;
  height: 812px;
  aspect-ratio: 0.46;
  object-fit: cover;
}

.iphone-mini .sav {
  position: absolute;
  top: 0;
  left: 0;
  width: 373px;
  height: 91px;
  aspect-ratio: 4.09;
  object-fit: cover;
}
.iphone-mini .sav-log {
  position: absolute;
  top: 148px;
  left: 96px;
  width: 184px;
  height: 184px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone-mini .text-wrapper {
  position: absolute;
  top: 105px;
  left: 36px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: 15px;
}

.iphone-mini .rectangle {
  position: absolute;
  top: 389px;
  left: 22px;
  width: 327px;
  height: 76px;
  background-color: #e7e5e5;
  border: 1px solid;
  border-color: #cfbfbf;
  backdrop-filter: blur(2px) brightness(100%);
  -webkit-backdrop-filter: blur(2px) brightness(100%);
  opacity: 0.5;
}
.iphone-mini .div {
  position: absolute;
  top: 420px;
  left: 113px;
  width: 150px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: 10px;
}

.iphone-mini .rectangle-2 {
  position: absolute;
  top: 794px;
  left: 0;
  width: 371px;
  height: 25px;
  background-color: #d9d9d9;
}

.iphone-mini .text-wrapper-2 {
  position: absolute;
  top: 797px;
  left: 113px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

PAGE 2

index.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-mini">
      <img
        class="pngtree-colorful"
        src="img/pngtree-colorful-sports-theme-background-material-picture-image-1636814-1.png"
      />
      <div class="text-wrapper">1500 M</div>
      <img class="star" src="img/star-11.svg" />
      <div class="div">RELAY</div>
      <div class="text-wrapper-2">400 m</div>
      <div class="text-wrapper-3">KABADDI</div>
      <p class="SELECT-EVENTS-YOU">
        &nbsp;&nbsp;*&nbsp;&nbsp;SELECT&nbsp;&nbsp;EVENTS YOU WANT TO PARTICIPATE <br /><br />&nbsp;&nbsp; *
        MAXIMUM&nbsp;&nbsp;THREE EVENTS CAN BE SELECTED
      </p>
      <img class="sav" src="img/sav-2.png" />
      <div class="SPOTS-DAY-EVENTS">SPOTS DAY&nbsp;&nbsp;EVENTS</div>
      <img class="img" src="img/star-1.svg" />
      <img class="star-2" src="img/star-2.svg" />
      <img class="star-3" src="img/star-3.svg" />
      <img class="star-4" src="img/star-4.svg" />
      <img class="star-5" src="img/star-5.svg" />
      <img class="star-6" src="img/star-6.svg" />
      <img class="star-7" src="img/star-7.svg" />
      <div class="text-wrapper-4">CRICKET</div>
      <div class="text-wrapper-5">VOLLEYBALL</div>
      <div class="text-wrapper-6">FOOTBALL</div>
      <div class="text-wrapper-7">TENNIS</div>
      <div class="text-wrapper-8">BASKETBALL</div>
      <img class="star-8" src="img/star-9.svg" />
      <img class="star-9" src="img/star-10.svg" />
      <div class="rectangle"></div>
      <div class="text-wrapper-9">NEXT</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-10">@ AKILA S (25018659)</div>
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

.iphone-mini {
  background-color: #ffffff;
  width: 100%;
  min-width: 375px;
  min-height: 812px;
  position: relative;
}

.iphone-mini .pngtree-colorful {
  position: absolute;
  top: 0;
  left: 0;
  width: 375px;
  height: 812px;
  aspect-ratio: 0.54;
  object-fit: cover;
}

.iphone-mini .text-wrapper {
  position: absolute;
  top: 539px;
  left: 79px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .star {
  position: absolute;
  top: 532px;
  left: 49px;
  width: 21px;
  height: 21px;
}

.iphone-mini .div {
  position: absolute;
  top: 503px;
  left: 79px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .text-wrapper-2 {
  position: absolute;
  top: 465px;
  left: 79px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .text-wrapper-3 {
  position: absolute;
  top: 431px;
  left: 81px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .SELECT-EVENTS-YOU {
  position: absolute;
  top: 162px;
  left: 45px;
  font-family: "Akaya Telivigala-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 10px;
}

.iphone-mini .sav {
  position: absolute;
  top: 0;
  left: 0;
  width: 375px;
  height: 93px;
  aspect-ratio: 4.09;
  object-fit: cover;
}

.iphone-mini .SPOTS-DAY-EVENTS {
  position: absolute;
  top: 114px;
  left: 98px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: 10px;
}

.iphone-mini .img {
  position: absolute;
  top: 244px;
  left: 49px;
  width: 21px;
  height: 21px;
}

.iphone-mini .star-2 {
  position: absolute;
  top: 280px;
  left: 49px;
  width: 21px;
  height: 21px;
}

.iphone-mini .star-3 {
  position: absolute;
  top: 276px;
  left: 59px;
  width: 1px;
  height: 4px;
}

.iphone-mini .star-4 {
  position: absolute;
  top: 316px;
  left: 49px;
  width: 21px;
  height: 21px;
}

.iphone-mini .star-5 {
  position: absolute;
  top: 352px;
  left: 49px;
  width: 21px;
  height: 21px;
}

.iphone-mini .star-6 {
  position: absolute;
  top: 388px;
  left: 49px;
  width: 21px;
  height: 21px;
}

.iphone-mini .star-7 {
  position: absolute;
  top: 424px;
  left: 49px;
  width: 21px;
  height: 21px;
}

.iphone-mini .text-wrapper-4 {
  position: absolute;
  top: 249px;
  left: 81px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 10px;
}

.iphone-mini .text-wrapper-5 {
  position: absolute;
  top: 356px;
  left: 79px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .text-wrapper-6 {
  position: absolute;
  top: 284px;
  left: 81px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .text-wrapper-7 {
  position: absolute;
  top: 320px;
  left: 81px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .text-wrapper-8 {
  position: absolute;
  top: 390px;
  left: 79px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .star-8 {
  position: absolute;
  top: 496px;
  left: 52px;
  width: 21px;
  height: 21px;
}

.iphone-mini .star-9 {
  position: absolute;
  top: 460px;
  left: 49px;
  width: 21px;
  height: 21px;
}

.iphone-mini .rectangle {
  position: absolute;
  top: 650px;
  left: 229px;
  width: 116px;
  height: 40px;
  background-color: #ff5e5e;
  box-shadow: 0px 4px 4px #00000040;
}

.iphone-mini .text-wrapper-9 {
  position: absolute;
  top: 665px;
  left: 270px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .rectangle-2 {
  position: absolute;
  top: 795px;
  left: 0;
  width: 375px;
  height: 17px;
  background-color: #d9d9d9;
}

.iphone-mini .text-wrapper-10 {
  position: absolute;
  top: 799px;
  left: 120px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

PAGE 3

index.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-mini">
      <img
        class="pngtree-colorful"
        src="img/pngtree-colorful-sports-theme-background-material-picture-image-1636814-1-1.png"
      />
      <div class="rectangle"></div>
      <div class="text-wrapper">GENDER</div>
      <div class="div"></div>
      <div class="text-wrapper-2">AGE</div>
      <img class="sav" src="img/sav-3.png" />
      <div class="text-wrapper-3">EVENT REGISTRATION FORM</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-4">FULL NAME</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-5">DEPARTMENT</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-6">REGISTER NO</div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-7">MOBILE NO</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="text-wrapper-8">EMAIL ID</div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-9">REGISTER</div>
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
  outline: 2px solid #4a90e2;
  outline: -webkit-focus-ring-color auto 5px ;
}
a {
  text-decoration: none;
}

style.css

.iphone-mini {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 375px;
  min-height: 812px;
  position: relative;
}

.iphone-mini .pngtree-colorful {
  position: absolute;
  top: 5px;
  left: 0;
  width: 375px;
  height: 802px;
  aspect-ratio: 0.5;
  object-fit: cover;
}

.iphone-mini .rectangle {
  position: absolute;
  top: 206px;
  left: 30px;
  width: 155px;
  height: 22px;
  background-color: #d9d9d9;
}
.iphone-mini .text-wrapper {
  position: absolute;
  top: 212px;
  left: 65px;
  font-family: "Bacasime Antique-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .div {
  position: absolute;
  top: 251px;
  left: 30px;
  width: 155px;
  height: 22px;
  background-color: #d9d9d9;
}
.iphone-mini .text-wrapper-2 {
  position: absolute;
  top: 257px;
  left: 85px;
  font-family: "Bacasime Antique-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .sav {
  position: absolute;
  top: 5px;
  left: 4px;
  width: 368px;
  height: 90px;
  aspect-ratio: 4.09;
  object-fit: cover;
}

.iphone-mini .text-wrapper-3 {
  position: absolute;
  top: 113px;
  left: 58px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}
.iphone-mini .rectangle-2 {
  position: absolute;
  top: 161px;
  left: 30px;
  width: 155px;
  height: 22px;
  background-color: #d9d9d9;
}

.iphone-mini .text-wrapper-4 {
  position: absolute;
  top: 167px;
  left: 51px;
  font-family: "Bacasime Antique-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .rectangle-3 {
  position: absolute;
  top: 294px;
  left: 30px;
  width: 155px;
  height: 22px;
  background-color: #d9d9d9;
}
.iphone-mini .text-wrapper-5 {
  position: absolute;
  top: 300px;
  left: 51px;
  font-family: "Bacasime Antique-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .rectangle-4 {
  position: absolute;
  top: 336px;
  left: 30px;
  width: 155px;
  height: 22px;
  background-color: #d9d9d9;
}

.iphone-mini .text-wrapper-6 {
  position: absolute;
  top: 341px;
  left: 58px;
  width: 101px;
  font-family: "Bacasime Antique-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}
.iphone-mini .rectangle-5 {
  position: absolute;
  top: 377px;
  left: 30px;
  width: 155px;
  height: 22px;
  background-color: #d9d9d9;
}

.iphone-mini .rectangle-6 {
  position: absolute;
  top: 420px;
  left: 30px;
  width: 155px;
  height: 22px;
  background-color: #d9d9d9;
}

.iphone-mini .text-wrapper-7 {
  position: absolute;
  top: 426px;
  left: 58px;
  font-family: "Bacasime Antique-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}
.iphone-mini .text-on-a-path {
  position: absolute;
  top: 373px;
  left: -1038px;
  width: 155px;
  height: 22px;
}

.iphone-mini .text-wrapper-8 {
  position: absolute;
  top: 383px;
  left: 69px;
  font-family: "Bacasime Antique-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

.iphone-mini .rectangle-7 {
  position: absolute;
  top: 651px;
  left: 230px;
  width: 123px;
  height: 40px;
  background-color: #ff5e5e;
  box-shadow: 0px 4px 4px #00000040;
}
.iphone-mini .text-wrapper-9 {
  position: absolute;
  top: 666px;
  left: 258px;
  font-family: "Agbalumo-Regular", Helvetica;
  font-weight: 400;
  color: #181616;
  font-size: 15px;
  letter-spacing: 0;
  line-height: 10px;
  white-space: nowrap;
}

PAGE 4

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-mini">
      <p class="thank-you-for">
        “Thank you for registering!<br /><br /><br /><br />
        Train hard, play fair, and give it your all.<br /><br /><br /><br />
        See you on the field!”
      </p>
      <img
        class="a-group-of-people"
        src="img/a-group-of-people-playing-basketball-on-a-colorful-background-photo-1.png"
      />
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


.iphone-mini {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 375px;
  min-height: 812px;
  display: flex;
  flex-direction: column;
}

.iphone-mini .thank-you-for {
  margin-left: 5px;
  width: 386px;
  height: 110px;
  margin-top: 99px;
  font-family: "ADLaM Display-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: 10px;
}

.iphone-mini .a-group-of-people {
  width: 375px;
  height: 603px;
  aspect-ratio: 1.08;
  object-fit: cover;
}
```

## OUTPUT:

![alt text](<Screenshot 2025-12-19 235101.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
