---
layout: post
title: What Does 0% Bounce Rate Mean on Google Analytics?
description: When analyzing a specific page's performance Google Analytics, it will always have a 0% bounce rate if it is not the first page the user views.
canonicalurl: http://www.neillaborce.com/what-does-0-bounce-rate-mean/
index: index, follow
excerpt_separator: <!--more-->
---

  When analyzing a specific page's performance on Google Analytics: <strong>Behavior > Site Content > All Pages</strong>, a 0% bounce rate indicates the user did not arrive on that page from an external traffic source.
  <br/><br/><img src="{{ site.baseurl }}/images/what-does-0-bounce-rate-mean.png" style="border:1px solid black" alt="What Does 0 Bounce Rate Mean?">
  <!--more-->
  <h2>What is Bounce Rate?</h2>
  Recall, <i><a href="https://support.google.com/analytics/answer/1009409?hl=en">"the bounce rate is the number of single-page sessions divided by the total number of sessions."</a></i> Single-page sessions occur when you arrive on a landing page and leave without viewing any additional pages after. For Google Analytics, a landing page is the first page you visit on a website.
  
  <h2>Single-Page Sessions</h2>
  When a user is already on the website and views a specific page, that page is not considered a landing page. And since it's not a landing page,  the number of single-page sessions for that page is going to be 0. 

  <h2>Not a Landing Page</h2>
  In other words, <strong>a page will always have a 0% bounce rate if it is not the first page the user views</strong>. Having a 0% bounce rate is not necessarily an issue or problem. A 0% bounce rate typically occurs when viewing content only accessible within the website.

  For example, a user visits a website's home page, clicks on the blog page and then clicks on a blog post. The blog post is not the landing page, so the number of single-page sessions for that blog post is 0. Calculating the bounce rate with the number of single-page sessions equal to 0 divided by the total number of sessions is always going to yield 0%.

  <h2>Other Technical Issues</h2>
  However, when assessing the bounce rate outside of Behavior > Site Content > All Pages, there may be other technical issues occurring. If a page is expected to have page views from external traffic sources (i.e. a blog post linked from other websites) but results in zero landing page metrics, there may be duplicate tags, redirect issues or third party plugins affecting Google Analytics tracking code from triggering correctly.  
  
  
  <br/>Please share this blog post if you found it useful!
  <br/>
  <br/>Neil Laborce.
  <br>
  <br>
