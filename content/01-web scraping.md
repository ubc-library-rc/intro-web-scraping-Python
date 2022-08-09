---
 layout: default
 title: Web scraping?
 parent: Outline
 nav_order: 1
---
# What is web scraping?

<!-- <div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
<iframe src="../slides/what-is-scraping.html" title="What is web scraping?" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
  <p>Your browser does not support iframes.</p>
</iframe>
</div> -->

<em><a href="../slides/what-is-scraping.html" target="_blank">View slides</a> for this section</em>

Web scraping is a technique for collecting and parsing from websites. This can be done manually
but it is usually faster, more efficient and less error-prone to **automate** the task.

Web scraping allows you to acquire non-tabular or poorly structured data from websites and convert it
into a usable structured format such as a .csv file or spreadsheet. In many cases scraping can save time by automating repetitive copy/paste retrieval processes.

![The promise of automation](media/the_general_problem.png)

Source: [https://xkcd.com/974/](https://xkcd.com/974/)

Specialized scraping tools can automate web data retrieval by defining what sites to visit, what information to look for, and whether data extraction should stop at the end of a page or continue to hyperlinked pages. Scraping processes can also be scheduled to run at regular intervals to capture changes in the data over time.

Online stores will often scour the publicly available pages of their competitors,
scrape item prices, and then use this information to adjust their own prices. Another common
practice is "contact scraping" in which email
addresses or phone numbers are collected for marketing purposes.

Web scraping is also increasingly used by scholars to create data sets for
text mining projects, such as collections of journal articles or digitised texts.


## Is scraping the best option?

Scraping can automate repetitive data retrieval tasks but depending on the site there may be simpler ways to accomplish this. Choose the easiest tool for the job:

- Check whether or not you can easily copy and paste data from a site into Excel or Google Sheets. This might be quicker than scraping.
- Check whether the site provides an export feature with the data you need (e.g. for contact lists or search results).
- Check if the site or service provides an API to extract structured data. Depending on your comfort level with APIs this could be more efficient.


## Ethics and considerations

The ethics of web scraping are extremely important, by learning about these easy and powerful tools, you also have a responsibility to use them appropriately and legally. 
Just because something is online does not mean it is free to scrape. Sites may wish to control how the information they provide is accessed and used. A few questions to consider when deciding whether web scraping is appropriate:

- *Am I allowed to take this data?* Check the website for *terms of use* that affect web scraping.
- *Are there restrictions on what I can do with this data?* Making a local copy of publicly available data is usually OK, but there may be limits on use and redistribution of the content. Look for any *copyright* statements on the website.
- *Am I overloading the website's servers?* Scraping practice should respect the website's access rules, often encoded in *robots.txt* files.

There are grey areas as scraping involves interacting with a website in a way that the site owner might not have intended. When in doubt get in touch with a librarian or contact UBC's [Copyright Office](https://copyright.ubc.ca/support/contact-us/).


## Understanding website structure

<em><a href="../slides/website-structure.html" target="_blank">View slides</a> for this section</em>

Website content is usually represented using HTML, or **H**yper**t**ext **M**arkup **L**anguage. Web servers make HTML content available to browsers using a data transfer protocol called HTTP (**H**yper**t**ext **T**ransfer **P**rotocol). Two of the most common HTTP request methods are *get* (to request data from a server) and *post* (to send data to a server).

Web scraping tools use a website's HTML structure to navigate the page and identify the content to scrape. Effective use of web scraping tools requires a basic understanding of how web pages are structured. Sites whose underlying structure is well organized and descriptive are usually easier to scrape.

<a href="https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics" target="_blank">Anatomy of an HTML element.</a>
