---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_banner.jpg
widget1:
  title: "Featured Stories"
  url: '/our_work/'
  image: family-archive-photo.png
  text: ''
widget2:
  title: "Contact Us"
  url: '/get_involved/'
  image: groupphoto_team.png
  text: ''
# widget3:
 # title: "Download Theme"
  # url: 'https://github.com/Phlow/feeling-responsive'
  # image: widget-github-303x182.jpg
  # text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. The code is well-documented and explains you how it works.'
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
  url: '/contribute/'
  text: CONTRIBUTE
  style: alert
permalink: /index.html

callforaction:
  url: '/contact/'
  text: CONTACT US
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

