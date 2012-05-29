## Contribute

If you would like http://your.name.hackingtheuniversity.net, please read on.

### In one sentence...

Hacking the University is a website of short interviews asking coders who work in universities about their craft.

### How can I contribute my profile?

The website is a git repository, [hosted on Github](https://github.com/josswinn/hacktheuni). Treat it like code. Fork it, add your contribution and then make a pull request to josswinn. 

Note that the pages are written in markdown and a formatted template is below. The file should be placed in the _posts directory and use the filename format: year-month-day-firstname.lastname.interview e.g. 2012-02-14-nick.jackson.interview

Hardware and software should reference a .yml file held either in /hardware/ or /software/ e.g. macbook-pro.yml

The format of the .yml files is as follows:

`---
title: "MacBook Pro"

url: "http://www.apple.com/macbookpro/"

description: "The popular Intel-based Mac laptop."`

The filename for a .yml file should be a single word or words joined by hyphens. e.g. macbook.yml or macbook-pro.yml

To link to the .yml files in your post, use this format: [Hardware Name][hardware-name] e.g. [Macbook Pro][macbook-pro]

#### Images

Your image should be added to three directories:

1. /portraits/500x335px
2. /thumbnails/500x100px
3. /icons/100x100px

Images should be named using the same slug as your profile e.g.
 
2012-02-14-nick.jackson.interview
nick.jackson.jpg (500x335)
nick.jackson.jpg (500x100)
nick.jackson.jpg (100x100).

#### Post template

Copy and paste the text below into your text editor to start with. Save the file as: year-month-day-firstname.lastname.interview e.g. 2012-02-14-nick.jackson.interview

Make sure that your text editor doesn't add .txt or .md onto the end. 

=====cut below=====

---
layout: post
title: "An interview with FIRSTNAME LASTNAME."
slug: "firstname.lastname"
person: "Firstname Lastname"
summary: "Job title, University name"
categories: ['country', 'city', 'language1', 'language2', 'foo', 'bar', 'foo', 'bar']
---
### Who are you, and what do you do?



### Who taught you how to do what you do?



### What tools do you use?



### Describe your dream working environment.


====cut above====