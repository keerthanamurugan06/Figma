# Ex08 Event Registration Web Application
## Date:23.12.25

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
Home page

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <img class="image" src="img/image-1.png" />
      <img class="screenshot" src="img/screenshot-2025-12-19-104847-1.png" />
      <img class="img" src="img/screenshot-2025-12-19-104552-2.png" />
      <img class="rectangle" src="img/rectangle-3.svg" />
      <div class="text-wrapper">CULTURAL EVENT</div>
      <img class="text-on-a-path" src="img/image.svg" />
      <img class="rectangle-2" src="img/rectangle-7.svg" />
      <img class="text-on-a-path-2" src="img/text-on-a-path.svg" />
      <img class="rectangle-3" src="img/rectangle-8.svg" />
      <div class="div">LOGIN</div>
      <div class="text-wrapper-2">REGISTER NOW</div>
      <div class="presented-by">Presented by:<br />Keerthana M</div>
    </div>
  </body>
</html>

.android-compact {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 470px;
  min-height: 917px;
  position: relative;
}

.android-compact .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 470px;
  height: 917px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.android-compact .screenshot {
  position: absolute;
  top: 112px;
  left: 99px;
  width: 274px;
  height: 278px;
  aspect-ratio: 0.99;
  object-fit: cover;
}

.android-compact .img {
  position: absolute;
  top: 11px;
  left: 10px;
  width: 450px;
  height: 90px;
  aspect-ratio: 5;
  object-fit: cover;
}

.android-compact .rectangle {
  position: absolute;
  top: 416px;
  left: 60px;
  width: 348px;
  height: 97px;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 439px;
  left: 85px;
  width: 302px;
  font-family: "Joti One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-on-a-path {
  position: absolute;
  top: 627px;
  left: 21px;
  width: 282px;
  height: 72px;
}

.android-compact .rectangle-2 {
  position: absolute;
  top: 656px;
  left: 85px;
  width: 288px;
  height: 85px;
}

.android-compact .text-on-a-path-2 {
  position: absolute;
  top: 538px;
  left: 25px;
  width: 282px;
  height: 72px;
}

.android-compact .rectangle-3 {
  position: absolute;
  top: 558px;
  left: 91px;
  width: 282px;
  height: 72px;
}

.android-compact .div {
  position: absolute;
  top: 548px;
  left: 169px;
  width: 204px;
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-2 {
  position: absolute;
  top: 684px;
  left: 137px;
  width: 220px;
  font-family: "Inder-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .presented-by {
  position: absolute;
  top: 821px;
  left: 221px;
  width: 272px;
  font-family: "Inria Serif-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

Event page

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <img class="image" src="img/image-2.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">CULTURAL DAY EVENTS</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-2">Fashion walk</div>
      <div class="text-wrapper-3">Played to perfection</div>
      <div class="text-wrapper-4">Drone show</div>
      <div class="text-wrapper-5">DJ Ninthin event</div>
      <div class="text-wrapper-6">College storm event</div>
      <div class="text-wrapper-7">Mismatch event</div>
      <img class="img" src="img/image-3.png" />
    </div>
  </body>
</html>

.android-compact {
  background-color: #ffffff;
  width: 100%;
  min-width: 471px;
  min-height: 917px;
  position: relative;
}

.android-compact .image {
  top: 0;
  left: 0;
  width: 471px;
  height: 917px;
  aspect-ratio: 0.56;
  position: absolute;
  object-fit: cover;
}

.android-compact .rectangle {
  position: absolute;
  top: 23px;
  left: 16px;
  width: 444px;
  height: 102px;
  background-color: #e719ee;
  border-radius: 20px;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 47px;
  left: 57px;
  width: 358px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .div {
  position: absolute;
  top: 148px;
  left: 38px;
  width: 356px;
  height: 69px;
  background-color: #ff69f0;
  border-radius: 300px;
}

.android-compact .rectangle-2 {
  position: absolute;
  top: 231px;
  left: 38px;
  width: 356px;
  height: 69px;
  background-color: #ff69f0;
  border-radius: 300px;
}

.android-compact .rectangle-3 {
  position: absolute;
  top: 314px;
  left: 38px;
  width: 356px;
  height: 69px;
  background-color: #ff69f0;
  border-radius: 300px;
}

.android-compact .rectangle-4 {
  position: absolute;
  top: 406px;
  left: 38px;
  width: 356px;
  height: 69px;
  background-color: #ff69f0;
  border-radius: 300px;
}

.android-compact .rectangle-5 {
  position: absolute;
  top: 490px;
  left: 38px;
  width: 356px;
  height: 69px;
  background-color: #ff69f0;
  border-radius: 300px;
}

.android-compact .rectangle-6 {
  position: absolute;
  top: 572px;
  left: 38px;
  width: 356px;
  height: 69px;
  background-color: #ff69f0;
  border-radius: 300px;
}

.android-compact .text-wrapper-2 {
  position: absolute;
  top: 162px;
  left: 63px;
  width: 280px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-3 {
  position: absolute;
  top: 241px;
  left: 63px;
  width: 352px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-4 {
  position: absolute;
  top: 328px;
  left: 63px;
  width: 272px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-5 {
  position: absolute;
  top: 425px;
  left: 63px;
  width: 307px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-6 {
  position: absolute;
  top: 505px;
  left: 63px;
  width: 331px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-7 {
  position: absolute;
  top: 598px;
  left: 82px;
  width: 245px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .img {
  top: 656px;
  left: 49px;
  width: 380px;
  height: 238px;
  aspect-ratio: 1.59;
  position: absolute;
  object-fit: cover;
}

Register page

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <img class="image" src="img/image-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">Event Registration Form</div>
      <img class="img" src="img/image-4.png" />
      <img class="rectangle-2" src="img/rectangle-17.svg" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="div"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <img class="rectangle-7" src="img/rectangle-24.svg" />
      <div class="rectangle-8"></div>
      <div class="text-wrapper-2">Register no:</div>
      <div class="text-wrapper-3">Full Name:</div>
      <div class="text-wrapper-4">Department:</div>
      <div class="text-wrapper-5">Mobile no:</div>
      <div class="text-wrapper-6">Email id:</div>
      <div class="text-wrapper-7">College:</div>
      <div class="text-wrapper-8">Event Registered:</div>
    </div>
  </body>
</html>

.android-compact {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 471px;
  min-height: 917px;
  position: relative;
}

.android-compact .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 471px;
  height: 917px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.android-compact .rectangle {
  position: absolute;
  top: 26px;
  left: 15px;
  width: 435px;
  height: 79px;
  background-color: #f2c3ed;
  border-radius: 30px;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 46px;
  left: 48px;
  width: 432px;
  font-family: "Inria Serif-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .img {
  position: absolute;
  top: 673px;
  left: 77px;
  width: 327px;
  height: 244px;
  aspect-ratio: 1.34;
}

.android-compact .rectangle-2 {
  position: absolute;
  top: 124px;
  left: 23px;
  width: 427px;
  height: 537px;
}

.android-compact .text-on-a-path {
  position: absolute;
  top: 137px;
  left: -1036px;
  width: 372px;
  height: 60px;
}

.android-compact .div {
  position: absolute;
  top: 219px;
  left: 55px;
  width: 372px;
  height: 60px;
  background-color: #e19191;
  border-radius: 10px;
}

.android-compact .rectangle-3 {
  position: absolute;
  top: 296px;
  left: 55px;
  width: 372px;
  height: 60px;
  background-color: #e19191;
  border-radius: 10px;
}

.android-compact .rectangle-4 {
  position: absolute;
  top: 373px;
  left: 55px;
  width: 372px;
  height: 60px;
  background-color: #e19191;
  border-radius: 10px;
}

.android-compact .rectangle-5 {
  position: absolute;
  top: 445px;
  left: 55px;
  width: 372px;
  height: 60px;
  background-color: #e19191;
  border-radius: 10px;
}

.android-compact .rectangle-6 {
  position: absolute;
  top: 514px;
  left: 55px;
  width: 372px;
  height: 60px;
  background-color: #e19191;
  border-radius: 10px;
}

.android-compact .rectangle-7 {
  position: absolute;
  top: 588px;
  left: 55px;
  width: 372px;
  height: 60px;
}

.android-compact .rectangle-8 {
  position: absolute;
  top: 147px;
  left: 55px;
  width: 372px;
  height: 60px;
  background-color: #e19191;
  border-radius: 10px;
}

.android-compact .text-wrapper-2 {
  position: absolute;
  top: 230px;
  left: 73px;
  width: 320px;
  font-family: "Inria Serif-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-3 {
  position: absolute;
  top: 158px;
  left: 65px;
  width: 320px;
  font-family: "Inria Serif-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-4 {
  position: absolute;
  top: 307px;
  left: 76px;
  width: 320px;
  font-family: "Inria Serif-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-wrapper-5 {
  position: absolute;
  top: 379px;
  left: 77px;
  width: 320px;
  font-family: "Inria Serif-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-6 {
  position: absolute;
  top: 461px;
  left: 77px;
  width: 320px;
  font-family: "Inria Serif-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-7 {
  position: absolute;
  top: 522px;
  left: 76px;
  width: 320px;
  font-family: "Inria Serif-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-8 {
  position: absolute;
  top: 591px;
  left: 76px;
  width: 320px;
  font-family: "Inria Serif-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 34px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}
```
## OUTPUT:
![alt text](<1.png (2).png>)


## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
