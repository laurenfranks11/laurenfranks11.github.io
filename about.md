---
layout: page
title: About
permalink: /about/
---



This website was created as part of a course requirement for a Masters of Research degree at Macquarie University.

The aim of this website is to provide a platform to share research on data privacy in an accessible way. This same method can be used by anyone wanting to share their research on a free static webpage. To try it yourself, see my deployment instructions below.

My backup recovery plan includes making regular commits to Github so that I can access and restore my work from any computer.

Here is some example code written in Ruby:

{% highlight ruby %}

---
layout: post
title:  "Internet Browsers"
date:   2019-11-07 10:51:47 +0530
categories: jekyll update
img: google-browser.jpg
categories: [one, two]
---
What privacy extensions are best?

Here's where I provide a complete overview of internet browser privacy concerns and browser privacy extension remedies.

<h4>TLDR; Overview of Privacy Extensions</h4>

| Extension   |      Benefits/Functions      |  Cost |
|-------------|:----------------------------:|------:|
|uBlock Origin|List of functions             | free  |
| LastPass    |    List of functions         |subscription|
| Trocker     | List of functions            |  free |
{: .table .table-striped .table-hover}

{% endhighlight %}


<h2>How to build a website using GitHub Pages, Jekyll and Atom on Windows operating system</h2>

1.	Download [Git for Windows](https://gitforwindows.org)
2.	Create [Github account](https://github.com/)
3.	Download [Jekyll for Windows](https://jekyllrb.com/docs/installation/windows/), which requires you to install using [RubyInstaller](https://rubyinstaller.org/). Be sure to install version Ruby+Devkit 2.6.X (x64).
4.	Follow [these instructions](https://pages.github.com/) to create a GitHub Page using the shell/terminal
5.	Download [Atom](https://atom.io/)code editor. Note that once installed, Atom hides itself in ~/programdata/user/atom. Consider creating desktop shortcut.

<h3>Changing theme</h3>

6.	Download [theme](http://jekyllthemes.org/themes/webjeda-cards/) and unzip contents of theme into root directory of webpage on local server i.e. ~/users/Lauren/laurenfranks11.github.io

<h3>How to run the user acceptance test</h3>

1.	Create a free [BrowserStack](https://www.browserstack.com/) account.
2.  Follow instructions according to manual testing option.
