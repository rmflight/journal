---
created: 2022-03-22T18:08:27-04:00
modified: 2022-03-22T18:09:04-04:00
---

# Mapping word styles in Rmd

There is a need to map styles to the custom elements.

If you have custom styles from a corporate document, those actually correspond to other defined styles in the document.

Ideally, you would want to create a mapping of the corporate / journal styles to the normal Word styled elements, and then only use the corporate journal ones that you really want to via <div> or <span>.

I think you really could do this with a package that took a word document, unzipped it, and then went through the XML tree and changed the style names to the ones that should be used, and then rezipped it.

See the discussion [here](https://github.com/ropensci/ozunconf19/issues/18) for example.
