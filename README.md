Design of the Civil Legal Aid (CLA) tool
==========

## What is the Civil Legal Aid tool

Civil Legal Aid is a service by the UK Ministry of Justice (MOJ) that provides legal aid and advice for those who can’t afford it.

The Civil Legal Aid (CLA) tool is a number of interconnected services built by [MOJ Digital Services (MOJDS)](https://mojdigital.blog.gov.uk) to allow someone in need to file a case either digitally or over the phone, and have that case processed  by an operator and if eligible assigned to a specialist provider who will then provide the person with legal aid.

The CLA call centre handles somewhere around 20,000 calls per month (7.5 minute average call time) and the operator fields calls from people with problems ranging from imminent homelessness to domestic physical abuse to just general legal enquiries. The application therefore needs to concentrate on letting the call progress with as little distraction to the caller (User) while guiding them through the process as quickly and efficiently as possible.

## Who is going to use it

* **The user** who is the member of the public and fills in the form themselves to determine whether or not they are eligible for Civil Legal Aid
* **The operator** in the call centre who answers the phone and determines the member of the public's problem and context and conducts the means test for the user
* **The Specialist Provider** who is a legal professional who is assigned the case by the operator and will handle the user's case

## How cla_design files are organised

The design is done for the most part in [Bohemian Coding’s Sketch](http://bohemiancoding.com/sketch) with the following files:

**Operator-Provider.sketch** - This is the file which contains the UI designs for the main case handling tool. The actual tool is predominantly the same for the Operator who answers the phone in the call centre and handles incoming digital cases created with the service form on GOV.UK, as well as for the Specialist Provider. It includes the designs for the following flows in separate pages:
* Styles&Elements - An abstracted stylesheet with linked symbols
* Operator - The design flow for an Operator receiving a case and conducting the financial eligibility test to determine if the User is eligible for Civil Legal Aid.
* Contact - This covers how an Operator adds the User’s details whilst handling a call. The Provider would see the same information which they would need to verify and can change if need be.
* Help - Design for guidance flyout module which the Operator, Operator-Manager and Specialist Provider would click to search for things they are unsure of that may come up in a call.
* Operator-Manager - Separate admin-type screen for the managers of the Operators where they can override cases and give feedback on problematic cases.
* Provider - Interface for the Specialist Provider who would once assigned by the Operator, provide legal aid.

**cla-icons.sketch** - A template for the icon font produced using [gulp-iconfont](https://www.npmjs.org/package/gulp-iconfont) which creates icon fonts from SVG icons and [gulp-iconfont-css](https://www.npmjs.org/package/gulp-iconfont-css) which generates the (S)CSS file for the icon font created with Gulp. Both require Node.js. The icons are 512w x 512h to generate the icon font, however they are designed to display at 16px.

**User.sketch** - The design for the form that the member of the public would use via [GOV.UK](https://www.gov.uk)

**User_mobile.sketch** - Designs for how the user form would look for mobile.