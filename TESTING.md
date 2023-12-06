# Testing

Return back to the [README.md](README.md) file.

Welcome to the testing section of my project documentation! In this segment, my aim is to assure that I’ve undertaken thorough testing to confidently affirm the effective functionality of my site, CharityXI. Throughout this documentation, I’ll delve into each project feature, ensuring they operate as intended. My commitment is to provide users with an uncomplicated and seamless experience, facilitating the achievement of their goals on CharityXI.


## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files. All HTML files were tested using the live deployed site!

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Ffirstnamejonas.github.io%2Fcharity-xi%2F) | ![screenshot](documentation/html-validation-home.png) | No errors or warnings to show. |
| Teams | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Ffirstnamejonas.github.io%2Fcharity-xi%2Fteams.html) | ![screenshot](documentation/html-validation-teams.png) | No errors or warnings to show. |
| Tickets | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Ffirstnamejonas.github.io%2Fcharity-xi%2Ftickets.html) | ![screenshot](documentation/html-validation-tickets.png) | No errors or warnings to show. |
| Confirmation | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Ffirstnamejonas.github.io%2Fcharity-xi%2Ftickets.html) | ![screenshot](documentation/html-validation-confirmation.png) | No errors or warnings to show. |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files. All CSS files were tested using the live deployed site!

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Ffirstnamejonas.github.io%2Fcharity-xi%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=de#warnings) | ![screenshot](documentation/css-validation-style.png) | Pass: No Errors // 12 Warnings for same color on button, this does not effect the visibility |


## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Teams | Tickets | Confirmation | Notes |
| --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/21.png) | ![screenshot](documentation/22.png) | ![screenshot](documentation/23.png) | ![screenshot](documentation/24.png) | Works as expected |
| Firefox | ![screenshot](documentation/17.png) | ![screenshot](documentation/18.png) | ![screenshot](documentation/19.png) | ![screenshot](documentation/20.png) | Works as expected |
| Safari | ![screenshot](documentation/13.png) | ![screenshot](documentation/14.png) | ![screenshot](documentation/15.png) | ![screenshot](documentation/16.png) | Works as expected |


## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | About | Contact | etc | Notes |
| --- | --- | --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/5.png) | ![screenshot](documentation/6.png) | ![screenshot](documentation/7.png) | ![screenshot](documentation/8.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/1.png) | ![screenshot](documentation/2.png) | ![screenshot](documentation/3.png) | ![screenshot](documentation/4.png) | Works as expected |
| Desktop | ![screenshot](documentation/13.png) | ![screenshot](documentation/14.png) | ![screenshot](documentation/15.png) | ![screenshot](documentation/16.png) | Works as expected |
| iPhone 13 | ![screenshot](documentation/9.png) | ![screenshot](documentation/10.png) | ![screenshot](documentation/11.png) | ![screenshot](documentation/12.png) | Works as expected |


## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse-home.png) | Lower performance due to video file and logo|
| Teams | ![screenshot](documentation/lighthouse-teams.png) | Low performance score due to large images |
| Tickets | ![screenshot](documentation/lighthouse-tickets.png) | Low performance score due to large images |
| Confirmation | ![screenshot](documentation/lighthouse-confirmation.png) | Lower accessibility due to auto refresh of the page |


## User Story Testing

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to know who’s participating in the CharityXI match, so that I can decide whether to buy tickets or not. | ![screenshot](documentation/feature06.png) |
| As a new site user, I would like to know where the CharityXI match is taking place, so that I know if I have to plan any travels in advance. | ![screenshot](documentation/feature05.png) |
| As a new site user, I would like to be informed about the project CharityXI, so that I can tell my friends and / or family more about it. | The Website as a whole functions as a presantation tool for this case |
| As a returning site user, I would like to show the information to family and / or friends, so that I can convince them to buy tickets with me. | The Website as a whole functions as a presantation tool for this case |


## Bugs / Fails

- Bad performance due to slow response time because of large images“

    ![screenshot](documentation/lighthouse-teams.png)
    ![screenshot](documentation/lighthouse-tickets.png)

- To get a higher score for performance, I changed my hero images from .svg to .png

    ![screenshot](documentation/lighthouse-teams-fixed.png)
    ![screenshot](documentation/lighthouse-tickets-fixed.png)


## Unfixed Bugs

There are no remaining bugs that I am aware of.