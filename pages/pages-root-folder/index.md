---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "header_banner_larger.jpg"
image:
  title: odunde_2019.jpg
  caption: Photo from the 2019 Odunde Festival.
  caption_url: https://www.odundefestival.org/
widget1:
  title: "Featured Projects"
  url: '/our_work/'
  image: family-archive-photo.png
  text: 'Some of our current projects involve preserving the organizational memory of The MOVE Organization, documenting community experiences of West Philadelphia High School and Odunde Festival, and supporting West Philadlephia residents in archiving their family histories through the digitization of photographs and documents.'
widget2:
  title: "About Re/Member Black Philly"
  url: '/about/'
  image: backlit_map.jpg
  text: 'Re/Member Black Philadelphia is a multimodal digital scholarship and community archiving project that investigates the increasingly endangered contexts of Black social and cultural life against the backdrop of this systematic displacement.'
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