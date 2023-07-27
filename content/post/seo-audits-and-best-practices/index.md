---
author: "Yigit Kocak"
title: "SEO Audits and Best Practices (Part 1)"
date: "2018-06-25T16:00:00"
lastmod: "2019-10-05T19:00:00"
hero: /static/images/posts/seo-auditing.svg
description: "This is the first part of SEO audits and best practices. It is about the most common on-page optimization strategies."
tags: [
    "seo",
    "seo audits",
]
categories: [
    "seo",
    "seo audits",
]
series: ["Themes Guide"]
aliases: ["migrate-from-jekyl"]
image: ""
---

Think of something that you want to be number 1 at. Is it easy to get there? How many other people are racing to the top? Who are the moderators/judges to decide?

Most people know SEO as a digital marketing tactic to rank higher in search engine results (sadly in an easy way) but that's just the end result of many, many factors combined. Some see it as a cheap practice while others think that rankings can change with a lvl. 120 spell from an SEO wizard.

# SEO Audit

In my opinion, SEO aligns customer expectations by providing a great experience for both humans and bots. That's why it's a complex ecosystem. Humans change bot behavior and bots are trying to emulate humans. In the past, bots used to be dumb, like the gif down below and ruined the user experience for all of us. This isn't the case anymore and as SEOs, we should lead the way for a better-organized internet.

![dumb bots](https://media.giphy.com/media/EizPK3InQbrNK/giphy.gif)

## Tags

### Title tag

Titles are what users see first in search queries and title tags are what creates them. It should describe the content of your page and give a brief idea on what the user should expect when clicking on the search engine result.

***Avoid***

* Keyword stuffing
* Repeated titles

***Use***

* Alphanumerics [0-9a-zA-Z] only
* Unique titles for every page
* Descriptive and concise text
* Branding if appropriate

***Restrictions***

* 10 - 70 Chars. for Google
* 5 - 65 Chars. for Bing

### Description tag

Descriptions are supportive sections to your title where you can describe your page in further detail. This is important for users who gave attention to the title and want to know more before they click.

***Avoid***

* Keyword stuffing
* Repeated descriptions

***Use***

* Alphanumerics [0-9a-zA-Z] only
* Unique descriptions for every page
* Descriptive and concise text

***Restrictions***

* 50 - 300 Chars. for Google
* 25 - 150 Chars. for Bing

### Social tags

Each social media platform has different specifications to blend your page into their feeds. You don't need to optimize your tags perfectly for every platform, only the ones your audience is using should be sufficient. Use the validators down below to make sure your content fits in well.

***Common social validators***

* [Facebook validator](https://developers.facebook.com/tools/debug/)
* [Pinterest validator](https://developers.pinterest.com/rich_pins/validator/)
* [Google+ validator](https://search.google.com/structured-data/testing-tool)
* [Twitter validator](https://cards-dev.twitter.com/validator)

### Structured data

Structured data defines and classifies your content even further which makes it easier for search engines to understand. There are standards for each data format with certain requirements to make it work.

***Avoid***

* Using unrelated data formats

***Restrictions***

* Make sure minimum requirements are met before applying the desired data format with the [structured data testing tool](https://search.google.com/structured-data/testing-tool)

### Header tags

The header tags make it easy to read and navigate through certain parts of your content.

***Avoid***

* Having any duplicate content in headings.

***Use***

* One h1 at the top of the page
* Multiple h2 - h6’s for the rest of the content

### Deprecated HTML tags

The website you've built can contain tags that aren't recognized by modern browsers anymore. That's seen as a bad indicator for page authority so it's important that you don't use any. Check out this article about [deprecated HTML tags](https://www.codehelp.co.uk/html/deprecated.html) and do a `find and replace` to get rid of old markup.

## Text Content

### Content volume

Content volume means the HTML code to actual text ratio for a page. Think of it as using your page resources efficiently. If you have a very low amount of text why have you created your page in the first place? Search engines use this as an indicator to separate pages that are worthy to index.

### Keyword density

This is another factor to weed out keyword stuffing and spammy practices. Over-optimizing content with a single keyword is probably not a human-readable page. Search engines are clever at detecting unnatural repetitions. Use your keyword once or twice at max. in your page.

### Keyword relevancy

This brings us how relevant our keywords are at both the page level and domain level. As an example, this page and the domain is about digital marketing and related subjects. Writing about `tennis shoes` or trying to sell them here isn't related to the theme of this website.

### Keyword research

It's unlikely to create content without doing keyword research anymore. What you think you know about your audience might not actually be true. That's why using keywords that our users actually search for is important. Check out two of the keywords down below and guess which is searched more. Using one over the other can make you look like a person who doesn't know anything about SEO.

* SEO rating checker
* SEO rank checker

### Last modified date

The lastModified property returns the date and time the current document was last modified. This is important because the information you provide should be relevant to the time it is written on. Search engines give higher credit for those who maintain and update their content occasionally.

## Visual Content

### Favicon

Favicons improve a brand's visibility especially for users bookmarking your website.

### Alt attributes

Alt attributes are used to describe images to the search engine and the visually impaired. Also, it can help them to appear in image search results.

***Use***

* Descriptive text if the image contains information
* Explanatory text where the link goes if the image is inside an a element
* `alt=""` if the image is only for decoration

### Image optimization

* Prefer vector formats: vector images are resolution and scale independent, which makes them a perfect fit for the multi-device and high-resolution world.

* Serve scaled images: resize images on the server and ensure that the `display` size is as close as possible to the `natural` size of the image. Pay close attention to large images in particular, as they account for largest overhead when resized!

### Image compression

Minify and compress images before uploading them to your website or CDN to save bandwidth and accelerate your site's loading speed.

### Flash usage

Avoid using embedded objects such as Flash. It should only be used for specific enhancements. Although Flash content often looks nicer, it cannot be properly indexed by search engines.

### iFrame usage

Avoid using iFrames which can cause problems on your web page because search engines will not crawl or index the content within them. Use a NoFrames tag if you must use them.

## URLs

### URL structure

The structure of URLs is a reflection of how organized the content of our website is. Taking the time to define your layout by keeping in mind to provide a great user experience is important for both your developers and customers.

I prefer using a single domain and keep a very tidy folder structure.

For example:

`blog
----> content
    ----posts
        ----seo-audits-and-best-practices-part-1`

***Avoid***

* Multiple URLs with the same content
* Multiple redirect hops

### Friendly URLs

A URL should be easy to read and remember for users. Search engines need URLs to be clean for giving a better user experience. They are also useful when shared on social media as they describe the page's content.

***Avoid***

* Dynamic URLs
* Keyword stuffing
* More than 60 chars.

***Use***

* Lower-case alphanumerics and hyphens
* A consistent structure
* Readable, descriptive text

### Internal URLs

Navigation links, content links, and footer links that point to other sections of your website should be standard for each page. Getting lost in a page that has no navigation and forces you to either signup or exit is just an irritating method. If you're using a landing page for your marketing campaigns make sure you don't include them in your organic traffic flow.

### Broken URLs

Links that don't go anywhere and provides a bad user experience is a big turn-off.

***Rule of thumb***

`Broken URLs = 0`

## Speed

### Gzip compression

Gzip is a method of compressing files on the server for faster network transfers. It allows reducing the size of web pages and any other typical web files to about 50% to 80% its original size before its transfer. When user's request the web page, it is automatically unzipped for faster loading times.

### Browser caching

When you leverage browser caching, your webpage files will get stored in the browser cache. Your pages will load much faster for repeat visitors and so will other pages that share those same resources.

### HTML/CSS/JS compression

Your HTML files have many things that can be removed which makes the file size smaller.

HTML compressors usually remove the following:

* Comments
* Line breaks
* Tab spaces
* Converts double spaces to single spaces

### Inline CSS

Inline CSS is only specific to the HTML page it is embedded into. It has its advantages and disadvantages in using it speed-wise.

***Advantages***

* One round trip
* Faster load times

***Disadvantages***

* Unorganized style
* Hard to maintain
* Cannot be cached

## Mobile

### Responsiveness

A website needs to be user-friendly on mobile devices. On April 21, 2015, Google rolled out the mobile-friendly update for webmasters. It boosts mobile search rankings for pages that are legible and usable on mobile devices.

***Update notes from Google***

* Affects in all languages globally
* Applies to individual pages only
* Affects search rankings on mobile devices only

***Do***

* Test your website for responsiveness
* Make sure text is readable and adjustable
* Make sure buttons and tap targets are legible and have adequate tap sizings
* Make sure there's no horizontal scrolling

## Technical

### Robots.txt

A robots.txt file allows you to restrict the access of search engine bots or crawlers that scan the web and also your website so it can prevent them from accessing specific pages and folders. It also specifies where your XML sitemap file is located.

*Disallow: Tells robots not to crawl your page(s).*

***My code***

`   User-agent: *
    Disallow: /tags
    Disallow: /topics
    Sitemap: https://yigit-kocak.com/sitemap.xml`

### XML sitemap

A sitemap lists URLs that are available for crawling and include additional information like your site's latest updates, the frequency of changes and importance of the URLs. This allows search engines to crawl the site more intelligently.

We recommend that you generate an XML sitemap for your website and submit it to both Google Search Console and Bing Webmaster Tools. It is also good practice to specify your sitemap's location in your robots.txt file.

### Header response

Understanding the header response codes are important to see which pages are doing ok, redirected, or cannot be found. It speeds up the manual labor of checking every page and how they behave.

The most commonly returned HTTP response codes include the following:

* 200: The page at the URL requested was successfully processed by the web server.
* 301: The URL requested has been permanently reassigned to another URL, and the page at that URL will be requested.
* 302: The URL requested has been temporarily reassigned to another URL, and the page at that URL will be requested.
* 404: The page at the URL requested couldn't be found on the web server.
* 503: The web server is temporarily unavailable and cannot process the URL request.

### URL redirects

Redirecting requests from a non-preferred domain and HTTP is important because search engines consider all URL variations that your site supports different URLs which include HTTPS, HTTP, www, and non-www. Also, redirect duplicate URLs the same method shown below.

Do a 301 redirect from other variations of your site and canonicalize the preferred version.

### Indexed pages

If it has been a while and search engines still haven't listed many of the pages in your sitemap there may be a bigger issue with either the quality of your pages or the structure of your sitemap.

Pages that search engines will often not index include:

* 404 and server error pages
* Low-quality, duplicate, identical content on different pages
* Tag, category, author pages
* Pages with noindex or a canonical tag that is telling to ignore it
* Pages that are previously indexed under your other domains (www.example.com and not example.com)

### Noindex

Tells search engines not to include your page(s) in search results. Check if your webpage is using the robots meta tag or the X-Robots-Tag HTTP header to instruct search engines not to show your site in search results pages.

### Nofollow

Tells search engines not to follow the links on your page. Don't use nofollow on all outbound links though. Linking out isn't bad for link juice and it's important to point to related content throughout the web for a better knowledge graph.

### Disavow

Analyze the backlinks for your site that may be spam or have a negative impact on your business and decide to Disavow them. The criteria on disavowing backlinks should be measured by checking the relevancy, DA, and PA of the web page the link is coming from. If you want to take things further, you might also contact the webmaster's of the web page and ask for removal manually.

### C Class IPs

As dynamic class C IP addresses are shared across multiple nodes, there are dangers associated with them. Say your website has a dynamic C class IP address which is shared with other websites. If a website who's sharing your IP address gets blacklisted, your website might also get blacklisted. It's because search engines don't only blacklist a website by its domain name but by its IP address as well. Be careful of other websites who are using the same IP as yours or just pay more to get a dedicated IP address just for you.

## Security

### HTTPS

In some modern browsers after July 2018, the browsers will begin displaying a warning that websites accessed over HTTP are “not secure.” Being prepared and having a complete transition for this change is crucial to have a long-term success in the digital world.

Reminders

* Make sure your certificate is always up to date
* Check that you have obtained a certificate for all host names that your site serves. For example, if your certificate only covers www.example.com, a visitor who loads your site using just example.com will be blocked by a certificate name mismatch error
* Redirect all HTTP pages to a single HTTPS with or without the www
* Migrate all media to HTTPS and serve them securely

### Safe browsing

Any site containing malware or phishing activity is seen as a threat to the online community and is often penalized by search engines. Check your website against regularly updated malware and phishing databases regularly to provide a safe browsing environment for your users.

### Server signatures

Check if your website server signature is on. It's a good idea to turn off server signatures because it reveals such information as versions of servers can help malicious users work out exploits that might affect your site.

### Website technology

There are many web technologies websites use for many reasons. The more you use them, the more you'll be vulnerable to attacks. Minimize the technologies you use and keep it as simple as you can. For example, don't use three different software for popup, form, and email. Choose a service that provides a complete package.

### Email privacy

Some email clients perform operations when reading an email which gives away information about the reader, to the sender of the message. Use clients that aren't using these policies or enable you to opt out.

### SPF records

SPF (Sender Policy Framework) is an open, DNS-based email authentication system that gives domain owners control over which IP addresses are allowed to deliver email on their behalf. Receiving mail servers check the SPF records for incoming messages, and if the delivering server has an IP address listed in the SPF rule set, the message is marked as authenticated.