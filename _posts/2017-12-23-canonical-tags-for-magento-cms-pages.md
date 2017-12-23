---
layout: post
title: How to Add Canonical Tags in Magento 2.0 for CMS Pages
description: Magento 2.0 does not automatically add canonical tags for CMS pages. You can set it up manually for Product and Category Pages. But you will need to add a canonical tag using the Layout Update XML for any other page.
index: index, follow
excerpt_separator: <!--more-->
---

  <img src="{{ site.baseurl }}/images/add-canonical-tags-magento-2.png" alt="add canonical tags in magento for cms pages" style="border:1px solid black">
  
  You can create canonical tags for Product and Category pages on Magento, but for some reason, you can't create it for CMS pages. While looking for a solution, most of the documentation I found says Magento does not automatically add canonical tags for CMS pages. And that you need to leverage the Layout Update XML located in the Design section of the CMS page by inserting a custom code. But this seems to only work for Magento 1.0.

  <!--more-->

  <h2>Canonical Tags in Magento 1.0 Pages</h2>
  
  The documentation I found follows this procedure:
  <p>
  1. Click on <i>CMS</i>
  <br/>2. Click on the <i>Page</i> you want to add canonical tags
  <br/>3. Click on <i>Design</i>
  <br/>4. Insert the following code into <i>Layout Update XML</i>
  </p>

  {% gist d58048b308138c16a93bce43c7cbd834 %}
  
  It <a href="https://community.magento.com/t5/Can-Magento-do/Canonical-Tags-in-CMS-pages/td-p/164" rel="nofollow" target="_blank">seems to work for others on Magento 1.0</a> but I tried this custom code for Magento 2.0 and it didn't work!
  
  <h2>Canonical Tags in Magento 2.0 Pages</h2>
  
  Similar to Magento 2.0, I followed this procedure:
  <p>
  1. Click on <i>Content</i>
  <br/>2. Click on <i>Pages</i>
  <br/>3. Click on <i>Select > Edit</i> for the page you want to add canonical tags
  <br/>4 Click on <i>Design</i>
  <br/>5. Insert the following code into <i>Layout Update XML</i>
  </p>
  
  {% gist 148c93a39aaa59ddd3c584af8d491b0d %}
  
  <strong>I tried this custom code for Magento 2.0 instead and it worked beautifully!</strong>
  <br/>
  <br/>Neil Laborce.
  <br>
  <br>
