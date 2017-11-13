---
layout: post
title: 4 Excel Formulas for PPC Keywords That You Should Know
description: Four useful functions you should be using when drafting PPC keywords include TRIM, CONCATENATE, SUBSTITUTE and LOWER. Learn more!
index: index, follow
excerpt_separator: <!--more-->
---

  <img src="{{ site.baseurl }}/images/4-excel-formulas-for-ppc-keywords.png" style="border:1px solid black" alt="4 Excel Formulas for PPC Keywords You Should Know">
  
  <strong>Fun Fact</strong>: I've been using Excel since I was 13, organizing my life, life goals, budget and my once-upon-a-time engineering work into spreadsheets on top of spreadsheets on top of spreadsheets (I'm now 28). And a lot of these functions, formulas and pivot tables can be seen permanently engraved on the inside of my forehead. So when I entered the world of SEO, SEM, and PPC, my intense appreciation for Excel was a useful skill set to leverage. 
  <!--more-->
  
  If you're using Excel to draft a keyword list for your PPC search campaign, four useful functions you should be using include TRIM, CONCATENATE, SUBSTITUTE and LOWER. These four functions can make your keyword drafting process faster and more productive. 

  <h2>TRIM, CONCATENATE, SUBSTITUTE and LOWER</h2>

  1) The <strong>TRIM</strong> function removes all extra spaces in a cell, leaving only one space character between words and zero space characters at the beginning or end of the string.

  <p class="code"><strong>=TRIM(text)</strong></p>

  2) The <strong>CONCATENATE</strong> function combines two or more text strings into one string. An alternative to the CONCATENATE function is using the <strong>AMPERSAND</strong> character instead. 

  <p class="code"><strong>=CONCATENATE(text1, [text2], ...)</strong>
  <br/><strong>=A1&"text1"&B2</strong></p>

  3) The <strong>SUBSTITUTE</strong> function replaces a specified text in a string with new text. The function replaces all occurrences of the specified text by default but you can also specify the number of replacements using [instance_num].

  <p class="code"><strong>=SUBSTITUTE(text, old_text, new_text, [instance_num])</strong></p>

  4) The <strong>LOWER</strong> function converts all characters in a string to lowercase text.

  <p class="code"><strong>=LOWER(text)</strong></p>
  
  <h3>Some examples</h3>
  <img src="{{ site.baseurl }}/images/4-excel-formulas-example.png" style="border:1px solid black" alt="Example of 4 Excel Formulas for PPC Keywords">

  <h2>How To Update Broad Match Type to Broad Match Modifier Keywords?</h2>

  If you need to update your broad match type keywords into broad match modifier keywords, leverage the SUBSTITUTE function and AMPERSAND character.  You can replace all space characters with " +" and insert a "+" at the beginning of the string.

  <p class="code"><strong>="+"&substitute(A1," "," +")</strong></p>
  
  <img src="{{ site.baseurl }}/images/substitute-function.png" style="border:1px solid black" alt="broad match type to broad match modifier">

  <h2>How To Update Broad Match Type to Phrase or Exact Match Keywords?</h2>

  You can use either the CONCATENATE function or AMPERSAND character. Personally, I prefer the AMPERSAND as I find it quicker to type. Note that Excel uses quotation marks for formulas, so you need to define the " character by typing it four times.

  <p class="code"><strong>=""""&A1&""""</strong>
  <br/><strong>="["&A1&"]"</strong></p>

  <br/>With the CONCATENATE function, you insert the quotation marks or opening/closing brackets between the text.

  <p class="code"><strong>=concatenate("""",A1,"""")</strong>
  <br/><strong>=concatenate("[",A1"]")</strong></p>
  
  <img src="{{ site.baseurl }}/images/concatenate-ampersand-function.png" style="border:1px solid black" alt="broad match type to phrase or exact match">

  <h2>How To Clean Up Your PPC Keyword List?</h2>

  Keywords in Adwords are not case-sensitive, so to keep things clean and organized, keep your list lowercased. When analyzing search queries from previous campaigns, users may often have spelling mistakes and extra spaces. Use the TRIM and LOWER function along with the "Spelling" tool to correct misspelled words, turn them lowercased and remove all extra space characters. 

  <img src="{{ site.baseurl }}/images/lower-trim-function.png" style="border:1px solid black" alt="broad match type to phrase or exact match">
  
  <br/>Please share this blog post if you found it useful!
  <br/>
  <br/>Neil Laborce.
  <br>
  <br>
