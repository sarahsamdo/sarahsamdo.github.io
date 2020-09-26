---
title: What is Metadata? Reflection
layout: post
categories:
- recap
---
My reflection on “What is Metadata?”

I have talked about data before in a previous reflection on this site, which can be [found here](https://sarahsamdo.github.io/recap/2020/09/04/reflective-post.html). This time, however, we are not going to be looking at what data is in a wide view lens. For this week, we are specifically going to look at what metadata is. I have mentioned before that data is everywhere, and that same view applies to metadata as well. Metadata is still data, but since data itself is an extremely broad term, metadata gives a more specific meaning to what data we are referring to and observing. Metadata can be on a package purchased from Amazon such as when the item was made, where the item was made, and what company made the item. Metadata can be the facts about a book such as when a book was printed, how many pages a book has, and who printed the book. Plus, metadata can inform a great deal to a person about the choices a site’s creator made for the end result. In short, metadata gives data about the data, essentially communicating facts about the data that would be the main content.

For the sake of this assignment, metadata will be looked at in the context of the web. For this week’s reflection, I will be analyzing the HTML page source document of [this web page](https://www.healthline.com/nutrition/10-health-benefits-of-apples) which talks about the benefits of apples. 

When looking at metadata in HTML, many tags can be seen throughout the page source document. Those tags would not show up in the actual website page displayed, but the tags are metadata because those dogs communicate information about the data inside them. As such, I would know which pieces of text were intended to be titles, headings, and links. The first line shows the following: <code>&lt;!DOCTYPE html&gt;</code> <code>&lt;html lang=”en”&gt;</code>. Immediately, I know that the document is in HTML language and also in English. None of this information is shown on the actual web page, but the page source communicates that about the data. 

There are a number of <code>&lt;meta&gt;</code> tags seen in the beginning of the HTML document as well. For example, the line <code>&lt;meta name="article:author" content="Kerri-Ann Jennings, MS, RD"&gt;</code> tells us many things. “Meta name” is the metadata and article author is the data. “Content” is the metadata and the data is  “Kerri-Ann Jennings, MS, RD.” As previously mentioned, there is a great quantity of metadata at the beginning of the document which includes the <code>og:image</code> property. The metadata communicates that the data is an image, but also communicates that the site is using Open Graph. Additional Open Graph properties used for the page includes <code>og:type</code>, <code>og:site_name</code>, <code>og:title</code>,  <code>og:url</code>, and <code>og:description</code>.

It would appear that metadata is tedious, especially in HTML, because of the constant need to define every piece of data, but metadata helps immensely with tasks such as organization of the data for proper display on a website and communication to others about the site.



