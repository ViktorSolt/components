<template lang="html">
 <footer>
  <div class="Subcrible-header">
    <h2>Keep in touch with us</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vitae eros eget tellus<br>
      tristique bibendum. Donec rutrum sed sem quis venenatis.</p>
  </div>
  <div class="input-email">
    <input type="text" name="" value="" placeholder="Enter your email to update">
    <button type="button" name="button">SUBMIT</button>
  </div>
  <div class="images">
    <img alt="" src="./../assets/facebook-ico.png">
    <img alt="" src="./../assets/twitter-ico.png">
    <img alt="" src="./../assets/google-ico.png">
    <img alt="" src="./../assets/pinterest-ico.png">
  </div>
    <div class="Media-Blog-Forums">
      <div class="bottomBar">
        <address>
          <p>HALOVIETNAM LTD<br>
          66, Dang Van ngu, Dong Da<br>
          Hanoi, Vietnam</p>
          <p>contact@halovietnam.com</p>
          <p>+844 35149182</p>
        </address>
     </div>
      <div class="bottomBar">
        <nuxt-link to="#">Examples</nuxt-link>
        <nuxt-link to="#">Shop</nuxt-link>
        <nuxt-link to="#">License</nuxt-link>
      </div>
      <div class="bottomBar">
        <nuxt-link to="#">Contact</nuxt-link>
        <nuxt-link to="#">About</nuxt-link>
        <nuxt-link to="#">Privacy</nuxt-link>
        <nuxt-link to="#">Terms</nuxt-link>
      </div>
      <div class="bottomBar">
        <nuxt-link to="#">Download</nuxt-link>
        <nuxt-link to="#">Support</nuxt-link>
        <nuxt-link to="#">Documents</nuxt-link>
      </div>
      <div class="bottomBar">
        <nuxt-link to="#">Media</nuxt-link>
        <nuxt-link to="#">Blog</nuxt-link>
        <nuxt-link to="#">Forums</nuxt-link>
      </div>

   </div>
 </footer>
</template>

<script>
export default {
}
</script>

<style lang="sass" scoped>
  @import '../assets/variables'
  footer
    background: $black
    font-family: PTSans
  .Subcrible-header
    text-align: center
    padding-top: 7%
  .Subcrible-header h2
    color: #fcdb00
    font-size: 32px
    margin-bottom: 1%
  .Subcrible-header p
    font-size: 20px
    color: $warm-grey
  .input-email
    display: flex
    margin-top: 40px
    justify-content: center
    margin-bottom: 6%
  input
    height: 50px
    width: $input_width
    font-size: 16px
    border-radius: 5px
    color: #898989
    line-height: 1.25
    margin-right: 2%
    padding: 1%
  button
    background: $sunflower-yellow
    font-size: 16px
    font-weight: bold
    color: $black
    border: none
    border-radius: 5px
    height: 50px
    width: 9%
  .images
    display: flex
    justify-content: center
    margin-bottom: 10%
  .images img
    margin-right: 2%
  .Media-Blog-Forums
    display: flex
    justify-content: space-around
    color: $white
    padding:
       left: 13%
       right: 12%
       bottom: 10%
  .bottomBar
    display: flex
    flex-direction: column
  .bottomBar a
    text-decoration: none
    color: $white
    margin: 1%
  .bottomBar p
    margin: 1%
</style>
