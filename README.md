# Ex09 Event Registration Web Application
## Date:08-05-2024

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
PAGE 1[HOMEPAGE]:

<div className="Homepage" style={{width: 277, height: 490, position: 'relative', background: 'white'}}>
  <img className="A578aba948f85432c8a4250f0cbc601" style={{width: 275, height: 495, left: 2, top: 0, position: 'absolute'}} src="https://via.placeholder.com/275x495" />
  <img className="SaeethaLogo" style={{width: 271, height: 41, left: 3, top: 25, position: 'absolute'}} src="https://via.placeholder.com/271x41" />
  <img className="Download1" style={{width: 103, height: 105, left: 88, top: 143, position: 'absolute'}} src="https://via.placeholder.com/103x105" />
  <div className="Celanza" style={{width: 184, height: 26, left: 47, top: 258, position: 'absolute', textAlign: 'center', color: '#FA1919', fontSize: 20, fontFamily: 'Irish Grover', fontWeight: '400', wordWrap: 'break-word'}}>CELANZA<br/><br/></div>
  <div className="Rectangle1" style={{width: 140, height: 23, left: 69, top: 294, position: 'absolute', background: '#00A2FE', boxShadow: '0px 4px 4px rgba(0, 0, 0, 0.25) inset', border: '1px black solid'}} />
  <div className="Rectangle2" style={{width: 140, height: 23, left: 69, top: 327, position: 'absolute', background: '#00A2FE', boxShadow: '0px 4px 4px rgba(0, 0, 0, 0.25) inset'}} />
  <div className="Login" style={{width: 124, height: 13, left: 76, top: 294, position: 'absolute', textAlign: 'center', color: '#000000', fontSize: 18, fontFamily: 'Jolly Lodger', fontWeight: '400', wordWrap: 'break-word'}}>LOGIN<br/></div>
  <div className="Register" style={{width: 123, height: 19, left: 76, top: 327, position: 'absolute', textAlign: 'center', color: '#0B0A0A', fontSize: 18, fontFamily: 'Jolly Lodger', fontWeight: '400', wordWrap: 'break-word'}}>REGISTER<br/></div>
</div>
```
```
PAGE 2[EVENTS]:

<div className="Events" style={{width: 281, height: 490, position: 'relative', background: 'white'}}>
  <img className="A578aba948f85432c8a4250f0cbc602" style={{width: 286, height: 490, left: 0, top: 0, position: 'absolute'}} src="https://via.placeholder.com/286x490" />
  <img className="SaeethaLogo" style={{width: 268, height: 43, left: 6, top: 28, position: 'absolute'}} src="https://via.placeholder.com/268x43" />
  <div className="Celanza2024Events" style={{width: 231, height: 20, left: 25, top: 95, position: 'absolute', textAlign: 'center', color: '#FF0000', fontSize: 24, fontFamily: 'Jolly Lodger', fontWeight: '400', wordWrap: 'break-word'}}>CELANZA 2024 EVENTS</div>
  <div className="MirrorDance" style={{width: 164, height: 17, left: 24, top: 152, position: 'absolute', textAlign: 'center', color: '#FF8A00', fontSize: 15, fontFamily: 'Keania One', fontWeight: '400', wordWrap: 'break-word'}}>MIRROR DANCE</div>
  <div className="DanceBattle" style={{width: 108, height: 17, left: 52, top: 184, position: 'absolute', textAlign: 'center', color: '#FFA800', fontSize: 15, fontFamily: 'Keania One', fontWeight: '400', wordWrap: 'break-word'}}>DANCE BATTLE</div>
  <div className="MimicDance" style={{width: 155, height: 23, left: 26, top: 214, position: 'absolute', textAlign: 'center', color: '#FF9900', fontSize: 15, fontFamily: 'Keania One', fontWeight: '400', wordWrap: 'break-word'}}>MIMIC DANCE</div>
  <div className="DrawWithComali" style={{width: 179, height: 19, left: 35, top: 245, position: 'absolute', textAlign: 'center', color: '#FFAE12', fontSize: 15, fontFamily: 'Keania One', fontWeight: '400', wordWrap: 'break-word'}}>DRAW WITH COMALI<br/></div>
  <div className="Ps4Ps5Tournament" style={{width: 191, height: 17, left: 40, top: 272, position: 'absolute', textAlign: 'center', color: 'rgba(255, 122.40, 0, 0.67)', fontSize: 15, fontFamily: 'Keania One', fontWeight: '400', wordWrap: 'break-word'}}>PS4/PS5 TOURNAMENT<br/></div>
  <div className="DigitalArt" style={{width: 107, height: 10, left: 44, top: 301, position: 'absolute', textAlign: 'center', color: '#FFAA06', fontSize: 15, fontFamily: 'Keania One', fontWeight: '400', wordWrap: 'break-word'}}>DIGITAL ART<br/></div>
  <div className="MagicTouch" style={{width: 110, height: 23, left: 48, top: 330, position: 'absolute', textAlign: 'center', color: '#EDA313', fontSize: 15, fontFamily: 'Keania One', fontWeight: '400', wordWrap: 'break-word'}}>MAGIC TOUCH<br/></div>
  <div className="WarOfWords" style={{width: 204, height: 16, left: 8, top: 353, position: 'absolute', textAlign: 'center', color: '#E8AB0E', fontSize: 15, fontFamily: 'Keania One', fontWeight: '400', wordWrap: 'break-word'}}>WAR OF WORDS</div>
</div>
```
```
PAGE 3[REGISTRATION FORM]:

<div className="RegistrationForm" style={{width: 281, height: 490, position: 'relative', background: 'white'}}>
  <img className="A578aba948f85432c8a4250f0cbc602" style={{width: 286, height: 490, left: 0, top: 0, position: 'absolute'}} src="https://via.placeholder.com/286x490" />
  <img className="SaeethaLogo" style={{width: 259, height: 39, left: 15, top: 29, position: 'absolute'}} src="https://via.placeholder.com/259x39" />
  <div className="EventRegistration" style={{width: 206, height: 20, left: 40, top: 96, position: 'absolute', textAlign: 'center', color: '#FF3D00', fontSize: 24, fontFamily: 'Jolly Lodger', fontWeight: '400', wordWrap: 'break-word'}}>EVENT REGISTRATION<br/></div>
  <div className="Rectangle3" style={{width: 199, height: 18, left: 44, top: 139, position: 'absolute', background: 'black'}} />
  <div className="Rectangle4" style={{width: 199, height: 18, left: 44, top: 170, position: 'absolute', background: '#000000'}} />
  <div className="Rectangle5" style={{width: 199, height: 18, left: 44, top: 201, position: 'absolute', background: '#0B0A0A'}} />
  <div className="Rectangle6" style={{width: 199, height: 18, left: 44, top: 232, position: 'absolute', background: '#100E0E'}} />
  <div className="Rectangle7" style={{width: 199, height: 18, left: 44, top: 263, position: 'absolute', background: '#100E0E'}} />
  <div className="Rectangle8" style={{width: 199, height: 18, left: 44, top: 294, position: 'absolute', background: '#000000'}} />
  <div className="Rectangle9" style={{width: 199, height: 18, left: 44, top: 325, position: 'absolute', background: 'black'}} />
  <div className="Rectangle10" style={{width: 199, height: 18, left: 44, top: 351, position: 'absolute', background: '#0B0A0A'}} />
  <div className="FullName" style={{width: 125, height: 9, left: 15, top: 144, position: 'absolute', textAlign: 'center', color: 'white', fontSize: 10, fontFamily: 'Lakki Reddy', fontWeight: '400', wordWrap: 'break-word'}}>FULL NAME</div>
  <div className="RegistrationNumber" style={{width: 210, height: 17, left: 0, top: 176, position: 'absolute', textAlign: 'center', color: 'white', fontSize: 10, fontFamily: 'Lakki Reddy', fontWeight: '400', wordWrap: 'break-word'}}>REGISTRATION NUMBER<br/></div>
  <div className="Department" style={{width: 180, height: 14, left: -7, top: 206, position: 'absolute', textAlign: 'center', color: 'white', fontSize: 10, fontFamily: 'Lakki Reddy', fontWeight: '400', wordWrap: 'break-word'}}>DEPARTMENT<br/></div>
  <div className="MobileNumber" style={{width: 154, height: 8, left: 15, top: 237, position: 'absolute', textAlign: 'center', color: 'white', fontSize: 10, fontFamily: 'Lakki Reddy', fontWeight: '400', wordWrap: 'break-word'}}>MOBILE NUMBER</div>
  <div className="EmailId" style={{width: 115, height: 14, left: 15, top: 267, position: 'absolute', textAlign: 'center', color: 'white', fontSize: 10, fontFamily: 'Lakki Reddy', fontWeight: '400', wordWrap: 'break-word'}}>EMAIL ID</div>
  <div className="RegistrationFee" style={{width: 142, height: 8, left: 27, top: 330, position: 'absolute', textAlign: 'center', color: 'white', fontSize: 10, fontFamily: 'Lakki Reddy', fontWeight: '400', wordWrap: 'break-word'}}>REGISTRATION FEE</div>
  <div className="PaymentScreenshot" style={{width: 124, height: 4, left: 45, top: 355, position: 'absolute', textAlign: 'center', color: 'white', fontSize: 10, fontFamily: 'Lakki Reddy', fontWeight: '400', wordWrap: 'break-word'}}>PAYMENT SCREENSHOT</div>
  <div className="EventsToRegister" style={{width: 176, height: 14, left: 15, top: 299, position: 'absolute', textAlign: 'center', color: 'white', fontSize: 10, fontFamily: 'Lakki Reddy', fontWeight: '400', wordWrap: 'break-word'}}>EVENTS TO REGISTER</div>
</div>
```
```
PAGE 4[GREETINGS]:

<div className="Greeting" style={{width: 276, height: 490, position: 'relative', background: 'white'}}>
  <img className="A578aba948f85432c8a4250f0cbc603" style={{width: 276, height: 490, left: 0, top: 0, position: 'absolute'}} src="https://via.placeholder.com/276x490" />
  <img className="SaeethaLogo" style={{width: 259, height: 39, left: 8, top: 27, position: 'absolute'}} src="https://via.placeholder.com/259x39" />
  <div className="ThankYouForRegistering" style={{width: 192, height: 154, left: 42, top: 162, position: 'absolute', textAlign: 'center', color: 'black', fontSize: 24, fontFamily: 'Lakki Reddy', fontWeight: '400', wordWrap: 'break-word'}}>THANK YOU <br/>FOR REGISTERING </div>
  <div className="WeHaveExictedToHaveYouOnBoard" style={{width: 236, height: 33, left: 22, top: 283, position: 'absolute', textAlign: 'center', color: 'black', fontSize: 24, fontFamily: 'Londrina Solid', fontWeight: '400', wordWrap: 'break-word'}}>“We have exicted to have you On Board”</div>
  <div className="DesignedByRDivyaDharshini" style={{width: 168, height: 9, left: 51, top: 370, position: 'absolute', textAlign: 'center', color: 'black', fontSize: 13, fontFamily: 'Lateef', fontWeight: '400', wordWrap: 'break-word'}}>DESIGNED BY R.DIVYA DHARSHINI</div>
</div>
```

## OUTPUT:

![alt text](<Screenshot 2024-05-08 144324.png>)OUTPUT:


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
