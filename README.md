# tachiyomi-faq

Website with FAQ info for the 
[Tachiyomi Android app](https://github.com/inorichi/tachiyomi).


## Goals

This website is designed to provide a way to vend FAQ information about 
Tachiyomi via:

- The website itself, accessed normally via a browser
- The website itself, embedded within a WebView within the Android app
- A JSON interface capable of being consumed by various parts of the Android app
  to contextually display information

The type of information that will be vended via the website includes, but is not
limited to:

- Instructions on how to use app functionality (e.g. local manga)
- Instructions on how to report bugs
- Instructions on how to request features
- Issues with catalogue extensions

The website must be designed such that:

- It is capable of vending the information described above
- The information can be easily created or modified by the support team
- It is of low or no cost to the development team in terms of infrastructure


## Technical details

This is a standard [Jekyll](http://jekyllrb.com) static site, hosted on
[GitHub Pages](https://pages.github.com/).
