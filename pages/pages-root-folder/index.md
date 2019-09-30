---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Blog & Portfolio"
  url: 'http://williamholtam.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'Enter here for my blog, where I prattle about tech and Data Science techniques I find interesting. Topics of interest  include Data Science, timeseries, IoT and cloud infrastructure.'
widget2:
  title: "About Me"
  url: 'http://williamholtam.github.io/feeling-responsive/about/'
  image: widget-1-302x182.jpg
  text: 'Check out my credentials here: <em>William Holtam</em> is a Data Scientist / Developer, with a background in Operational Research and Physics. He has experience in both the public and private sectors.'
widget3:
  title: "Resources"
  url: 'http://williamholtam.github.io/feeling-responsive/hobbies/'
  image: widget-github-303x182.jpg
  text: 'I like to share useful resources I've found around the web here.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
