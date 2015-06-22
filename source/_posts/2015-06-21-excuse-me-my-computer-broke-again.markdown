---
layout: post
title: "EXCUSE ME!!! My Computer Broke!"
date: 2015-06-21 21:04:20 -0400
comments: true
categories: "Flatiron School"
---
<p>There she goes. Again.</p>  
<p><font color="red">#Shocking </font></p> 
<p>It's always MY fault.  Like there's some sort of magic fairy dust sprinkled on <em>everyone else's</em> computer except *hers*. She even got an instructor to help her this time. Wow.  They are going to be in for a tasty treat--look what she put in!</p>



```ruby
evil_pokemons.each do
Pretty Please scrape the pokemons for me!!!!!
end
```

<p>Please. Tell me she's joking.</p> 

<p>Oh Wait, Shhhh. This is going to be good! She was just asked if she read the Nokogiri tutorial.  SAY WHAT???? <em>She DID</em>?  She was on that website for .56 seconds.  #FACTS. <em><strong>(PLEASE!!! JUST OPEN MY PAGES AND I WILL SPILL ALL! NO SNITCHES GET STICHES FOR ME!!!)</strong></em>.</p>

<p>Deep breaths. Lets turn on this fan. Look, I mean had she read it, she would have seen it is all really quite simple. You just give me a few, quick, straightforward commands at the top of your page, and I make like a shepherd and flock!</p>

```ruby
require 'nokogiri'
require 'open-uri'
```

<p>You can even put these commands into irb to play around with, and I will set up your ENTIRE environment perfectly (just make sure I return "true" after each command).</p> 

<P> Next, kindly let me know what language you would like to use (I'm <em>very</em> versatile), and for heaven's sake don't be lazy, name your document something fun--'doc' is just so uneventful.</p>

```ruby
html = open('website').read
doc_name = Nokogiri::HTML(html)
```
<p>Now, you are at the part where you get to chillax.  Open up your browser by right clicking in crome on inspect element, and you should be able to use the nifty magnifying glass to help you locate any element's css selector you would like on the page. Once you've found the css selector of your desired element-try it out-I mean, you wouldn't buy a car without test driving it first, why should scraping be <em>any</em> different? Feel free to use binding.pry, a simple puts command, or the beautiful world of irb!</p>

```ruby
variable_doc.search(" ").text
variable_doc.css(" ").text
```
<p>.search and .css mean the same thing, so don't fret about that!  Once you have successfully matched the css selector to your element you are good to go and can head right back to your ruby program. Adding .text at the end returns--you guessed it--the text that your css selector selected!  I will take care of all the rest (like I ALWAYS do 😘).</p>

![Jimmy Jet and His TV Set](https://thereadingwomb.files.wordpress.com/2011/07/jimmy-jet.gif)