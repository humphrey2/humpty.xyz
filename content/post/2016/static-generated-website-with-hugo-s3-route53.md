+++
banner = "post/2016/static-generated-website-with-hugo-s3-route53/hugo-website.jpg"
categories = ["programming"]
date = "2016-04-19T15:10:00+00:00"
description = ""
draft = false
images = []
tags = ["programming", "nerdy"]
title = "Static generated website with Hugo, S3, Route53"
[menu.]

+++
So, I've started a new website!  It's been a while since I've done something nerdy like this, but I thought that it
would be a good excuse to try out static website generation.

## Hugo Static generator

Most of my web site experience has been with Django, which is a dynamic, database driven backend for creating websites.
I've recently come across [Hugo](http://gohugo.io/) though.  It allows you to do something similar to wordpress, but all
the posts are stored in text files, rather than a database.

To publish a post, I just need to edit a file, compile, and upload the entire new site.  It's brilliant!

## Fast, Cheap, Hosting on Amazon S3

I'm hosting this site using [Amazon S3](https://aws.amazon.com/s3/) which provides very fast static file hosting for
a very good price.  I'm hosting it out of Sydney, Australia which will make it lightening fast for Australians, and a
little bit slower for the rest of the world.  However, if I do start getting traffic from overseas, I can always use
Amazon CloudFront to cache it all around the world.

## So, what am I going to write about?

This is a good question!  I'm planning on using this blog/website as a place to write up about my nerdy activities.
Hopefully, other nerds will find my projects helpful, and inspiring.  For example, I'm currently installing a Nexus 7
tablet into the dashboard of my car.  It's going to be awesome, and I'm planning on writing a post about that.

When it is finished, it should look something like this.

{{< gallery
    "/post/2016/static-generated-website-with-hugo-s3-route53/tablet-dashboard-1.min.jpg"
>}}

But I'm waiting for some slim-fitting cables for audio and power before it will fit together.  So, it currently looks
like this.

{{< gallery
    "/post/2016/static-generated-website-with-hugo-s3-route53/tablet-dashboard-2.min.jpg"
>}}

So, this is my first post.  I'm mostly just trying to get a post up, so that I can test my publishing scripts.