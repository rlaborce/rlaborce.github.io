---
layout: post
title: How to do Site-Wide A/B Testing on Google Optimize?
description: To do site-wide A/B testing on Google Optimize, simply update your targeting to include all pages. That's it! 
canonicalurl: http://www.neillaborce.com/site-wide-experiment-on-google-optimize
index: index, follow
excerpt_separator: <!--more-->
---

  <img src="{{ site.baseurl }}/images/optimize.png" style="border:1px solid black">
  
  You may find yourself needing to experiment with an element that exists on all pages for conversion rate optimization. <em>Let's say you want to test a call-to-action placed in the footer to determine how many conversions you can get if you make the font bigger or change the colour.</em> With Google Analytics Experiment and Google Optimize, you can conduct A/B and multivariate testing on a page-by-page basis but <strong>what about a site-wide option?</strong> 
  <!--more-->
  
  It's possible with Google Analytics Experiment however it gets a little bit complicated. Most of the time you'll need to get your developers involved. However, with Google Optimize, it's pretty simple: <strong>just update your targeting to include all pages. That's it! Targetting all pages will trigger the experiment for every page where the element exists.</strong>

  First, let's review how to create an experiment... (see <a href="https://support.google.com/360suite/optimize/answer/6211930" rel="nofollow" target="_blank">Google's Documentation</a>)

  <h2>Step 1: Create an experiment on Google Optimize</h2>

  &ndash; Click on your Container name to get to the Experiments page
  <br/>&ndash; Click CREATE EXPERIMENT
  <br/>&ndash; Enter an Experiment name
  <br/>&ndash; Enter an Editor page URL (choose a generic page that contains your element)
  <br/>&ndash; Click A/B test
  <br/>&ndash; Click CREATE
  

  <h2>Step 2: Configure your experiment objectives in the Objective tab</h2>

  &ndash; Select a Google Analytics view
  <br/>&ndash; Select a Primary Objective
  <br/>&ndash; Add a description and hypothesis
  <br/>&ndash; Click SAVE

  <h2>Step 3: Create your variant page</h2>

  &ndash; Click on CREATE VARIANT
  <br/>&ndash; Add a variant name
  <br/>&ndash; Click ADD
  <br/>&ndash; Click on the variant (you will redirect to the Optimize Visual Editor)
  <br/>&ndash; Use the editor panel to make your changes on the target element
  <br/>&ndash; Click Save to save the variant
  <br/>&ndash; Click Done

  This is where the process changes...

  <h2>Step 4: Configure your experiment target in the Targeting tab</h2>
  
  <img src="{{ site.baseurl }}/images/site-wide-ab-testing-edit-condition.png" style="border:1px solid black" alt="edit the additional condition">

  &ndash; Ensure the activation event is set to "evaluate on page load"
  <br/>&ndash; Edit the additional condition
  <br/>&ndash; Update the condition to: URL contains [yourdomainname.com]

  <img src="{{ site.baseurl }}/images/site-wide-ab-testing-condition.png" style="border:1px solid black" alt="update AB test target">

  Now, your experiment triggers whenever this condition is true. And since all your pages contain your domain name, it will fire the test on all pages. <strong>And since your element exists on all pages, the original or variant will display accordingly.</strong>

  Try it for yourself and see how it works. And don't forget to share this blog post if you found it useful!

  <br/>
  <br/>Neil Laborce.
  <br>
  <br>
