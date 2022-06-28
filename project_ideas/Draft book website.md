---
created: 2022-05-27T19:30:26-04:00
modified: 2022-05-27T19:32:33-04:00
---

# Draft book website

Create a digital ocean instance with 3 parts:

1 - shiny app that takes a text file, and spits out a preview of the html, so that submitters can see what it will look like.

2 - shiny app that takes a file, checks formatting, and then commits it to the repo.

3 - takes the file and renders it and adds it to the site.

Things to consider:

* How to make it so authors can submit stand alone stories, as well as do serials?

* How to enable comments. My primary thought is to use utterances, but that
requires a GH account for both author and commenter. Could work if each page associated could use a repo that was for the author. Hmmm.
But it might work, I'm not sure.
Maybe with email turned on, we could forward comments to the author so they know if they have a comment?

* Using the same markdown format as LeanPub, so that works can go straight from the site to LeanPub and a digital book form.

* ability to export the full set of markdown files, and their part of the website and send it all to them.

* The writer shouldn't need a lot of knowledge about file paths, etc.

* Metadata should tell us everything we need. User login should give us the user subdirectory, then have metadata that tells us everything we need to know, like which one is previous to the submitted
