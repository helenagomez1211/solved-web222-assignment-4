Download Link: https://assignmentchef.com/product/solved-web222-assignment-4
<br>
Practise DOM/JavaScript coding, dynamically adding image and populating HTML table using DOM (rather than innerHTML property), and updating the text in HTML element using the innerHTML property.




<h1>Specifications</h1>

To begin, download <strong>assign4-template.zip</strong> file from <strong>My.Seneca/Blackboard </strong>and unpack the zip file. In this assignment, you’ll build up a front-end web app which queries data from a given array of Country objects, named <strong>countries,</strong> and show the results on a web page using HTML DOM API. The array of Country objects is provided in the <strong>js/a4-country-data.js</strong> file and all countries’ flag images are stored under the <strong>flages</strong> folder. And your tasks are to update JavaScript code in the <strong>myscript.js</strong> file according to the instructions below.

Open the <strong>assignment4.html</strong> file in a browser, a 2-level menu will show up on the page,




Your tasks are that when the menu items are clicked, appropriate country data should be populated into the HTML table as specified.




<strong>BASIC REQUIREMENTS </strong>

<ol>

 <li>You should not change the given files <strong>html</strong>, <strong>a4-country-data.js</strong> or image files under flags folder. The <strong>myscript.js</strong> and <strong>honesty.html</strong> are the two files that you are allowed to update. Note: you should create event handlers to the menu items (the <strong>assignment4.html</strong> document’s unorder list <strong>&lt;li id=”menu_??”&gt;</strong> items) using JavaScript code inside the <strong>myscript.js</strong> file. When one of these items is clicked, a corresponding function should be called to change the subtitle and populate the country table.</li>

 <li>You <strong>must not</strong> use the DOM/Node innerHTML property to populate HTML tables, including adding images. However, using innerHTML property to update the text of the “<strong>subtitle</strong>” (&lt;h4 id=”subtitle”&gt;List of Countries and Dependencies&lt;/h4&gt;) on the page is appropriate.</li>

 <li>When running you web app on a browser, no errors should occur on the browser web console.</li>

</ol>




<strong>DETAILED INSTRUCTIONS </strong>

<h2>The Country List item</h2>

When the <strong>Country List</strong> item is clicked, the web page <strong>assignment4.html</strong> will be (re)loaded into the browser. Complete the following tasks upon the page is loaded:

<ol>

 <li>Update the text of the “<strong>subtitle</strong>” (&lt;h4 id=”subtitle”&gt;List of Countries and Dependencies&lt;/h4&gt;) to <strong>“List of Countries and Dependencies”</strong> on the page.</li>

 <li>Populate the HTML table with the data including all countries. The results should be as the screenshot below. Click the screenshot to see the full-screen image.</li>

</ol>




<ol start="3">

 <li>Note: the flag images are provided under the <strong>flags</strong> The flag image of each country has the file name which is same as the code of the country, e.g. Canada’s <strong>ccTLD</strong> (<strong>country code</strong> / top-level domain) is “<strong>CA</strong>”, and Canada’s flag image is named “<strong>ca.png</strong>” under the flags folder.</li>

</ol>




<u>The<strong> By Population, “&gt; 100,000,000” </strong>item</u>

Complete the following tasks once the item is clicked:

<ol>

 <li>Update the text of the “<strong>subtitle</strong>” to<strong> “List of Countries and Dependencies – Population greater than 100 million”</strong> on the page.</li>

 <li>Populate the HTML table with the data including countries whose population is greater than 100 million. The results should be as the screenshot below. Click the screenshot to see the full-screen image.</li>

</ol>













<u>The<strong> By Population, “1 ~ 2 million” </strong>item</u>

Complete the following tasks once the item is clicked:

<ol>

 <li>Update the text of the “<strong>subtitle</strong>” <strong>to “List of Countries and Dependencies – Population between 1 and 2 million”</strong> on the page.</li>

 <li>Populate the HTML table with the data including countries whose population is between 1 and 2 million. The results should be as the screenshot below. Click the screenshot to see the full-screen image.</li>

</ol>







<u>The<strong> By Area &amp; Continent, “1 million km</strong></u><strong><sup>2</sup><u>, Americas” </u></strong><u>item</u>

Complete the following tasks once the item is clicked:

<ol>

 <li>Update the text of the “<strong>subtitle</strong>” to <strong>“List of Countries and Dependencies – Area greater than 1 million Km2, Americas”</strong> on the page.</li>

 <li>Populate the HTML table with the data including countries whose area is greater than 1 million km<sup>2</sup>, and the countries are in The results should be as the screenshot below. Click the screenshot to see the full-screen image.</li>

</ol>







<u>The<strong> By Area &amp; Continent, “All size, Asia” </strong>item</u>

Complete the following tasks once the item is clicked:

<ol>

 <li>Update the text of the “<strong>subtitle</strong>” to <strong>“List of Countries and Dependencies – All countries in Asia”</strong> on the page.</li>

 <li>Populate the HTML table with the data including all Asia countries<strong>.</strong> The results should be as the screenshot below. Click the screenshot to see the full-screen image.</li>

</ol>







<u>The<strong> Language, English </strong>item</u>

Same as the <strong>Country List</strong> item




<h2>The Language, ? item</h2>

Select and implement only one language from <strong>Arabic</strong>, <strong>Chinese</strong>, <strong>French</strong>, <strong>Hindi</strong>, <strong>Korean</strong>, <strong>Japanese</strong>, and <strong>Russian</strong>. Complete the following tasks once the item is clicked:

<ol>

 <li>Update the text of the “<strong>subtitle</strong>” to fit selected language on the page, e.g. <strong>“List of Countries and Dependencies – Country / Dep. Name in Chinese (</strong>中文<strong>)” </strong>if Chinese is selected.</li>

 <li>Populate the HTML table with the data including all countries, and show the</li>

</ol>

“Country/Dep. Name” in the selected language<strong>.</strong> The results, e.g. “中文 (Chinese)”

selected, should be as the screenshot below. Click the screenshot to see the fullscreen image.

.