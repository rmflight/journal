---
created: 2022-12-28T22:43:31-05:00
modified: 2022-12-30T23:44:56-05:00
---

# blog2newlsetter

Should use an _init.R file that does the gmailr and googlesheets4 dance,, and pulls down the subscribers, and sets some metadata for the newsletter

Should keep a cache of the subscribers, and tell the user that it is skipping doing another pull

Should keep a cache of what posts have been emailed and when, and asks the user if it wants to send the same one again.

Should have some decisioning around the source of the RSS: 

  Directory, goes looking for index.xml
  File, assumes it is the index.xml
  URL, uses the top level function of tidyRSS

bn_compose should keep the item data, or maybe even a hash of the email contents (check if it will stay the same) to compare against a record of sent things in its own cache.
