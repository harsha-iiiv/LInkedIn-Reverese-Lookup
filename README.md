


<p align="center"><img src="https://i.ytimg.com/vi/4q9CNtwdawA/maxresdefault.jpg" align="center" width="300"></p>
<h2 align="center">LinkedIn-Reverese-Lookup</h2>
<p align="center"><b>🔎Searching LinkedIn profile by email address📧</b></p>

#### 🔎LinkedIn by email address.

### Installation Guide
1. Open terminal on your PC.
2. Clone the repo `git clone https://github.com/harsha-iiiv/LInkedIn-Reverese-Lookup.git`
3. Go inside the project directory
4. Go to `keys.js` file and add your microsoft email, password and emails count there.
5. Install dependencies `npm install`
6. Now before runnig `find.js` file make sure you imported emails as contacts into the your outlook and `node find.js`



### Requirements
- [Node.js](https://nodejs.org/en/download/) should be installed
- [Google Chrome](https://www.google.com/intl/en_in/chrome/) with version 70+

### If you want to see the whole process
In `keys.js` file you have to set a variable name head=false;

But while for deployment we need headless as true.



### Todo

Deployment on Cloud

### How it works

Project is made using [Puppeteer](https://developers.google.com/web/tools/puppeteer) which is a Node library which provides a high-level API to control headless Chrome or Chromium. We open a chromium app on server where we can add create open tabs see browser versions and everything.

So here we are using `puppeteer-extra` and `puppeteer-extra-plugin-stealth` which helps in creating an instance of chrome where google don't able to detect that it is created by puppeteer.



---
<p align="center"> Made with ❤️ by <a href="https://harshaa.ninja/">Harsha Surisetty</a></p>


