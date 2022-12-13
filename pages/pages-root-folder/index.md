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
  title: odunde_2019_crop.jpg
  caption: Photo from the 2019 Odunde Festival.
  caption_url: https://www.odundefestival.org/
widget1:
  title: "Featured Projects"
  url: '/projects/'
  image: family-archive-photo.png
  text: 'Some of our current and recent projects involve preserving the organizational memory of The MOVE Organization, mapping sites of  Black resistance in Philadelphia, documenting community experiences of West Philadelphia High School and the Odunde Festival, and supporting West Philadelphia residents in archiving their family histories through the digitization of photographs and documents.'
widget2:
  title: "About Re/Member Black Philly"
  url: '/about/'
  image: backlit_map.jpg
  text: 'Re/Member Black Philadelphia is a multimodal digital scholarship and community archiving project that investigates increasingly endangered contexts of Black social and cultural life and community-driven memory work against the backdrop of systematic displacement.'
widget3:
  title: "Get Involved"
  url: '/get-involved/contact/'
  image: groupphoto_team.png
  text: 'Sign up for updates, to volunteer, or collaborate, or share community preservation efforts we should know about.'
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