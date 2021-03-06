---
author: Everett Toews
comments: true
date: 2013-02-11 20:53:36+00:00
layout: post
slug: innovation-in-the-jclouds-community
title: Innovation in the jclouds Community
categories:
  - jclouds
---

Last week I had the pleasure of hosting the first [jclouds meetup](http://www.meetup.com/jclouds/events/99094612/) of 2013 at the Rackspace offices in San Francisco. The number one thing that struck me during the meetup was the amount of innovation going on and the commitment of the community. We had a great turn out and 4 presentations were given by members. Without further ado, here they are in the order they were presented.

<!--more-->

## The Rackspace Java SDK Powered by jclouds

What with hosting the meetup and all, I took the opportunity to let the community know about the Rackspace SDKs and how our Java SDK is powered by jclouds. No fork, no separate "distribution", just committing code, examples, and documentation to the upstream jclouds repos. I kept it short and sweet, followed by a brief demo of jclouds in action working with different OpenStack providers. It also gave me a chance to let everyone know that [developer.rackspace.com](http://developer.rackspace.com/) is now the destination for developers building solutions on the Rackspace Cloud. Here's my slide deck.

<div class="img-center"><iframe src="http://www.slideshare.net/slideshow/embed_code/16386136?rel=0" width="427" height="356" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px 1px 0; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="https://www.slideshare.net/phymata/jclouds-meetup" title="jclouds meetup" target="_blank">jclouds meetup</a> </strong> from <strong><a href="http://www.slideshare.net/phymata" target="_blank">Everett Toews</a></strong> </div></div>

## A jclouds High Level Overview

Next up was the founder of jclouds, Adrian Cole, to give everyone an overview and update on where jclouds is and where it's going. For a lot of the attendees this was their first introduction to jclouds. Here are Adrian's slides.

<div class="img-center"><iframe src="http://www.slideshare.net/slideshow/embed_code/16412164?rel=0" width="427" height="356" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px 1px 0; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="https://www.slideshare.net/phymata/jclouds-high-level-overview-by-adrian-cole" title="jclouds High Level Overview by Adrian Cole" target="_blank">jclouds High Level Overview by Adrian Cole</a> </strong> from <strong><a href="http://www.slideshare.net/phymata" target="_blank">Everett Toews</a></strong> </div></div>

This was a real privilege for me as I had yet to meet Adrian person. I've been working with him and the jclouds community for that past 6 months but really only knew people by their IRC handles. It was great to meet everyone in person and put a face to those IRC handles.

## Pallet and Hadoop

Antoni Batchelli then described how his startup had built Pallet on top of jclouds. Pallet is platform for agile and programmatic automation of infrastructure in the cloud, on server racks or directly on virtual machines. Pallet provides cloud provider and operating system independence, and allows for an unprecedented level of customization. Antoni's goal is to deliver people from the "Amazon tax" by allowing them them to run their Hadoop jobs on any provider supported by jclouds. To find out more about the solution check out [PalletOps.com](http://palletops.com/). Here are his slides.

<div class="img-center"><p  style=" margin: 12px auto 6px auto; font-family: Helvetica,Arial,Sans-serif; font-style: normal; font-variant: normal; font-weight: normal; font-size: 14px; line-height: normal; font-size-adjust: none; font-stretch: normal; -x-system-font: none; display: block;">   <a title="View Pallet Big Data - JClouds Meetup 2013 on Scribd" href="http://www.scribd.com/doc/124377819/Pallet-Big-Data-JClouds-Meetup-2013"  style="text-decoration: underline;" >Pallet Big Data - JClouds Meetup 2013</a> by <a title="View tbatchelli's profile on Scribd" href="http://www.scribd.com/tbatchelli"  style="text-decoration: underline;" >tbatchelli</a></p><iframe class="scribd_iframe_embed" src="//www.scribd.com/embeds/124377819/content?start_page=1&view_mode=slideshow&access_key=key-23plgufqer9tkyu3u4uy&show_recommendations=false" data-auto-height="false" data-aspect-ratio="1.2997118155619596" scrolling="no" id="doc_53165" width="427" height="356" frameborder="0"></iframe></div>

## jclouds-chef and Abiquo

Finally, Ignasi Barrera had travelled from Barcelona, Spain to tell us about how his company Abiquo was using jclouds-chef to bootstrap chef deployments in the cloud. jclouds-chef are components to use the Opscode Chef REST API. [Abiquo](http://www.abiquo.com/) is a purpose built Cloud Management solution that integrates, operates and optimises your existing legacy infrastructure, processes and services into a single, easy to use, unified platform. Put them together and it allows Abiquo users to easily provision and configure software when they need it. Here are Ignasi's slides.

<div class="img-center"><iframe src="http://www.slideshare.net/slideshow/embed_code/16283126?rel=0" width="427" height="356" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px 1px 0; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="https://www.slideshare.net/ignasibarrera/cooking-the-cloud" title="Cooking the cloud" target="_blank">Cooking the cloud</a> </strong> from <strong><a href="http://www.slideshare.net/ignasibarrera" target="_blank">Ignasi Barrera</a></strong> </div></div>

## Coda

I was thoroughly impressed with the innovation and passion demonstrated by the members of the jclouds community at the meetup. Many stuck around after the presentations were finished to chat about the possibilities that jclouds enables. I'm privileged to be part of such a strong open source community and I'm looking forward to the future of jclouds.

Thanks to everyone for taking the time to come out to the meetup and to those who presented. Cheers.
