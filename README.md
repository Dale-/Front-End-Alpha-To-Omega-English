<h1 align="center">
<br>
  <img src="/source/images/fe-title.png" alt="Front-End-Alpha-To-Omega" width="400">
  <br>
    <br>
  Front-End-Alpha-To-Omega
  <br>
</h1>

<h4 align="center">The Front-End-Alpha-To-Omega is an exhaustive guide that help beginner to learning front end development. It's based on 14 modules, from front end knowledge graph to the most essential list of resources.</h4>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  </a>
  <a href="https://gitpod.io/#https://github.com/thedaviddias/Front-End-Checklist">
    <img src="https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod" alt="Gitpod Ready-to-Code">
  </a>
  <a href="https://creativecommons.org/publicdomain/zero/1.0/">
    <img src="https://img.shields.io/badge/license-CC0-green.svg?style=flat-square" alt="CC0">
  </a>
</p>


* If you want to learn how to become a Front-End developer, you are on the right place! 
* I will update that list with new resources and links I found on the web regularyly. 


## Table of Contents

1. **[Start here](#here)**
2. **[HTML](#html)**
3. **[CSS](#css)**
4. **[JavaScript](#javascript)**
5. **[Security](#security)**
6. **[Performance](#performance-1)**
7. **[SEO](#seo)**
8. **[Tools](#tools)**
9. **[Engineering](#tools)**
10. **[Test](#tools)**
11. **[Mini Program](#tools)**

---


### Start Here
* [📖 How the Internet Works?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work)  **|** [📹 video](https://www.youtube.com/watch?v=7_LPdttKXPc)
* Front End & Back End
* [What is HTTP?](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
* How browsers works

### HTML
* DOM
* Element
* Attribute

### CSS
* Selector
* Priority
* Specificity
* Box Model

> CSS Architecture
* BEM
* OOCS
* SMACSS

> CSS Preprocessore
* Sass
* PostCSS
* Less

### JavaScript
> Framework
* [React](https://reactjs.org/)
  * [Redux](https://redux.js.org/)
  * [Mobx](https://mobx.js.org/README.html)
* [Vue](https://vuejs.org/)
  * [VueX](https://vuex.vuejs.org/)
* [AngularJS](https://angularjs.org/)
  * RxJS
  * NgR


### [Security](https://github.com/thedaviddias/Front-End-Checklist#security)
* **HTTPS**
   HTTPS is used on every pages and for all external content (plugins, images...).
* **HTTP Strict Transport Security (HSTS)**
   The HTTP header is set to 'Strict-Transport-Security'.'Strict-Transport-Security'
* **Cross Site Request Forgery (CSRF)**
  You ensure that requests made to your server-side are legitimate and originate from your website / app to prevent CSRF attacks.
* **Cross Site Scripting (XSS)**
  Your page or website is free from XSS possible issues.
* **Content Type Options**
  Prevents Google Chrome and Internet Explorer from trying to mime-sniff the content-type of a response away from the one being declared by the server.
* **X-Frame-Options (XFO)**
  Protects your visitors against clickjacking attacks.
* **Content Security Policy**
  Defines how content is loaded on your site and from where it is permitted to be loaded. Can also be used to protect against clickjacking attacks.


### Performance
* **Add long-term headers expiration dates**
  Near-future headers expiration dates prevent effective caching and cause a repeat visit to your site from the device to be slower than necessary.
* **Make fewer HTTP requests**  
  Latency has a substantial impact on mobile application performance. Reducing the number of unique objects on the page will help reduce sensitivity to latency.
* **Remove duplicate JavaScript and CSS**
  Evaluating redundant scripts wastes time—and the duplicate parsing happens even if the script is cacheable. Duplicate scripts also waste mobile bandwidth.
* **Avoid HTTP 404 (Not Found) error**  
  Making an HTTP request and receiving a 404 (Not Found) error is expensive and degrades the user experience. Some sites have helpful 404 messages (for example, "Did you mean...?"), which may assist the user, but server resources are still wasted.
* **Goals to achieve**
  * First Meaningful Paint under 1 second
  * Time To Interactive under 5 seconds for the "average" configuration (a $200 Android on a slow 3G network with 400ms RTT and 400kbps transfer speed) and under 2 seconds for repeat visits
  * Critical file size under 170Kb gzipped
* **Minified HTML**
  Your HTML is minified.
* **Lazy loading**
  Images, scripts and CSS need to be lazy loaded to improve the response time of the current page (See details in their respective sections).
* **Cookie size**
  If you are using cookies be sure each cookie doesn't exceed 4096 bytes and your domain name doesn't have more than 20 cookies.
* **Third party components**
  Third party iframes or components relying on external JS (like sharing buttons) are replaced by static components when possible, thus limiting calls to external APIs and keeping your users activity private.

### SEO
* Google Analytics
* Headings logic
* sitemap.xml
* robots.txt
* Structured Data
* Sitemap HTML
* Pagination link tags

### Debugging Tools
> Package Managers
* npm
* yarn

> Version Control
* Git

> IDE

* Visual Studio Code
* Atom
* Sublime Text
* WebStorm
* Vim
* Emacs
* Brackets

> 调试工具
* Firebug/Firebug-lite/Web Inspector
* YSlow/Smushit
* IEDeveloperToolBar/IETester
* SuperPreview/JsBeautifier
* Fiddler/WireShark/tcpdump


### Engineering

> Code Quality
* JSCS
* ESLint
* stylelint
* htmlhint

> Build System
* webpack
* gulp
* grunt

> Code Analysis
* Code climate

### Test
> Unit Test
 * Jasmine
* Mocha
* Protractor
* Karma
* Jest
> End to End Test

> Integration Test

> Test Coverage

### Mini Program
* Taro
* WePY
* mpvue