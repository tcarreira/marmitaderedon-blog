+++
title = "Podcasting for free (what is essential)"
author = "Tiago Carreira"
date = "2021-02-12T12:00:00.000+00:00"
description = "Podcasting for free (what is essential)"
thumbnail = "images/dog_phonograph_400.jpg"

featured = false
categorias = ["Tutorial"]
aliases = ["1-essenciais"]
+++


**>> What is a podcast? <<**

Technically, a podcast is just a list of audio files, listed on a [RSS feed](https://en.wikipedia.org/wiki/RSS).
But maybe this is too simplistic.

Let's state the most important things about podcasting, in 3 different categories: essential, recommended, optional.

{{% 
figure
src="../../../images/dog_phonograph_400.jpg" 
attr="<small>\"Dog Looking at and Listening to a Phonograph\" by Beverly & Pack is licensed under CC BY 2.0</small>"
attrlink="https://live.staticflickr.com/3546/3353936487_2599d7b8dc_b.jpg"
%}}

## Essential

- Content

  The most important thing in a podcast is the content - it is the podcast soul and it is what listeners get.

- Capturing

  This is one crucial point regarding the podcast quality.
  Unfortunately, there are no shortcuts on this one:
  in order to have quality, a good microphone is a must (but it's not the only thing!).
  Nevertheless, if your objective is **to experiment and to learn**, there are free options (that was made at [Marmita de Redon](https://marmita.pt)).

- Audio files: digital episodes

  This is how the content is sent to the listeners - and audio file, usually MP3 format
  This file must be hosted on a publicly accessible website.

- Hosting

  There are multiple options for hosting this files, some cheaper or more expensive, other free/_libre_ or proprietary, etc.
  We have some examples: 
  [archive.org](https://archive.org),
  [S3 from AWS](https://aws.amazon.com/s3/),
  [Dropbox](https://dropbox.com)/[Drive](https://drive.google.com)/[OneDrive](https://www.microsoft.com/microsoft-365/onedrive/online-cloud-storage),
  or even the podcast website.

- RSS Feed

  This is a critical part of the podcasting engine.
  The podcast directories (Apple Podcasts, Spotify, etc.) require an RSS feed in order to add a podcast to their lists.

  An RSS feed is nothing but an XML formatted file, read and analyzed by computers,
  with all information about the podcast (title, authors, thumbnail ...),
  including all episodes list (and their respective audio file location).

  From this feed, listeners are notified when a new episode is available (though podcatchers).


## Recommended

- Official website

  Although it is not mandatory, the website is probably the best place to find some information about the podcast,
  like the authors contact.
  
  An easy alternative to a conventional website, are the podcast platforms,
  which provide a "face" for the podcast, with the episodes list and their show notes.

- Social networks

  Nowadays the marketing is a key part of a podcast success.
  How will you search for the podcast you never heard about?

- Brand

  From the opening theme to colors and image, this is usually the first contact one has with the podcast.
  A consistent image which represents the brand (podcast) will show commitment and professionalism.
  
- Statistics

  Knowing how many times each episode was downloaded may have or have not any consequence,
  but there is always that desire to know how many people listen to our words.


## Optional

- Periodicity

  If episodes are released with a fixed periodicity, 
  listeners will feel the podcast as "healthier".

- Monetization

  This may even be one of the core objectives (though I do not recommend it).
  Getting money from podcasting is possible, if you have a relatively large audience.
  This is mostly achieved through ads,
  usually by negotiating with brands in order for them to be featured on the episodes.

- A plan

  What's next? 
  Should I keep this project for 3 monthly listeners?
  How many listeners should I have before taking podcast to a professional level?
  Should I hire services now, or should I wait for X followers?  
  Making this kind of plans from the beginning may become very useful when those questions arise.


# How to make it for free

Presenting a practical example is better than explaining everything.
This is how it was made with [Marmita de Redon](https://marmita.pt) podcast

|       What       | How                                                                                                                                                                                                                                                                                |
|:----------------:|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|     Content      | A group of 4 friends keeps thinking about what to talk next episode                                                                                                                                                                                                                |
|    Capturing     | In order to capture with minimum quality, we record every episode with our smartphones. I dare to say this is the only thing you cannot get professional for free                                                                                                                  |
|   Audio files    | Each episode is edited and rendered using open source [Audacity](https://www.audacityteam.org/) and rendered as a stereo MP3 at 192kbps                                                                                                                                            |
|     Hosting      | Every episode is uploaded to the [archive.org](https://archive.org)                                                                                                                                                                                                                |
|     RSS Feed     | Custom made source code, in order to fully support podcasting RSS feeds ([code on Github](https://github.com/marmita-de-redon/hugo-redon-podcast/blob/master/layouts/feed/rss.xml))                                                                                                |
| Official website | Website made using [Hugo - a static site framework](https://gohugo.io/) and hosted on [Github Pages](https://pages.github.com/) for free ([code on Github](https://github.com/marmita-de-redon/website))                                                                           |
| Social networks  | Free accounts at Instagram, Facebook, Twitter, Youtube, Github, Disqus                                                                                                                                                                                                             |
|      Brand       | Vector images edited with [Inkscape](https://inkscape.org/), using open source materials from [Flaticon](https://www.flaticon.com/) and open sourced at [Github](https://github.com/marmita-de-redon/brand). Colors are coherent among the website, thumbnails and social networks |
|    Statistics    | You can get [free basic statistics](https://create.blubrry.com/resources/podcast-media-download-statistics/basic-statistics/) provided by Blubrry                                                                                                                                  |
|   Periodicity    | Weekly, every friday morning                                                                                                                                                                                                                                                       |
|   Monetization   | No                                                                                                                                                                                                                                                                                 |
|      A Plan      | Personal satisfaction, hearing our customers and feel our gut &#128539;                                                                                                                                                                                                            |

Moreover, the [Marmita de Redon](https://marmita.pt) podcast
is completely open source, and its code is available (suggestions are welcome)
at [github.com/marmita-de-redon](https://github.com/marmita-de-redon)

--- 

This is the 1st article from the series [How to make a Podcast](../how-to-make-a-podcast)

1. [Podcasting for free (the essentials)](../1-essentials)
2. Recording and capturing
3. Sound editing
4. Brand: music, image and licencing
5. Website
6. Submission and publishing (iTunes, Spotify, etc...)
7. Social Network
8. Automation
