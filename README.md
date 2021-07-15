# ePubFormattingCodeSample

I created this repository to provide a sample of how to put together and format an eBook in the .ePub format.

Here are some other helpful resources:

Helpful Guides:

http://www.unrulyguides.com/2015/02/ebook-formatting-tip-changing-font-size-css/

Conversion & trouble shooting: http://www.paulsalvette.com/2011/08/calibre-tutorial-ebook-formatting.html

Formatting Poetry: http://epubsecrets.com/formatting-poetry-in-epub-part-1.php

Helpful formatting: https://www.thebookdesigner.com/2017/01/elements-of-style-css-for-ebooks2/

EMs vs %: https://kyleschaeffer.com/css-font-size-em-vs-px-vs-pt-vs-percent

Counters + lists: https://www.joshwcomeau.com/css/styling-ordered-lists-with-css-counters/



# Documentation: #

ePUB 3.0: http://idpf.org/epub/30/spec/epub30-contentdocs.html

http://kb.daisy.org/publishing/docs/index.html

ePUB 3.2:
https://www.w3.org/publishing/epub3/

https://www.w3.org/publishing/epub/epub-contentdocs.html#sec-epub-type-attribute

https://www.w3.org/publishing/epub32/epub-contentdocs.html#sec-xhtml-svg-css

https://www.w3.org/publishing/epub32/epub-spec.html

http://kb.daisy.org/publishing/docs/index.html

* _Amazon Publishing Guide:_ https://kdp.amazon.com/en_US/help/topic/GU72M65VRFPH43L6
* https://kindlegen.s3.amazonaws.com/AmazonKindlePublishingGuidelines.pdf

* _Barnes and Noble:_ https://help.barnesandnoble.com/app/bnpress/detail/a_id/4062#epub
* _Kobo Guidelines:_ https://github.com/kobolabs/epub-spec
* _iBooks Asset Guide:_ https://help.apple.com/itc/booksassetguide/#/itc67f3d840e
* _Apple (Create an EPUB book in Pages):_ https://support.apple.com/en-us/HT202066




eBookBlog:

http://www.paulsalvette.com/2012/04/previous-post-page-breaks-similar-to.html

# Drop Caps: #
## My Approach ##

```
main > p:nth-child(1)::first-letter {
  font-size: 4.25em;
  font-family: "UnifrakturMaguntia", serif;
  float: left;
  line-height: 1;
  margin-top: -0.05;
  margin-bottom: -0.175em;
  margin-right: 0.025em;
  padding-top: 0;
  padding-bottom: 0;
  vertical-align: text-top;
}
```
## Other Helpful Resources: ##
* https://nachtimwald.com/2011/08/02/formatting-tip-big-first-letter/
* https://www.thebookdesigner.com/2017/04/fancy-free-some-fun-css-tricks-for-ebooks/
* https://product.voxmedia.com/2019/6/17/18524029/the-ballad-of-drop-caps-and-design-systems
* Line Height: https://css-tricks.com/how-to-tame-line-height-in-css/
* Inclusively Hidden: https://www.scottohara.me/blog/2017/04/14/inclusively-hidden.html
* Selectors/Drop Caps:https://www.mobileread.com/forums/showthread.php?t=212300




OPF: http://idpf.org/epub/20/spec/OPF_2.0.1_draft.htm#Section2.6

SVGL https://www.w3.org/TR/SVG/embedded.html#HTMLElements

SVG Fallback: http://davidensinger.com/2013/04/inline-svg-with-png-fallback/

- https://codepen.io/tigt/post/inline-svg-fallback-no-javascript-required

foot notes/linear reading: https://ebooks.stackexchange.com/questions/613/epub-opf-spine-element-how-to-exclude-an-html-file-from-linear-reading-order


 


# SVG Tricks:#

* https://css-tricks.com/a-complete-guide-to-svg-fallbacks/
* https://css-tricks.com/change-color-of-svg-on-hover/
* https://css-tricks.com/svg-properties-and-css/
* https://css-tricks.com/cascading-svg-fill-color/
* https://css-tricks.com/a-complete-guide-to-svg-fallbacks/
* https://css-tricks.com/using-svg/
* https://css-tricks.com/gotchas-on-getting-svg-into-production/
* https://css-tricks.com/accessible-svgs-high-contrast-mode/
* http://tympanus.net/codrops/2014/08/19/making-svgs-responsive-with-css/
* https://www.epubble.com/svg-wrappers-for-kindle/6/
* https://www.oreilly.com/library/view/html5-for-publishers/9781449320065/ch05.html
* https://github.com/oreillymedia/svg-essentials-examples
* Kobo SVG Guidelines: https://github.com/kobolabs/epub-spec#scalable-vector-graphics-svg

svg mask element: https://stackoverflow.com/questions/22252472/how-to-change-the-color-of-an-svg-element/53336754#53336754

## SVG Fallbacks ##

Background: https://css-tricks.com/stacking-order-of-multiple-backgrounds/

Masking: https://stackoverflow.com/questions/56885405/how-to-set-width-and-height-of-mask-image-in-css

# Other eBook Formats #
* _MOBI_: https://wiki.mobileread.com/wiki/MOBI#Guidelines
