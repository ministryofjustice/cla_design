Design of the Civil Legal Aid (CLA) tool
==========

Civil Legal Aid is a service by the UK Ministry of Justice (MOJ) that provides legal aid and advice for those who can’t afford it.

The Civil Legal Aid (CLA) tool is a number of interconnected services built by [MOJ Digital Services (MOJDS)](https://mojdigital.blog.gov.uk) to allow someone to file a case either digitally or over the phone, and have that case processed by an operator, and if eligible, assigned to a specialist provider who will then provide the person with legal aid.

The CLA call centre handles somewhere around 20,000 calls per month (7.5 minute average call time) and the operator fields calls from people with problems ranging from imminent homelessness to domestic physical abuse to just general legal enquiries. The application therefore needs to concentrate on letting the call progress with as little distraction to the caller (User) while guiding them through the process as quickly and efficiently as possible. This will cut call time, and likely case handling costs as well, by half by encouraging the Operator to follow the lead of the caller and to not prescribe too much process on the information gathering, thus providing a better and more efficient service.

The overall design of the interface is furthering the standards in the [GDS Design Manual](https://www.gov.uk/service-manual/designers) and has been expanded to create a developing standard for government-wide back-end and internal tools.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

# Who is going to use it

**The user** who is the member of the public and fills in the form themselves to determine whether or not they are eligible for Civil Legal Aid

**The operator** in the call centre who answers the phone and determines the member of the public's problem and context and conducts the means test for the user

**The Specialist Provider** who is a legal professional who is assigned the case by the operator and will handle the user's case

# Links
[CLA frontend GitHub](https://github.com/ministryofjustice/cla_frontend)

[Governmental Digital Services Design Notes](https://designnotes.blog.gov.uk)

[Cases queue - Integration version](https://dchtm6r471mui.cloudfront.net/hackpad.com_B2kIZMUCiTq_p.113892_1412265710243_cla-case-list.gif)

[Case interface - Integration version](https://dchtm6r471mui.cloudfront.net/hackpad.com_B2kIZMUCiTq_p.113892_1412265727578_cla-case.gif)

- - - -

# User scenarios

[Click throughs of various operator scenarios](http://ministryofjustice.github.io/service-screens/service/civil-legal-advice/index.html)

### Key screens
Admin case handling system queue
<img src="https://cloud.githubusercontent.com/assets/495102/4885828/6d2b8382-6377-11e4-9c32-12666f146c9d.png">

Case interface assessment test
<img src="https://cloud.githubusercontent.com/assets/495102/4885808/4c761e22-6377-11e4-8237-2544e630279e.png">

Assigning a case for Civil Legal Aid
<img src="https://cloud.githubusercontent.com/assets/495102/4885846/81b31e00-6377-11e4-9fa8-df8462199c92.png">

# Styles & Elements

## Typography
> ![](https://cloud.githubusercontent.com/assets/495102/4829414/f6058efe-5f86-11e4-81c0-8dfa9538031a.png)

### Colours
> ![](https://cloud.githubusercontent.com/assets/495102/4829534/be184d32-5f87-11e4-927d-1fb2068bf070.png)
### Buttons
> ![](https://cloud.githubusercontent.com/assets/495102/4994734/88e8b88c-69b3-11e4-8dd5-a80bb558ae59.png)

### Tabs & Pills

> ![](https://cloud.githubusercontent.com/assets/495102/4841797/882ed1d6-601e-11e4-9d41-d9120318a335.png)

### Labels
> ![](https://cloud.githubusercontent.com/assets/495102/4841901/b3f2878a-601f-11e4-9ba3-a8a807271d7b.png)

### Forms
> ![](https://cloud.githubusercontent.com/assets/495102/4841916/d0a1bdce-601f-11e4-97e3-362671c5df76.png)

### Blockquotes
> ![](https://cloud.githubusercontent.com/assets/495102/4841921/e2f28558-601f-11e4-8689-705a737082fe.png)

### Progress bars
> ![](https://cloud.githubusercontent.com/assets/495102/4841932/f33e2660-601f-11e4-9aec-cc6bf92c2e1b.png)

- - - -

### Icons

A template for the icon font produced using [gulp-iconfont](https://www.npmjs.org/package/gulp-iconfont) which creates icon fonts from SVG icons and [gulp-iconfont-css](https://www.npmjs.org/package/gulp-iconfont-css) which generates the (S)CSS file for the icon font created with Gulp. Both require Node.js. The icons are 512w x 512h to generate the icon font, however they are designed to display at 16px.

<img src="https://cloud.githubusercontent.com/assets/495102/4977080/4c9ea62c-68e4-11e4-8a46-a76bbc4afd2f.png">

All of the icons used in the project are free and open to use under [the CC license below](http://creativecommons.org/licenses/by-nc-sa/4.0/).
