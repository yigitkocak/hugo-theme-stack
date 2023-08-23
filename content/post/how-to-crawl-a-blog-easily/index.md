---
author: "Yigit Kocak"
title: "How to Crawl a Blog Easily"
date: "2018-05-29T16:59:00"
lastmod: "2019-10-05T19:00:00"
description: "There is a huge amount of information out there and it's getting harder and harder to create unique and appealing content."
tags: [
    "web scraping",
    "scraping hub",
]
categories: [
    "web scraping",
    "scraping hub",
]
series: ["Themes Guide"]
aliases: ["how-to-crawl-a-blog"]
image: "how-to-crawl-a-blog.png"
---

There is a huge amount of information out there and it's getting harder and harder to create unique and appealing content. The common excuse is that there is no time, skills, or energy.

But let's focus on finding good performing blog posts from competitors, blogs you adore, or just to do a random analysis. This post is about using a web crawler without getting too much into technical details. Of all the tools out there, I've found Portia from the guys at Scrapinghub.com great because it is free, fast, and user-friendly.

## Determine blog

Choose a blog for crawling. I'd select a blog that is organized, categorized, and standardized. But I've chosen the [Scrapinghub Blog](https://blog.scrapinghub.com) due to easy access.

![how to crawl a blog task 1](https://res.cloudinary.com/yigit-kocak/image/upload/v1527683330/posts/how-to-scrape-a-blog-task-1_bwe2da.jpg)

## Sign up to scrapinghub

Go to scrapinghub.com and sign up if you haven't already.

![how to crawl a blog task 2](https://res.cloudinary.com/yigit-kocak/image/upload/v1527683329/posts/how-to-scrape-a-blog-task-2_tjywke.jpg)

## Choose crawler

Choose Portia to create your first project.

![how to crawl a blog task 3](https://res.cloudinary.com/yigit-kocak/image/upload/v1527683329/posts/how-to-scrape-a-blog-task-3_ysgufn.jpg)

Portia is quite straightforward. There are so many things that you can do. Play with it for a couple of minutes and you'll get used to it in no time. Here's an overview of the basic steps for using Portia in a basic level.

1. Enter website URL
2. Configure link crawling
3. Set sample page
4. Choose elements
5. Publish project
6. Run crawler
7. Analyze data

![how to crawl a blog task 4](https://res.cloudinary.com/yigit-kocak/image/upload/v1527683329/posts/how-to-scrape-a-blog-task-4_c8hxyt.jpg)

## Specify sections

Now, this is where things can get complicated. Don't just crawl the complete page because it might be hard for you to smoothen and analyze data later on. Select the sections of information you need by clicking at the sections you want. Let's go to our example and chose the title, date, author, no. of comments, description, and URL for each blog post.

![how to crawl a blog task 5](https://res.cloudinary.com/yigit-kocak/image/upload/v1527683329/posts/how-to-scrape-a-blog-task-5_qqiyuu.jpg)

## Collect data

Go back to your Scrapinghub Dashboard and click the green button RUN. Great! We've extracted the entire blog in less than a minute which has 107 blog posts* with 8 fields.

_*We've excluded the full content of each post because we just needed an overview. But we could've extracted the entire content if we wanted to._

I can't imagine the time that I could've wasted if I've manually copied and pasted that much information!

## Export data

We've finally come to the fun part. Let's export our data as CSV, import to Google Spreadsheets and start analyzing the content.

![how to crawl a blog task 6](https://res.cloudinary.com/yigit-kocak/image/upload/v1527683329/posts/how-to-scrape-a-blog-task-6_b2vsff.jpg)

## Analyze data

Raw data is useless without questions. Let's ask some to find out more about our data. Now, I only collected data that I was interested in. You may need to change your data collection methods to direct your analysis to your preferences.

**Which blog post had the highest comments?**

![how to crawl a blog task 7](https://res.cloudinary.com/yigit-kocak/image/upload/v1527683329/posts/how-to-scrape-a-blog-task-7_xdmwum.jpg)

**Who has created the most content?**

![how to crawl a blog task 8](https://res.cloudinary.com/yigit-kocak/image/upload/v1527683329/posts/how-to-scrape-a-blog-task-8_z8iqxz.jpg)

**What is the frequency of publishing posts at 2016?**

Blog posts were published every 8 days in 2016. The calculation is done by getting the date difference between 2 following blog posts and doing a simple average with all the date differences for 2016.

Now that we know how to extract data by using Portia we can collect data from anywhere* that we'd like.

_*A lot of websites block crawlers that aren't trusted or from unknown sources. So, Portia might not work on some._

## Is this legal

In my opinion, collecting publicly available data isn't an issue. We're not breaching any databases or collecting personal information nor we're using it for commercial purposes. However, this is a different topic where it needs to be covered in the future.

Happy crawling!