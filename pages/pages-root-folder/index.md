---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_banner.jpg
image:
    title: cropped-cropped-cropped-odunde30-27-1.jpg
    caption: Photo from the 2019 Odunde Festival.
    caption_url: https://www.odundefestival.org/
widget1:
  title: "Featured Stories"
  url: '/our_work/'
  image: family-archive-photo.png
  text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.'
widget2:
  title: "About Re/Member Black Philly"
  url: '/about/'
  image: backlit_map.jpg
  text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.'
widget3:
  title: "Get Involved"
  url: '/get_involved/'
  image: groupphoto_team.png
  text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.'
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