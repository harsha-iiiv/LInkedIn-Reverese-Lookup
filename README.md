

### Early access is on [here](https://enrich-email.cyclic.app/) 
<p align="center"><img src="https://i.ytimg.com/vi/4q9CNtwdawA/maxresdefault.jpg" align="center" width="300"></p>
<h2 align="center">LinkedIn-Reverese-Lookup</h2>
<p align="center"><b>🔎Searching LinkedIn profile by email address📧</b></p>

Sales Navigator is a sales tool, designed to allow sales teams to build and nurture customer relationships on LinkedIn. It was recently announced that as of March 2020 Sales Navigator would no longer function within Gmail, due to low usage. Whilst sales teams may not have been using Sales Navigator in its intended sense, OSINT practitioners were using it day-to-day when conducting people searching. 


Until 08/04/2020, anyone with a LinkedIn account could manipulate a URL to give them the results of a Sales Navigator search for an email address, without having to pay for Sales Navigator. Simply changing the email address at the end of the URL, you could freely query LinkedIn for any email address, to identify if it was linked to a LinkedIn account. The query was as follows:


https://www.linkedin.com/sales/gmail/profile/viewByEmail/harsha@gmail.com.


However, instead of getting the expected result for your query, you are now met with a message stating "Something went wrong while displaying this profile. Please reload or try again later.". 

Fortunately, there is another way to search LinkedIn by email address. Since 2017, Sales Navigator has been integrated with Outlook, as well as Gmail. Microsoft owns both Outlook and LinkedIn and a large number of corporations use Outlook for day-to-day activity, so it makes sense for Microsoft to integrate with Outlook rather than Gmail. 

#### 🔎LinkedIn by email address.

### Disclaimer :- I am not promoting any illegal activity here. This is purely for educational purpose . I am not responsible if you use it for illegal purpose or cross the linkedin terms and conditions .

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


