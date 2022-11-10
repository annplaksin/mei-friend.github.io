---
layout: page
title: Quickstart
permalink: /quickstart/
---

# Quickstart guide

Here we walk you through a short interaction with the mei-friend editor. For more in-depth instruction, please see the [mei-friend documentation]({{ site.baseurl }}/docs/). Also consider consulting the handy [cheat sheet]({{ site.baseurl }}/cheatsheet). 

## What is MEI? 

mei-friend is an editor targeting the [Music Encoding Initiative's](https://music-encoding.org) (*MEI*) XML schema for music encodings, though it is able to open other formats as well. If you are new to MEI and/or to XML, consider working through the [beginner's tutorials](https://music-encoding.org/resources/tutorials.html) available on the [MEI website](https://music-encoding.org) before proceeding here.

## What do I need to start working with mei-friend?
{% include alert.html type="info" title='mei-friend is available at <a href="https://mei-friend.mdw.ac.at">https://mei-friend.mdw.ac.at</a>.' %}
mei-friend is a browser-based application - no further installation is necessary. Though we endevour to support all modern browsers, Firefox and Chrome-based browsers currently offer the best experience. While the editor will function when opened on a tablet, interaction with mei-friend is optimised for a mouse-and-keyboard set-up. 
{% include alert.html type="warning" title="mei-friend works best with Firefox or Chrome on a PC or Mac." %}

## Let's work through an example

Open <a href="https://mei-friend.mdw.ac.at" target="_blank">mei-friend</a> in another tab and have a look at the interface. It should look something like this:

{% include alert.html type="danger" title="TODO INSERT ANNOTATED SCREENSHOT" %}

### Open a music encoding
mei-friend is able to open files from three different locations:
* Locally on your machine, via `File->Open file` in the mei-friend menu, or via drag'n'drop
* From the Web, via `File->Open URL`
* From GitHub, through the GitHub (available via `Login`)

{% include alert.html type="info" title="Regardless of the location type, mei-friend runs locally on your machine - no data is submitted to our server." %}

For now, let's open a local file. For the purposes of this exercise, please download [this sample MEI file]({{ site.baseurl }}/assets/mei/example.mei). 

Click on `File->Open file` and navigate to the file's download location. Select it, and click "OK" to open it in mei-friend. Back in the editor, you should see the file status display area to the right of the mei-friend menu updated with the new filename. The file's MEI XML content should load in the text editor area, and the corresponding notation should appear in the rendered notation area. 

You may notice a validation error being displayed when the file loads -- we will learn how to fix this shortly. But first, let's learn about basic editing.

### Manipulating notation elements
* A few example edits / manipulations
* Notice update of file status display to indicate changes
{% include alert.html type="info" title="Your mei-friend session persists even if its tab is closed or your browser crashes or restarts, so you will not lose any changes." %}

### Inserting notation elements
* A few example inserts 

### Correcting validation errors
* How validation window works
{% include alert.html type="info" title="Auto-validation can be deactivated in mei-friend's editor settings." %}
* Recognize what message means (maybe a missing attribute?)
* Jump to MEI Guidelines to look up attributes for element
* Fix error


### Saving your work

Now that you've completed work on this encoding, you will want to save a local copy. To avoid overwriting the unedited version, you may wish to change the filename -- to do this, simply click on it in the file status display area and change it to `example-modified.mei` (or however you see fit). 

Use `File->Save MEI` to download a copy of your modified MEI to your hard drive. Notice that the file status display's change indicator is now reset, since there have been no changes (yet) since your last save.

Note that mei-friend is also able to commit changes directly to a GitHub repository - for more on this, see [Working with GitHub](docs/github).

## What next?

Congratulations, you've completed a first simple music encoding workflow with mei-friend! But there is a lot more to this editor, and a *whole lot* more to learn about music encoding, and the Music Encoding Initiative community! 
* public repertoire
* further reading
* Summarise MEI contacts (slack, mailing list, conference)




