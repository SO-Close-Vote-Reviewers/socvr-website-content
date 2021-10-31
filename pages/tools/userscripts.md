# Userscripts

There are a bunch of [useful userscripts for Stack Overflow out there](https://stackapps.com/questions/tagged/script "userscripts and browser extensions on Stack Apps"). Userscripts add functionality to the site by running scripts in your browser. All major browsers support userscripts by installing a userscript manager extension, for example [Tampermonkey](https://tampermonkey.net/) or [Violentmonkey](https://violentmonkey.github.io/).

- [How to install a userscript?](https://greasyfork.org/en/help/installing-user-scripts)
 - With [Tampermonkey](https://www.tampermonkey.net/), [Violentmonkey](https://violentmonkey.github.io/), or [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) installed, from a GitHub userscript page you can [click the "Raw" button](https://i.stack.imgur.com/75kID.gif "GIF showing what happens in Tampermonkey when you click the 'Raw' button"). (Greasemonkey is recommended against, due to general userscript compatibility issues.)</dd>

### <a id="our-scripts" href="#our-scripts" class="hover-visible"></a>Our own scripts

##### See [our GitHub userscript repository](https://github.com/SO-Close-Vote-Reviewers/UserScripts) with the full list of our scripts!

##### <a id="our-commonly-used-scripts" href="#our-commonly-used-scripts" class="hover-visible"></a>Our most commonly used scripts


 - [\*-pls Request Generator](https://github.com/SO-Close-Vote-Reviewers/UserScripts#user-content-so-close-vote-request-generator "instructions in our GitHub repository")&nbsp;&nbsp;<sup><sub>([GitHub](//github.com/SO-Close-Vote-Reviewers/UserScripts/blob/master/SECloseVoteRequestGenerator.user.js))</sub></sup>&nbsp;<sup><sub>([install](//github.com/SO-Close-Vote-Reviewers/UserScripts/raw/master/SECloseVoteRequestGenerator.user.js))</sub></sup>
   -  This userscript is the primary method of posting `cv-pls` requests to SOCVR.
   -  It adds a link under each question, so you can send a `cv-pls` to a chatroom (e.g. SOCVR).
   -  <s>When you're unable to install userscripts, limited functionality is [available as a bookmarklet](https://github.com/SO-Close-Vote-Reviewers/UserScripts#user-content-creating-the-bookmarklet). However, the bookmarklet has not been updated in some time, so may not be functional, due to changes made by Stack Exchange to their pages.</s> The bookmarklet is not currently functional.
   -  **Greasemonkey users:** There there are some incompatibilities. From what people have reported, it will mostly function, but there are limitations. Makyen recommends against using Greasemonkey due to general compatibility issues with a large number of userscripts. It is [recommended that you use a different userscript manager](https://chat.stackoverflow.com/transcript/41570?m=49330127#49330127) and run the version of the Request Generator linked earlier. 
 - [Magic™ Editor](https://github.com/SO-Close-Vote-Reviewers/UserScripts#user-content-magic-editor "instructions in our GitHub repository")&nbsp;&nbsp;<sup><sub>([GitHub](https://github.com/SO-Close-Vote-Reviewers/UserScripts/blob/master/Magic%E2%84%A2Editor.user.js))</sub></sup>&nbsp;<sup><sub>([install](https://github.com/SO-Close-Vote-Reviewers/UserScripts/raw/master/Magic%E2%84%A2Editor.user.js))</sub></sup>
   - While you're editing a post, one click fixes the most common spelling and grammar mistakes.
 - Unclosed Request Review Script&nbsp;&nbsp;<sup><sub>([GitHub](https://github.com/SO-Close-Vote-Reviewers/UserScripts/blob/master/UnclosedRequestReview.user.js))</sub></sup>&nbsp;<sup><sub>([install](https://github.com/SO-Close-Vote-Reviewers/UserScripts/raw/master/UnclosedRequestReview.user.js))</sub></sup>
   - Enhances the display of requests and question links in the main chat page.
   - Provides brief question and answer status in the main chat window.
   - Indicates on the main chat page which requests are complete.
   - Enhances the search pages for `cv-pls`, `reopen-pls`, and `del-pls` requests, giving more detailed status, sorting, filtering, etc. Allows you to focus only on the open requests meeting the criteria you desire to work on.
 - Review Finder&nbsp;&nbsp;<sup><sub>([GitHub](https://github.com/SO-Close-Vote-Reviewers/UserScripts/blob/master/ReviewFinder.user.js))</sub></sup>&nbsp;<sup><sub>([install](https://github.com/SO-Close-Vote-Reviewers/UserScripts/raw/master/ReviewFinder.user.js))</sub></sup>
   - finds the review of a post by searching for the post's id in the current review queue's history.
 - Close Vote Review Shortcuts&nbsp;&nbsp;<sup><sub>([GitHub](https://github.com/SO-Close-Vote-Reviewers/UserScripts/blob/master/CloseVoteShortcuts.user.js))</sub></sup>&nbsp;<sup><sub>([install](https://github.com/SO-Close-Vote-Reviewers/UserScripts/raw/master/CloseVoteShortcuts.user.js))</sub></sup>
   - adds keyboard shortcuts in the close-vote review-queue and close dialog, so your hands never have to leave the keyboard


### <a id="endorsed-scripts" href="#endorsed-scripts" class="hover-visible"></a>Endorsed scripts

 - [AutoReviewComments](http://stackapps.com/questions/2116/autoreviewcomments-pro-forma-comments-for-se "description and instructions on Stack Apps")&nbsp;&nbsp;<sup><sub>([GitHub](https://github.com/Benjol/SE-AutoReviewComments))</sub></sup>&nbsp;<sup><sub>([install](https://raw.github.com/Benjol/SE-AutoReviewComments/master/dist/autoreviewcomments.user.js))</sub></sup>
   - You can use [our collection of comments](https://github.com/SO-Close-Vote-Reviewers/auto-comments), or create your own.
 - Magic™ Tag Review 2&nbsp;&nbsp;<sup><sub>([GitHub](https://github.com/Tiny-Giant/myuserscripts/blob/master/MagicTagReview2.user.js))</sub></sup>&nbsp;<sup><sub>([install](https://github.com/Tiny-Giant/myuserscripts/raw/master/MagicTagReview2.user.js))</sub></sup>
   - Review questions in a tag with filtering on multiple criteria, including by close votes and delete votes 
 - [Roomba Forecaster](https://stackapps.com/questions/7239/roomba-forecaster-when-will-the-question-be-roombaed-if-it-wont-why "description and instructions on Stack Apps")&nbsp;&nbsp;<sup><sub>([GitHub](https://github.com/makyen/StackExchange-userscripts/blob/master/Roomba-Forecaster/RoombaForecaster.user.js))</sub></sup>&nbsp;<sup><sub>([install](https://github.com/makyen/StackExchange-userscripts/raw/master/Roomba-Forecaster/RoombaForecaster.user.js))</sub></sup>
   - Tells the user if the question is eligible for being deleted by the [Roomba](http://stackoverflow.com/help/roomba).

### <a id="additional-scripts" href="#additional-scripts" class="hover-visible"></a>Additional Stack Exchange userscripts

- [Charcoal HQ userscripts](https://charcoal-se.org/scripts)&nbsp;&nbsp;<sup><sub>([GitHub](https://github.com/Charcoal-SE/userscripts))</sub></sup>
  - scripts to provide feedback to [SmokeDetector](https://charcoal-se.org/#whats-smokey)&nbsp;([wiki](https://github.com/Charcoal-SE/SmokeDetector/wiki)), among other things
  - The ones to provide feedback to SmokeDetector require a [review-approved Metasmoke account](https://github.com/Charcoal-SE/Userscripts/wiki/FDSC#user-content-what-do-i-need-to-use-fdsc), in addition to being [authorized to use SmokeDetector](https://socvr.org/faq#what-is-smoke-detector-and-how-can-i-participate).
- [Stack Apps](https://stackapps.com/questions/tagged/script)
  - wide variety of userscripts/browser extensions for Stack Exchange
