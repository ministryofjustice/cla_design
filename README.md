Design of the Civil Legal Aid (CLA) tool
==========

## The design of the Civil Legal Aid tool

Civil Legal Aid is a service by the UK Ministry of Justice (MOJ) that provides legal aid and advice for those who can’t afford it.

The Civil Legal Aid (CLA) tool is a number of interconnected services built by [MOJ Digital Services (MOJDS)](https://mojdigital.blog.gov.uk) to allow someone to file a case either digitally or over the phone, and have that case processed by an operator, and if eligible, assigned to a specialist provider who will then provide the person with legal aid.

The CLA call centre handles somewhere around 20,000 calls per month (7.5 minute average call time) and the operator fields calls from people with problems ranging from imminent homelessness to domestic physical abuse to just general legal enquiries. The application therefore needs to concentrate on letting the call progress with as little distraction to the caller (User) while guiding them through the process as quickly and efficiently as possible. This will cut call time, and likely case handling costs as well, by half by encouraging the Operator to follow the lead of the caller and to not prescribe too much process on the information gathering, thus providing a better and more efficient service.

The overall design of the interface is furthering the standards in the [GDS Design Manual](https://www.gov.uk/service-manual/designers) and has been expanded to create a developing standard for government-wide back-end and internal tools.

## Who is going to use it

* **The user** who is the member of the public and fills in the form themselves to determine whether or not they are eligible for Civil Legal Aid
* **The operator** in the call centre who answers the phone and determines the member of the public's problem and context and conducts the means test for the user
* **The Specialist Provider** who is a legal professional who is assigned the case by the operator and will handle the user's case

## How cla_design files are organised

The design is done for the most part in [Bohemian Coding’s Sketch](http://bohemiancoding.com/sketch) with the following files:

**cla-icons.sketch** - A template for the icon font produced using [gulp-iconfont](https://www.npmjs.org/package/gulp-iconfont) which creates icon fonts from SVG icons and [gulp-iconfont-css](https://www.npmjs.org/package/gulp-iconfont-css) which generates the (S)CSS file for the icon font created with Gulp. Both require Node.js. The icons are 512w x 512h to generate the icon font, however they are designed to display at 16px.

**User.sketch** - The design for the form that the member of the public would use via [GOV.UK](https://www.gov.uk)

**User_mobile.sketch** - Designs for how the user form would look for mobile.

## Links
[CLA frontend GitHub](https://github.com/ministryofjustice/cla_frontend)
[Governmental Digital Services Design Notes](https://designnotes.blog.gov.uk)

## Styles & Elements

### Typography
<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/495102/4829414/f6058efe-5f86-11e4-81c0-8dfa9538031a.png">
</p>

### Colours
<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/495102/4829534/be184d32-5f87-11e4-927d-1fb2068bf070.png">
</p>

### Buttons
<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/495102/4830248/7806b9c8-5f8c-11e4-95fd-7452bdc7d952.png">
</p>

### Tabs & Pills
<p align="center">
	<img src=“https://cloud.githubusercontent.com/assets/495102/4841797/882ed1d6-601e-11e4-9d41-d9120318a335.png”>
</p>

### Labels
![](https://cloud.githubusercontent.com/assets/495102/4841901/b3f2878a-601f-11e4-9ba3-a8a807271d7b.png)

### Forms
![](https://cloud.githubusercontent.com/assets/495102/4841916/d0a1bdce-601f-11e4-97e3-362671c5df76.png)

### Blockquotes
![](https://cloud.githubusercontent.com/assets/495102/4841921/e2f28558-601f-11e4-8689-705a737082fe.png)

### Progress bars
![](https://cloud.githubusercontent.com/assets/495102/4841932/f33e2660-601f-11e4-9aec-cc6bf92c2e1b.png)