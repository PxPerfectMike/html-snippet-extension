# Best HTML Snippets

This extension is like a cute and cuddly HTML coding buddy, always there to lend you a hand with its library of useful HTML snippets. And trust me, it's a real lifesaver on those days when you just can't seem to remember how to write that perfect form tag.

So, whether you're a seasoned HTML pro or a newbie just starting out, the "Best HTML Snippets" extension is a must-have for anyone who wants to write HTML like a pro in no time!

### Author - Michael Baker --> [Open to Opportunities](https://www.linkedin.com/in/pxperfectmike/)

---

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![VSCode](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)](https://code.visualstudio.com/download)

## Top Features

|             Prefix              | Description                                                                                      |          Requirements           |
| :-----------------------------: | ------------------------------------------------------------------------------------------------ | :-----------------------------: |
|           `htmlpage`            | Start off your web development with a professional-grade HTML template.                          |              None               |
|           `progress`            | Show progress with a stylish, text-based bar that updates dynamically as the task progresses.    | [JavaScript/CSS](#progress-bar) |
|           `htmltable`           | Quickly create beautiful, functional tables to organize your data.                               |              None               |
|         `userinfofield`         | Easily create fieldsets with legends to gather user information in a clean and organized manner. |              None               |
|        `restrictuploads`        | Prevent the upload of undesirable image types to keep your site secure and optimized.            |              None               |
|         `autocomplete`          | Experience the convenience of autocomplete functionality without relying on JavaScript.          |              None               |
|        `emailvalidation`        | Ensure accurate email addresses with built-in email validation for your form inputs.             |              None               |
|         `googlesearch`          | Add a Google Search form to your site for quick and easy searches.                               |              None               |
|         `googleplaces`          | Enhance your forms with the power of Google Places, allowing for easy location searching.        |              None               |
|            `autooff`            | Turn off autocomplete for select inputs to protect sensitive information.                        |              None               |
|         `newformwindow`         | Allow your users to submit forms in a new window or tab for a seamless experience.               |              None               |
| `smslink, phonelink, emaillink` | Create links for phone calls, text messages, and emails with just a few clicks.                  |              None               |
|           `hidelink`            | Hide the URL of a link for added privacy and security.                                           |              None               |
|           `filelink`            | Create links to files for easy downloading or access.                                            |              None               |
|            `noindex`            | Prevent search engines from indexing specific pages on your site for added privacy and security. |              None               |
|            `asyncjs`            | Script tag to load javascript asynchronously                                                     | [JavaScript](#asyncjs-deferjs)  |
|            `deferjs`            | Script tag to load javascript deferred                                                           | [JavaScript](#asyncjs-deferjs)  |

> ## TIP!
>
> ### While the top features are impressive, the real magic lies in the multitude of HTML snippets that are waiting for you to discover. These snippets are not just mere code snippets, but they are the building blocks of your next masterpiece. So, get ready to unleash your creativity and take your HTML coding to the next level. Whether you're a seasoned developer or a beginner, this extension is your ticket to a world of endless possibilities. If you dont find what you need with this extension please submit the proposed snippet <a href = "mailto: pxperfectmike@gmail.com">Here</a>.

## Known Issues

None

## Release Notes

### 1.0.0

Initial release of Best HTML Snippets

Please do not hesitate to contact me <a href = "mailto: pxperfectmike@gmail.com">Here</a> with any requests to add or modify snippets and I will get to it ASAP.

**_Thank you for downloading_**

# **ENJOY!**

# Requirements

## Progress Bar

```javascript
function updateProgress(percent) {
	document.getElementById('progress-bar').style.width = percent + '%';
	document.getElementById('progress-percent').innerHTML = percent + '%';
}
```

```css
#progress-bar {
	width: 0%;
	height: 30px; /* Choose your height */
	background-color: #0000ff; /* Choose a color */
}

#progress-percent {
	color: #000000;
	text-align: center;
}
```

## asyncjs, deferjs

```markdown
Requires Javascript file to work appropriately
```

[Back to top](#best-html-snippets)
