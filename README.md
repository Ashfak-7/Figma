# Ex09 Event Registration Web Application
## Date:16/10/2025

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
    <div class="android-medium">
      <img class="fim" src="img/fim-1.png" />
      <img class="logo" src="img/logo-1.png" />
      <img class="sa" src="img/sa-1.png" />
      <div class="text-wrapper">sports day events</div>
      <img class="union" src="img/union.png" />
      <div class="rectangle"></div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="div"></div>
      <div class="text-wrapper-2">LOGIN</div>
      <div class="text-wrapper-3">REGISTER</div>
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

.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 693px;
  min-height: 827px;
  position: relative;
}

.android-medium .fim {
  position: absolute;
  top: 0;
  left: 0;
  width: 693px;
  height: 821px;
  aspect-ratio: 0.68;
  object-fit: cover;
}

.android-medium .logo {
  position: absolute;
  top: 37px;
  left: 17px;
  width: 664px;
  height: 100px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

.android-medium .sa {
  position: absolute;
  top: 157px;
  left: 232px;
  width: 229px;
  height: 220px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 426px;
  left: 232px;
  width: 298px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .union {
  position: absolute;
  top: 508px;
  left: 214px;
  width: 247px;
  height: 72px;
}

.android-medium .rectangle {
  position: absolute;
  top: 637px;
  left: 227px;
  width: 234px;
  height: 84px;
  background-color: #2c01ff;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 526px;
  left: 212px;
  width: 249px;
  height: 70px;
}

.android-medium .div {
  position: absolute;
  top: 514px;
  left: 225px;
  width: 236px;
  height: 88px;
  background-color: #3107ff;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 534px;
  left: 288px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 651px;
  left: 251px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
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
    <div class="android-medium">
      <img class="image" src="img/image-3.png" />
      <div class="text-wrapper">EVENTS</div>
      <div class="div">-cricket</div>
      <div class="text-wrapper-2">-tennis</div>
      <p class="footbal"><span class="span">-</span> <span class="text-wrapper-3">footbal</span></p>
      <div class="text-wrapper-4">-basket ball</div>
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


.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 840px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 74px;
  left: 79px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #2e04ff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .div {
  position: absolute;
  top: 216px;
  left: 236px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #2e04ff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 357px;
  left: 245px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #2e04ff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .footbal {
  position: absolute;
  top: 496px;
  left: 252px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: transparent;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .span {
  color: #000000;
}

.android-medium .text-wrapper-3 {
  color: #2e04ff;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 614px;
  left: 257px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #2e04ff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
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
    <div class="android-medium"><img class="image" src="img/image-2.png" /></div>
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


.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  display: flex;
}

.android-medium .image {
  width: 700px;
  height: 840px;
  aspect-ratio: 0.66;
  object-fit: cover;
}



```
## OUTPUT:
![alt text](<Screenshot (41).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
