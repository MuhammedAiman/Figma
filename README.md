# Ex09 Event Registration Web Application
## Date:23/12/2024

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
Homepage
html code
```
<div class="container--0-">
  <svg
    width="254"
    height="66"
    viewBox="0 0 254 66"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="254" height="66" fill="#D9D9D9"></rect></svg
  ><svg
    width="254"
    height="63"
    viewBox="0 0 254 63"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="254" height="63" fill="#D9D9D9"></rect></svg
  ><img
    src="data:image/jpeg;base64"
      /><img
    src="data:image/png;base64"
      /><svg
    width="202"
    height="60"
    viewBox="0 0 202 60"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="202" height="60" fill="#D9D9D9"></rect></svg
  ><svg
    width="202"
    height="63"
    viewBox="0 0 202 63"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="202" height="63" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-6">REGISTER</div>
  <div class="text-0-1-7">LOGIN</div>
  <div class="text-0-1-8">SPORTS DAY!!!</div>
  <img
    src="data:image/jpeg;base64"
      />
  <div class="text-0-1-10">LET’S GOO!!!</div>
</div>
```
css code
```
.container--0- {
  position: absolute;
  left: -1099px;
  top: -749px;
  width: 393px;
  height: 852px;
  background-color: #23cc37;
  justify-content: start;
  align-items: start;
}
.text-0-1-6 {
  width: 159px;
  height: 39px;
  color: #3994e4;
  font-size: 32px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-7 {
  width: 128px;
  height: 44px;
  color: #0aa1ff;
  font-size: 36px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-8 {
  width: 248px;
  height: 47px;
  color: #5353f3;
  font-size: 32px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-10 {
  width: 215px;
  height: 39px;
  color: #5c37ff;
  font-size: 32px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
```

Events
html code
```
<div class="container--0-">
  <img
    src="data:image/jpeg;base64"
     />
  <div class="text-0-1-1">EVENTS</div>
  <div class="text-0-1-2">→CRICKET</div>
  <div class="text-0-1-3">→ BADMINTON</div>
  <div class="text-0-1-4">→ FOOTBALL</div>
  <div class="text-0-1-5">→ TENNIS</div>
  <div class="text-0-1-6">→ BASKETBALL</div>
</div>

```
css code
```
.container--0- {
  position: absolute;
  left: -625px;
  top: -749px;
  width: 393px;
  height: 852px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-1 {
  width: 234px;
  height: 58px;
  color: #fd1212;
  font-size: 48px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-2 {
  width: 196px;
  height: 44px;
  color: #000000;
  font-size: 36px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-3 {
  width: 268px;
  height: 44px;
  color: #000000;
  font-size: 36px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-4 {
  width: 236px;
  height: 44px;
  color: #000000;
  font-size: 36px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-5 {
  width: 176px;
  height: 44px;
  color: #000000;
  font-size: 36px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-6 {
  width: 282px;
  height: 44px;
  color: #000000;
  font-size: 36px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}

```
Register page
```
<div class="container--0-">
  <img
    src="data:image/jpeg;base64"
     />
  <div class="text-0-1-1">EVENT REGISTRATION FORM</div>
  <div class="text-0-1-2">FILL THE DETAILS</div>
  <svg
    width="181"
    height="37"
    viewBox="0 0 181 37"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="181" height="37" fill="#E0D2D2"></rect>
  </svg>
  <div class="text-0-1-4">FULL NAME</div>
  <svg
    width="178"
    height="39"
    viewBox="0 0 178 39"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="178" height="39" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-6">GENDER</div>
  <svg
    width="170"
    height="37"
    viewBox="0 0 170 37"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="170" height="37" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-8">AGE</div>
  <svg
    width="168"
    height="36"
    viewBox="0 0 168 36"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="168" height="36" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-10">REG NO.</div>
  <svg
    width="167"
    height="36"
    viewBox="0 0 167 36"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="167" height="36" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-12">DEPARTMENT</div>
  <svg
    width="167"
    height="32"
    viewBox="0 0 167 32"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="167" height="32" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-14">MOB NO.</div>
  <svg
    width="167"
    height="35"
    viewBox="0 0 167 35"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="167" height="35" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-16">EMAIL ID</div>
  <svg
    width="167"
    height="34"
    viewBox="0 0 167 34"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="167" height="34" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-18">EVENTS TO REGISTER</div>
  <svg
    width="150"
    height="53"
    viewBox="0 0 150 53"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="150" height="53" fill="#FF0000"></rect>
  </svg>
  <div class="text-0-1-20">REGISTER</div>
</div>

```
css code
```
.container--0- {
  position: absolute;
  left: -151px;
  top: -749px;
  width: 393px;
  height: 852px;
  background-color: #efd7d7;
  justify-content: start;
  align-items: start;
}
.text-0-1-1 {
  width: 398px;
  height: 42px;
  color: #e000f5;
  font-size: 24px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-2 {
  width: 140px;
  height: 19px;
  color: #ff0000;
  font-size: 16px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-4 {
  width: 86px;
  height: 18px;
  color: #000000;
  font-size: 15px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-6 {
  width: 62px;
  height: 18px;
  color: #000000;
  font-size: 15px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-8 {
  width: 32px;
  height: 18px;
  color: #000000;
  font-size: 15px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-10 {
  width: 61px;
  height: 18px;
  color: #000000;
  font-size: 15px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-12 {
  width: 105px;
  height: 18px;
  color: #000000;
  font-size: 15px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-14 {
  width: 66px;
  height: 18px;
  color: #000000;
  font-size: 15px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-16 {
  width: 66px;
  height: 18px;
  color: #000000;
  font-size: 15px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-18 {
  width: 153px;
  height: 17px;
  color: #000000;
  font-size: 14px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-20 {
  width: 119px;
  height: 29px;
  color: #000000;
  font-size: 24px;
  font-family: Inter, "Extra Bold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}

```
Final page
html code
```
<div class="container--0-">
  <img
    src="data:image/jpeg;base64"
     /><img
    src="data:image/png;base64"
     />
  <div class="text-0-1-2">THANK YOU!!</div>
  <div class="text-0-1-3">
    WE ARE ALL EAGERLY WAITING FOR<br />YOUR PARTICIPATION
  </div>
  <div class="text-0-1-4">CONTACT US</div>
  <div class="text-0-1-5">saveetha engineering college@gmail.com</div>
  <div class="text-0-1-6">+91 8870167403</div>
</div>

```
css code
```
Preview
Code
CSS
.container--0- {
  position: absolute;
  left: 323px;
  top: -749px;
  width: 393px;
  height: 852px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-2 {
  width: 273px;
  height: 48px;
  color: #000000;
  font-size: 40px;
  font-family: Inter, "Black Italic";
  font-weight: 900;
  text-align: left;
  vertical-align: top;
}
.text-0-1-3 {
  width: 253px;
  height: 34px;
  color: #000000;
  font-size: 14px;
  font-family: Inter, "Black Italic";
  font-weight: 900;
  text-align: center;
  vertical-align: top;
}
.text-0-1-4 {
  width: 94px;
  height: 17px;
  color: #000000;
  font-size: 14px;
  font-family: Inter, "Black Italic";
  font-weight: 900;
  text-align: center;
  vertical-align: top;
}
.text-0-1-5 {
  width: 297px;
  height: 17px;
  color: #000000;
  font-size: 14px;
  font-family: Inter, "Black Italic";
  font-weight: 900;
  text-align: center;
  vertical-align: top;
}
.text-0-1-6 {
  width: 121px;
  height: 17px;sssssss
  color: #000000;
  font-size: 14px;
  font-family: Inter, "Black Italic";
  font-weight: 900;
  text-align: center;
  vertical-align: top;
}

```
## OUTPUT:

![alt text](<Screenshot (60).png>)

![alt text](<Screenshot (61).png>)

![alt text](<Screenshot (62).png>)

![alt text](<Screenshot (62).png>)

![alt text](<Screenshot (64).png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
