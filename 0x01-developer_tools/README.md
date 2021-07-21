# 0x01. Developer tools

## Learning Objectives

#### * What Developer Tools in your browser are
Nowadays, web browsers include a powerful suite of tools for developers that can do a range of different things, from inspecting currently-loaded HTML, CSS and JavaScript to showing which assets the page has requested and how long it takes them to load.

#### * How to open the Developer Tools on Chrome, Firefox, Safari, and Edge.
##### Google Chrome
Open the Chrome Menu in the upper-right-hand corner of the browser window and select More Tools > Developer Tools. You can also use the shortcut Option + ⌘ + J (on macOS), or Shift + CTRL + J (on Windows/Linux).
##### Microsoft Edge
Open the Edge Menu in the upper-right-hand corner of the browser window and select F12 Developer Tools. You can also press F12 to open it.
##### Mozilla Firefox
Click on the Firefox Menu in the upper-right-hand corner of the browser and select Web Developer > Browser Console. You can also use the shortcut Shift + ⌘ + J (on macOS) or Shift + CTRL + J (on Windows/Linux).

#### * How to use the elements tab to edit HTML and CSS
Find the ansuer in this [article](https://www.lucidchart.com/techblog/2018/05/01/live-editing-html-css-chrome-devtools/)

#### * How to audit a page according to the tips suggested by Lighthouse
Google Lighthouse has the option of running the Audit for Desktop as well as mobile version of your page(s). The top metrics that will be measured in the Audit are:

Performance: This score is an aggregation of how the page fared in aspects such as (but not limited to) loading speed, time taken for loading for basic frame(s), displaying meaningful content to the user, etc. To a layman, this score is indicative of how decently the site performs, with a score of 100 meaning that you figure in the 98th percentile, 50 meaning that you figure in the 75th percentile and so on.

PWA Score (Mobile): Thanks to the rise of Service Workers, app manifests, etc., a lot of modern web applications are moving towards the PWA paradigm, where the objective is to make the application behave as close as possible to native mobile applications. Scoring points are based on the Baseline PWA checklist laid down by Google which includes Service Worker implementation(s), viewport handling, offline functionality, performance in script-disabled environments, etc.

Accessibility: As you might have guessed, this metric is a measure of how accessible your website is, across a plethora of accessibility features that can be implemented in your page (such as the ‘aria-’ attributes like aria-required, audio captions, button names, etc.). Unlike the other metrics though, Accessibility metrics score on a pass/fail basis i.e. if all possible elements of the page are not screen-reader friendly (HTML5 introduced features that would make pages easy to interpret for screen readers used by visually challenged people like tag names, tags such as <section>, <article>, etc.), you get a 0 on that score. The aggregate of these scores is your Accessibility metric score.

Best Practices: As any developer would know, there are a number of practices that have been deemed ‘best’ based on empirical data. This metric is an aggregation of many such points, including but not limited to:Use of HTTPS
Avoiding the use of deprecated code elements like tags, directives, libraries, etc.
Password input with paste-into disabled
Geo-Location and cookie usage alerts on load, etc.

### * How to create and run snippets on a page
Click the Snippets tab to open the Snippets pane. You might need to click More Tabs More Tabs in order to access the Snippets option.

Open the Snippets pane with the Command Menu 
Focus your cursor somewhere inside of DevTools.

Press Control+Shift+P or Command+Shift+P (Mac) to open the Command Menu.

Start typing Snippets, select Show Snippets, and then press Enter to run the command.

How to block requests
How to know how much JavaScript or CSS is used on a page
How to detect 404 issues
How to move elements on a webpage