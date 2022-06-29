# Automation-Exercise

Intro

In this exercise, you will need to create simple automation using the Puppeteer library.
Puppeteer is a javascript library that allows you to simulate Chrome usage by writing javascript
code, this is why it is optimal for web site automation.

Puppeteer runs on Node so you first must install and run Node:
[Node](https://nodejs.org/en/download/)
Node can be installed both in Windows and Linux, many installation guides are available online.

Puppeteer library:
[Puppeteer](https://github.com/GoogleChrome/puppeteer)

API guide:
[API](https://github.com/GoogleChrome/puppeteer/blob/v1.5.0/docs/api.md)

Examples:
[Examples](https://github.com/checkly/puppeteer-examples)

The exercise:
Create an automation file to check the following site:
[Example Form](http://contractorsinsurancereview.com/ExampleForm/)

The automation flow should:
- Type values in the Name, Email, Phone and Company fields.
- Create a screenshot of the page before clicking the “Request a call back” button.
- Bonus: Change the Number of Employees from 1-10 to 51-500
- Click the “Request a call back” button.
- Write to the console.log when reaching the thank you page.
