Jelica Thorn Music - TESTING

![Jelica Thorn Music Website shown on different devices](docs/images/reponsive.png)

You can view the page [here](https://andreasawenlof.github.io/pp1-final/)
---

## CONTENTS

- [You can view the page here](#you-can-view-the-page-here)
- [CONTENTS](#contents)
- [AUTOMATED TESTING](#automated-testing)
  - [ W3C Validator](#w3c-validator)
  - [Lighthouse](#lighthouse)
    - [Desktop Results](#desktop-results)
    - [Mobile Results](#mobile-results)
    - [Testing Results of the Media Section on both mobile and desktop are affected by third party cookies and due to the lack of access to the server the http header cannot be set/changed. Therefor the Results cannot be increased.](#testing-results-of-the-media-section-on-both-mobile-and-desktop-are-affected-by-third-party-cookies-and-due-to-the-lack-of-access-to-the-server-the-http-header-cannot-be-setchanged-therefor-the-results-cannot-be-increased)
- [MANUAL TESTING](#manual-testing)
  - [Testing User Stories](#testing-user-stories)
    - [First Time Visitors Goals](#first-time-visitors-goals)
    - [Returning Visitors Goals](#returning-visitors-goals)
  - [Full Testing](#full-testing)
- [FIXED AFTER MENTOR FEEDBACK](#fixed-after-mentor-feedback)
- [FIXED AFTER USER FEEDBACK/EXPERIENCE](#fixed-after-user-feedbackexperience)
- [BUGS](#bugs)

---

## AUTOMATED TESTING


###  W3C Validator
[WC3](https://validator.w3.org/) was used to validate all HTML and CSS.
- [index.html](https://andreasawenlof.github.io/pp1-final/index.html) - passed
- [media.html](https://andreasawenlof.github.io/pp1-final/media.html) - passed
- [contact.html](https://andreasawenlof.github.io/pp1-final/contact.html) - passed
- [404.html](https://andreasawenlof.github.io/pp1-final/404.html) - passed

### Lighthouse

Lighthouse
I used Lighthouse within the Chrome Developer Tools to test the performance, accessibility, best practices and SEO of the website.

#### Desktop Results
![Test Index Desktop](docs/images/test/test-index-desk.png)
![Test Media Desktop](docs/images/test/test-media-desk.png)
![Test Contact Desktop](docs/images/test/test-contact-desk.png)
![Test 404 Error Desktop](docs/images/test/test-404-desk.png)

#### Mobile Results
![Test Index Mobile](docs/images/test/test-index-mob.png)
![Test Media Mobile](docs/images/test/test-media-mob.png)
![Test Contact Mobile](docs/images/test/test-contact-mob.png)
![Test 404 Error Mobile](docs/images/test/test-404-mob.png)

#### Testing Results of the Media Section on both mobile and desktop are affected by third party cookies and due to the lack of access to the server the http header cannot be set/changed. Therefor the Results cannot be increased.

## MANUAL TESTING

### Testing User Stories

#### First Time Visitors Goals
| Goals | How are they achieved? |
| :--- | :--- |
| `First Time Visitors` |
|  |  |  |
| I want to know what the artist is about and through that know if i'm interested or not | By providing an "about-section" on the homepage instead of another link attract the user right away |
| I want to be able to listen or watch the artist media either on the site or being able to click external links that can open in a new tab | There is a media section and there are music and videos that you can either play on the site or click to go to an external link opening in a new tab |
| I want to be able to contact the artist or send them a message | A contact section exists where the user can write a message to the artist |

#### Returning Visitors Goals
| Goals | How are they achieved? |
| :--- | :--- |
| `Returning Visitors` |
|  |  |  |
| I want to see updates of new releases | There is a media section where you can post that |
| I want to be able to contact her or send a message | There is a contact section where the user can send the artist a message |
| I want to still be able to relate and recognize myself as last time | At the homepage the user can read about the artist and their vision |


### Full Testing
Full testing was performed on the following devices:

- Laptop:
  - Macbook Air M2 13,6"
- Mobile Devices:
  - iPhone X

Tested the site using the following browsers:
- Google Chrome (All devices)
- Safari  (All Devices)
- Firefox (All devices)
- Microsoft Edge (Desktop)

- Had friends and family testing the site and reported very few issues (all those issues got fixed as you can see in the bug/fix section below).

## FIXED AFTER MENTOR FEEDBACK
- Removed transparency on header and footer
- Merged about.html content to be at the home page for better attraction of visitor
- Added more content in media section
- Added Copyright in bottom of footer
- Submit didn't go anywhere, added link to formdump.

## FIXED AFTER USER FEEDBACK/EXPERIENCE
- Split up the media section into Music and Video
- Wrapped the logo in a link to index.html
- Added a 404.html page
- Added hover effects on social links as well to look like the header
- Added that social media links opened up in a new tab

## BUGS
| Bug | Fix |
| :--- | :--- |
| Scroll-bar appeared in the "who-section" on Home | Removed "overflow" from style.css. |
| Viewing contact form on Firefox, placeholder was too aligned to the left | Increased the padding-left |
| Background scrolled with the content | Added background-attachment: fixed |
| Everything was transparent even the videos on media section | Instead of Opacity i added an alpha channel to the color and changed it from HEX to RGBA |

No unsolved bugs except the above mentioned Lighthouse Result that I'm not able to influence due to lack of access to backend.