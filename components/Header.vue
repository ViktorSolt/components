<template lang="html">
  <header>
    <div class="container">
   <div class="main">
     <div class="logo">
       <img src="./../assets/fingerprint@3x.png" alt="">
       <h1>tinyone</h1>
     </div>
    <h1>Inspire your inspiration</h1>
    <h3>Simple to use for your app, products<br>
    showcase and your inspiration</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br>
    Praesent vitae eros eget tellus tristique bibendum. Donec<br>
    rutrum sed sem quis venenatis. Proin viverra risus a eros<br>
    volutpat tempor. In quis arcu et eros porta lobortis sit </p>
    <div class="images">
      <img src="./../assets/icon-fa-apple.png" alt="">
      <img src="./../assets/icon-fa-android.png" alt="">
      <img src="./../assets/icon-fa-windows.png" alt="">
    </div>
   </div>
   <div class="notmain">
    <nuxt-link to="#">Features</nuxt-link>
    <nuxt-link to="#">Support</nuxt-link>
    <nuxt-link to="#">Blog</nuxt-link>
    <div class="phone">
    <img src="./../assets/fingerprint@y3x.png" alt="">
    <h3>tinyone</h3>
    </div>
   </div>
  </div>
   <div class="but">
     <button type="button" name="button"></button>
     <button type="button" name="button"></button>
     <button type="button" name="button"></button>
   </div>
 </header>
</template>

<script>
export default {
}
</script>

<style lang="sass" scoped>
  @import '../assets/variables'
  header
    background: $sunflower-yellow
    font-family: PTSans
    word-spacing: 0.0001em
  .container
    display: flex
  .logo
    display: flex
  .main
    width: $left_side_header_width
    padding-top: $logo_top
    flex-direction: column
    margin-left: $logo_left
  .main img
    margin-right: $logo_right
    height: 43px
    margin-bottom: $logo_bottom
  .main h1
    font-size: 32px
    flex-shrink: 0
    margin:
      top: $text_inspire_top
      bottom: $text_inspire_bottom
    font-weight: bold
    line-height: 0.67

  .main h3
    font-size: 20px
    color: $charcoal-grey
    line-height: 1.2
    font-weight: 500
    margin:
      top: $text_h3_top
      bottom: $text_h3_bottom
  .main p
    color: $greyish-brown
    line-height: 1.25
    font-size: 16px
    flex-shrink: 0
  .images
    margin-top: $images_top
  .images img
    margin-right: $images_margin_right
  .notmain
    width: $right_side_header_width
    padding-top: 4%
    margin-left: 7%
  .notmain a
    margin-right: 13%
    text-decoration: none
    font-size: 20px
    font-weight: bold
    color: #010101
  .notmain a:nth-child(3)
    margin-right: 0%
  .notmain h3
    color: $sunflower-yellow
    font-size: 30px
  .phone
    display: flex
    width: 62%
    background: $black
    border-top: 44px solid white
    border-right: 14px solid white
    border-left: 14px solid white
    border-bottom: 44px solid white
    border-radius: 18px
    justify-content: center
    margin:
       top: 14%
    padding:
       top: 32%
       bottom: 38%
  .phone img
    height: 43px
    margin-right: 4%
  .but
    display: flex
    justify-content: center
    margin:
       top: 3%
    padding-bottom: 3%
  .but button
    background: $white
    border: none
    padding: 7px
    border-radius: 10px
    margin: 2px

</style>
