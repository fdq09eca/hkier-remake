---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: landing-banner.jpg
widget1:
  title: "About us"
  url: "/about/"
  image: about-thumbnail.jpg
  text: Our background information and people.
widget2:
  title: "Our Research"
  url: "/research/"
  image: research-thumbnail.jpg
  text: Our Research themes, progress and results.
widget3:
  title: "News"
  url: "/blog/"
  image: latest-news-thumbnail.jpg
  text: Our latest plan and activities.
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
# callforaction:
#   url: https://tinyletter.com/feeling-responsive
#   text: Inform me about new updates and features ›
#   style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<!--
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div> -->

# {{site.title}}

<div class="row">
    <div class="medium-4 columns t30">
    <img src="{{ site.urlimg }}gallery-example-4.jpg" alt="">
    </div><!-- /.medium-4.columns -->

    <div class="medium-4 columns t30">
      <img src="{{ site.urlimg }}gallery-example-5.jpg" alt="">
    </div><!-- /.medium-4.columns -->

    <div class="medium-4 columns t30">
      <img src="{{ site.urlimg }}gallery-example-6.jpg" alt="">
    </div><!-- /.medium-4.columns -->

</div><!-- /.row -->

<div class="row">
    <div class="medium-8 columns t30">
    <img src="{{ site.urlimg }}gallery-example-7.jpg" alt="">
    </div><!-- /.medium-8.columns -->

    <div class="medium-4 columns t30">
      <img src="{{ site.urlimg }}gallery-example-3.jpg" alt="">
      <img class="t30" src="{{ site.urlimg }}gallery-example-8.jpg" alt="">
    </div><!-- /.medium-4.columns -->

</div><!-- /.row -->
