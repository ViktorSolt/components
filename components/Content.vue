<template lang="html">
  <div class="Content">
    <div class="title">
      <h1>Tinyone features</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent vitae eros eget tellus<br>
        tristique bibendum. Donec rutrum sed sem quis venenatis.</p>
    </div>
    <div class="main">
      <div class="image">
        <img src="./../assets/icon-font-1.png" alt="">
        <img src="./../assets/icon-font-4.png" alt="">
      </div>
       <div class="text">
         <h3>Fully Responsive</h3>
         <p>Lorem ipsum dolor sit amet,<br>
         consectetur adipiscing elit.<br>
         Praesent vitae eros eget tellus<br>
         tristique bibendum.</p>
         <h3>HTML3 & CSS3</h3>
         <p>Lorem ipsum dolor sit amet,<br>
         consectetur adipiscing elit.<br>
         Praesent vitae eros eget tellus<br>
         tristique bibendum.</p>
       </div>
      <div class="image">
        <img src="./../assets/icon-font-3.png" alt="">
        <img src="./../assets/icon-font-3-.png" alt="">
      </div>
       <div class="text">
         <h3>Fully Layered PSD</h3>
         <p>Lorem ipsum dolor sit amet,<br>
         consectetur adipiscing elit.<br>
         Praesent vitae eros eget tellus<br>
         tristique bibendum.</p>
         <h3>Email Template</h3>
         <p>Lorem ipsum dolor sit amet,<br>
         consectetur adipiscing elit.<br>
         Praesent vitae eros eget tellus<br>
         tristique bibendum.</p>
        </div>
       <div class="image">
         <img src="./../assets/icon-font-2.png" alt="">
         <img src="./../assets/icon-font-2-.png" alt="">
      </div>
       <div class="text">
           <h3>Font Awesome Icons</h3>
           <p>Lorem ipsum dolor sit amet,<br>
           consectetur adipiscing elit.<br>
           Praesent vitae eros eget tellus<br>
           tristique bibendum.</p>
           <h3>Free to download</h3>
           <p>Lorem ipsum dolor sit amet,<br>
           consectetur adipiscing elit.<br>
           Praesent vitae eros eget tellus<br>
           tristique bibendum.</p>
         </div>
      </div>
    </div>
</template>

<script>
export default {
}
</script>

<style lang="sass" scoped>
  @import './assets/variables'
  .Content
    font-family: PTSans
  .title
    text-align: center
  .title h1
    font-size: 32px
    font-weight: bold
    color: $black
    margin:
      top: 9%
      bottom: 1%
  .title p
    font-size: 20px
    margin-bottom: 6%
    color: #313841
    line-height: 1.4
  .main
    display: flex
    justify-content: space-around
    margin:
      left: 12%
      right: 13%
  .image img
    display: flex
    flex-direction: column
    margin:
       right: 6%
       bottom: 162px
  .text
    display: flex
    flex-direction: column
    flex-shrink: 0
  .text h3
    margin-bottom: 15px
    line-height: 1.09
    font-size: 22px
    color: $black
    font-weight: 500
  .text p
    margin-bottom: 33%
    font-size: 16px
    color: $warm-grey
</style>
