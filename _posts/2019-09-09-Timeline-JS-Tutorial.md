---
layout: post
title: "Timeline JS Tutorial"
date: 2019-09-09
---

## A Little Introduction to Timeline JS ##

1. Timeline JS is an open-source tool that allows anyone to create content-rcih timelines. Do more than present content, give it to users in an interactive and compelling way. Timelines can be about any event you choose, but try to stick with events that have a strong chrological narrative. Events that skip forwards and then backwards in time are no good.
2. Media forms you can use in your Timeline include Youtube, Vimeo, Wikipedia articles, tweets, audio files from Soundcloud, and more.
3. Customize your Timeline, with background colors and images. Use simple html formatting tags to change font size and color.

### A Basic Step-by-Step Guide to Create Your Timeline: Adapted from [Timeline JS at knight lab](https://timeline.knightlab.com/#make) ###

1. **Getting Started:** Log into your Google account to download spreadsheet template and save on Google Drive [Timeline JS Spreadsheet Template](https://docs.google.com/spreadsheets/d/1L-BYrNCEAcSwn8Rr91uiYwee7VD-pK4x38auquRepm0/edit#gid=0)
    1. edit the timeline template to include the dates, text, links, and media specific to your project.
    2. You will fill you data into horizontal rows provided in the template. Delete the example data KnightLabs has in the template and then add your own.
    3. [Here is a link to my spreadsheet](https://docs.google.com/spreadsheets/d/1G_DhfiS3g_mIs-lPvuATjqSIDCgRX5gSK9W4pY1SeA0/edit?usp=sharing)
    
2. **Publish to the Web**
   1. Under the 'File' menu, select 'Publish to the Web'
   2. copy the URL from the top of the page

3. **Generate Your Timeline**
   1. This feature hosts your timeline on the Timeline JS site. While it's here you can make changes on your spreadsheet and preview those changes.
   
4. **Share Your Timeline** Yay!

5. **Example Video on Youtube**

    >[![Timeline JS](http://img.youtube.com/vi/y9kViqYzG3E/0.jpg)](http://www.youtube.com/watch?v=y9kViqYzG3E "Timeline JS")

### Important Notes on Timeline JS: Tricks & Hints ###

  * When importing in Timeline, make sure the URL you use takes you straight to the image. A URL to a wikipedia page where the image is will NOT work in Timeline. On Wikimedia, there should be a button that says "Use this file on the web" which gives you the URL you're looking for. Or, right click on an image and select "Open in a new tab" which should give you a usable URL too.
  * When working with eras, make sure your eras have starting and end dates. Similarly, if you give the exact hour an event started, it needs to have an ending hour as well. 

### HTML In-line Formatting ###

  * Want to change the color of your text in your Timeline? Use HTML color codes, [sourced here](https://html-color-codes.info/)

<div class="blurb">
<p>Snippet 1: <code>In-line Color Formatting with Color Codes</code></p>
<pre class="prettyprint pre-scrollable"><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
	&lt;head&gt;
        	&lt;pstyle="color:#6E6E6E!important;font-size:30px;"&gt;content of p&lt;/h1&gt;
    	&lt;/head&gt;
    	&lt;head&gt;
        	&lt;h1style="color:#0431B4!important;font-size:80px;"&gt;content of h1&lt;/h1&gt;
&lt;/head&gt;</code></pre>
	
<iframe src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1G_DhfiS3g_mIs-lPvuATjqSIDCgRX5gSK9W4pY1SeA0&font=Default&lang=en&initial_zoom=2&start_at_slide=6&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>

<p>Snippet 2: <code>In-line Color Formatting with Color Names</code></p>
<pre class="prettyprint pre-scrollable"><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
	&lt;head&gt;
		&lt;pstyle="color:grey!important;font-size:30px;"&gt;content of p tag&lt;/h1&gt;
	&lt;/head&gt;
	&lt;head&gt;
        	&lt;pstyle="color:blue!important;font-size:80px;"&gt;content of p tag&lt;/h1&gt;
&lt;/head&gt;</code></pre>

<iframe src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1G_DhfiS3g_mIs-lPvuATjqSIDCgRX5gSK9W4pY1SeA0&font=Default&lang=en&initial_zoom=2&start_at_slide=1&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>

<p>Snippet 3: <code>In-line Font-Size Formatting</code></p>
<pre class="prettyprint pre-scrollable"><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
	&lt;head&gt;
		&lt;pstyle="font-size:30px;"&gt;content of p tag&lt;/h1&gt;
	&lt;/head&gt;
	&lt;head&gt;
        	&lt;pstyle="font-size:80px;"&gt;content of p tag&lt;/h1&gt;
&lt;/head&gt;</code></pre>
</div class="blurb>

<iframe src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1G_DhfiS3g_mIs-lPvuATjqSIDCgRX5gSK9W4pY1SeA0&font=Default&lang=en&initial_zoom=2&start_at_slide=5&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>


<p>Snippet 4: <code>Adding Bullet Points</code></p>
<pre class="prettyprint pre-scrollable"><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
	&lt;head&gt;
		&lt;ulstyle="Tehran Conference:disc;"&gt;
			&lt;li&gt;FDR, Winston Churchill, Joseph Stalin&lt;/li&gt;
			&lt;li&gt;Meeting of Allied officials to discuss German dominance in Europe&lt;/li&gt;
			&lt;li&gt;Developed plans that became Operation Bodyguard and Operation Overlord&lt;/li&gt;
		&lt;/ul&gt;
	&lt;/head&gt;
</code></pre>
</div class="blurb>

<iframe src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1G_DhfiS3g_mIs-lPvuATjqSIDCgRX5gSK9W4pY1SeA0&font=Default&lang=en&initial_zoom=2&start_at_slide=3&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>

<p>Snippet 5: <code>Adding An Ordered List</code></p>
<pre class="prettyprint pre-scrollable"><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
	&lt;head&gt;
		&lt;olstyle=Normandy Landings:disc;"&gt;
			&lt;li&gt;Began on Tuesday the 6th of June 1944.&lt;/li&gt;
			&lt;li&gt;Most of the 5 beaches along the coast were secured by 12 June.&lt;/li&gt;
			&lt;li&gt;Took Allied forces until 21 July, 1944 to secure Caen, a major French port.&lt;/li&gt;
		&lt;/ul&gt;
	&lt;/head&gt;
</code></pre>
</div class="blurb>

<iframe src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1G_DhfiS3g_mIs-lPvuATjqSIDCgRX5gSK9W4pY1SeA0&font=Default&lang=en&initial_zoom=2&start_at_slide=5&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>

### My Timeline Example ###

<iframe src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1G_DhfiS3g_mIs-lPvuATjqSIDCgRX5gSK9W4pY1SeA0&font=Default&lang=en&initial_zoom=2&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>
