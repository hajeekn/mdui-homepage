<template>
  <nav>
    <h1 class="title"><bold>Hajeekn</bold></h1>
    <span class="subtitle">当你凝视深渊时,深渊也在凝视你</span>
  </nav>
  <router-view />
</template>

<style lang="stylus">
#app
  font-family Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  margin-top 60px
.title
  padding-top: 80px;
.title
  box-sizing border-box
  display -webkit-box
  display -webkit-flex
  display -ms-flexbox
  display flex
  -webkit-box-flex-wrap wrap
  -webkit-flex-wrap wrap
  -ms-flex-wrap wrap
  flex-wrap wrap
  width 100%
  margin 0
  -webkit-flex-direction row
  -ms-flex-direction row
  flex-direction row
  margin-top -24px
  -webkit-flex-basis 200%
  -ms-flex-preferred-size 200%
  flex-basis 200%
  -webkit-box-flex 0
  -webkit-flex-grow 0
  -ms-flex-positive 0
  flex-grow 0
  max-width 200%
  -webkit-box-pack center
  -ms-flex-pack center
  -webkit-justify-content center
  justify-content center
  -webkit-align-items center
  -webkit-box-align center
  -ms-flex-align center
  align-items center
  padding-top 24px
  margin: 0;
  font-family "Roboto","Helvetica","Arial",sans-serif
  font-weight 400
  font-size 1rem
  line-height 1.5
  letter-spacing 0.00938em
  font-size 80px
  font-weight 250
  color rgba(0, 0, 0, 0.7)

.subtitle
  margin 0
  font-family "Roboto","Helvetica","Arial",sans-serif
  font-weight 400
  font-size 0.75rem
  line-height 1.66
  letter-spacing 0.03333em
  color rgba(0, 0, 0, 0.55)
  width 100%
  margin-left auto
  box-sizing border-box
  margin-right auto
  display block
  padding-left 16px
  padding-right 16px
  padding-bottom 4rem
  margin-left auto
  margin-right auto
  width 100%
  text-align center
.all
  width 100%
  margin-left auto
  box-sizing border-box
  margin-right auto
  display block
  padding-left 16px
  padding-right 16px
  padding-top 4rem
  padding-bottom 4rem
  margin-left auto
  margin-right auto
  width 100%
  text-align center
  margin 0px
  font-family Roboto, Helvetica, Arial, sans-serif
  line-height 1.5
  letter-spacing 0.00938em
  text-align left
  font-size 20px
  font-weight 350
  color rgba(0, 0, 0, 0.55)
.sustext
  margin 0
  font-family "Roboto","Helvetica","Arial",sans-serif
  font-weight 400
  font-size 1rem
  line-height 1.5
  letter-spacing 0.00938em
  font-size 30px
  font-weight 350
  color rgba(0, 0, 0, 0.7)
.cards
    box-sizing border-box
    margin 0
    -webkit-flex-direction row
    -ms-flex-direction row
    flex-direction row
    -webkit-flex-basis 100%
    -ms-flex-preferred-size 100%
    flex-basis 100%
    -webkit-box-flex 0
    -webkit-flex-grow 0
    -ms-flex-positive 0
    flex-grow 0
    max-width 100%
    background-color #fff
    color rgba(0, 0, 0, 0.7)
    -webkit-transition box-shadow 300ms cubic-bezier(0.4, 0, 0.2, 1) 0ms
    transition box-shadow 300ms cubic-bezier(0.4, 0, 0.2, 1) 0ms
    border-radius 4px
    box-shadow none
    overflow hidden
    background-color transparent
    max-width 300px
    min-width 150px
    display -webkit-inline-box
    display -webkit-inline-flex
    display -ms-inline-flexbox
    display inline-flex
    -webkit-align-items center
    -webkit-box-align center
    -ms-flex-align center
    align-items center
    -webkit-box-pack center
    -ms-flex-pack center
    -webkit-justify-content center
    justify-content center
    position relative
    box-sizing border-box
    -webkit-tap-highlight-color transparent
    background-color transparent
    outline 0
    border 0
    margin 0
    border-radius 0
    padding 0
    cursor pointer
    -webkit-user-select none
    -moz-user-select none
    -ms-user-select none
    user-select none
    vertical-align middle
    -moz-appearance none
    -webkit-appearance none
    -webkit-text-decoration none
    text-decoration none
    color inherit
    display block
    text-align inherit
    width 100%
    padding-top 5px
    padding-bottom 5px
    padding-left 8px
    padding-right 8px
.all
    justify-content center
    align-items center
    margin-left auto !important
    margin-right auto !important
.mdui-panel-item
  margin 3rem !important
  justify-content center
  align-items center
  text-align center
</style>
