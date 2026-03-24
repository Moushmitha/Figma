# Ex08 Event Registration Web Application
## Date:20.03.2026

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
Layer 1:
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
      <img class="bg-figma" src="img/bg-figma-1.png" />
      <div class="text-wrapper">Event</div>
      <div class="div">Artsy</div>
      <img class="text-on-a-path" src="img/image.svg" />
      <div class="rectangle"></div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="text-wrapper-2">Login</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">Register</div>
      <img class="logo" src="img/logo1-1.png" />
      <img class="img" src="img/logo2-1.png" />
    </div>
  </body>
</html>
style.css
.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .bg-figma {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 533px;
  left: 120px;
  font-family: "Kranky-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 423px;
  left: 96px;
  width: 247px;
  font-family: "Kranky-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  top: 520px;
  left: 821px;
  width: 178px;
  height: 65px;
}

.iphone-pro-max .rectangle {
  top: 781px;
  width: 178px;
  height: 64px;
  background-color: #ff0505;
  box-shadow: 0px 4px 4px #00000040;
  position: absolute;
  left: 120px;
  border-radius: 5px;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 787px;
  left: 159px;
  width: 99px;
  font-family: "Libre Caslon Text-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-2 {
  top: 673px;
  width: 176px;
  height: 65px;
  background-color: #f91010;
  position: absolute;
  left: 120px;
  border-radius: 5px;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 684px;
  left: 138px;
  font-family: "Libre Caslon Text-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .logo {
  position: absolute;
  top: 214px;
  left: 96px;
  width: 224px;
  height: 216px;
  aspect-ratio: 1.04;
}

.iphone-pro-max .img {
  position: absolute;
  top: 9px;
  left: 27px;
  width: 373px;
  height: 75px;
  aspect-ratio: 4.97;
  object-fit: cover;
}


Layer 2:
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
      <img class="bg-figma" src="img/bg-figma-2.png" />
      <div class="text-wrapper">Event you join:</div>
      <img class="star" src="img/star-1.svg" />
      <img class="img" src="img/star-2.svg" />
      <img class="star-2" src="img/star-3.svg" />
      <img class="star-3" src="img/star-4.svg" />
      <img class="star-4" src="img/star-5.svg" />
      <div class="div">Drawing</div>
      <div class="text-wrapper-2">Sketching</div>
      <div class="text-wrapper-3">Painting</div>
      <div class="text-wrapper-4">Handcrafts</div>
      <div class="text-wrapper-5">Digital Art</div>
      <div class="text-wrapper-6">Editing</div>
      <img class="star-5" src="img/star-6.svg" />
      <div class="rectangle"></div>
      <div class="text-wrapper-7">To Register</div>
    </div>
  </body>
</html>
style.css
.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .bg-figma {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 67px;
  left: 66px;
  font-family: "Kranky-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .star {
  position: absolute;
  top: 206px;
  left: 44px;
  width: 35px;
  height: 24px;
}

.iphone-pro-max .img {
  position: absolute;
  top: 299px;
  left: 48px;
  width: 31px;
  height: 31px;
}

.iphone-pro-max .star-2 {
  position: absolute;
  top: 400px;
  left: 50px;
  width: 29px;
  height: 33px;
}

.iphone-pro-max .star-3 {
  position: absolute;
  top: 499px;
  left: 54px;
  width: 26px;
  height: 31px;
}

.iphone-pro-max .star-4 {
  position: absolute;
  top: 596px;
  left: 55px;
  width: 25px;
  height: 26px;
}

.iphone-pro-max .div {
  position: absolute;
  top: 197px;
  left: 107px;
  font-family: "Kranky-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 287px;
  left: 107px;
  font-family: "Kranky-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 395px;
  left: 107px;
  font-family: "Kranky-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 498px;
  left: 107px;
  font-family: "Kranky-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 679px;
  left: 107px;
  font-family: "Kranky-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 588px;
  left: 107px;
  font-family: "Kranky-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .star-5 {
  position: absolute;
  top: 688px;
  left: 55px;
  width: 26px;
  height: 24px;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 815px;
  left: 69px;
  width: 291px;
  height: 74px;
  background-color: #ffa528;
  border-radius: 20px;
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 827px;
  left: 112px;
  font-family: "Libre Bodoni-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}


Layer 3:
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
      <img class="bg-figma" src="img/bg-figma-3.png" />
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <img class="img" src="img/rectangle-10.svg" />
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper">Please fill the details:</div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-2">Register</div>
      <div class="text-wrapper-3">Full Name:</div>
      <div class="text-wrapper-4">Register no:</div>
      <div class="text-wrapper-5">Department:</div>
      <div class="text-wrapper-6">Year:</div>
      <div class="text-wrapper-7">Phone no:</div>
      <div class="text-wrapper-8">Gender:</div>
      <div class="text-wrapper-9">Event:</div>
    </div>
  </body>
</html>
style.css
.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .bg-figma {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 149px;
  left: 45px;
  width: 364px;
  height: 44px;
  background-color: #d9d9d9;
  border-radius: 10px;
}

.iphone-pro-max .div {
  position: absolute;
  top: 248px;
  left: 45px;
  width: 314px;
  height: 44px;
  background-color: #d9d9d9;
  border-radius: 10px;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 351px;
  left: 44px;
  width: 310px;
  height: 44px;
  background-color: #d9d9d9;
  border-radius: 10px;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 319px;
  left: 354px;
  width: 1px;
  height: 1px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 454px;
  left: 46px;
  width: 270px;
  height: 48px;
  background-color: #d9d9d9;
  border-radius: 10px;
}

.iphone-pro-max .img {
  position: absolute;
  top: 564px;
  left: 46px;
  width: 271px;
  height: 51px;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 668px;
  left: 46px;
  width: 337px;
  height: 53px;
  background-color: #d9d9d9;
  border-radius: 10px;
}

.iphone-pro-max .rectangle-6 {
  position: absolute;
  top: 779px;
  left: 46px;
  width: 370px;
  height: 53px;
  background-color: #d9d9d9;
  border-radius: 10px;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 46px;
  left: 15px;
  width: 373px;
  font-family: "Kranky-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-7 {
  position: absolute;
  top: 874px;
  left: 118px;
  width: 225px;
  height: 68px;
  background-color: #f91313;
  border-radius: 15px;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 888px;
  left: 163px;
  font-family: "Libre Bodoni-Regular", Helvetica;
  font-weight: 400;
  color: #160a0a;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 160px;
  left: 53px;
  font-family: "Libre Bodoni-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 259px;
  left: 53px;
  font-family: "Libre Bodoni-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 360px;
  left: 53px;
  font-family: "Libre Bodoni-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 465px;
  left: 53px;
  font-family: "Libre Bodoni-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 580px;
  left: 53px;
  font-family: "Libre Bodoni-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-8 {
  position: absolute;
  top: 682px;
  left: 53px;
  font-family: "Libre Bodoni-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-9 {
  position: absolute;
  top: 794px;
  left: 53px;
  font-family: "Libre Bodoni-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}



```


## OUTPUT:
<img width="1920" height="1080" alt="Screenshot (53)" src="https://github.com/user-attachments/assets/0e95cfaf-1d46-4bbf-8688-a2cebdb1a6d4" />
<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/888ac6b9-1d27-48a0-99c0-081690385ede" />
<img width="1920" height="1080" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/3c5734a6-f968-4b08-9844-098f5512ab16" />





## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
