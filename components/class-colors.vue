<template functional>
  <p class="color-scheme-demo">
    <span class="icon class-pld"><span class="ticker"> </span></span>
    <span class="icon class-war"><span class="ticker"> </span></span>
    <span class="icon class-drk"><span class="ticker"> </span></span>
    <span class="icon class-gnb"><span class="ticker"> </span></span>
    <span class="icon class-mnk"><span class="ticker"> </span></span>
    <span class="icon class-drg"><span class="ticker"> </span></span>
    <span class="icon class-nin"><span class="ticker"> </span></span>
    <span class="icon class-sam"><span class="ticker"> </span></span>
    <span class="icon class-brd"><span class="ticker"> </span></span>
    <span class="icon class-mch"><span class="ticker"> </span></span>
    <span class="icon class-dnc"><span class="ticker"> </span></span>
    <span class="icon class-smn"><span class="ticker"> </span></span>
    <span class="icon class-blm"><span class="ticker"> </span></span>
    <span class="icon class-rdm"><span class="ticker"> </span></span>
    <span class="icon class-blu"><span class="ticker"> </span></span>
    <span class="icon class-whm"><span class="ticker"> </span></span>
    <span class="icon class-sch"><span class="ticker"> </span></span>
    <span class="icon class-ast"><span class="ticker"> </span></span>
  </p>
</template>

<style lang="sass">

$icon-size: 1.25rem

.color-scheme-demo.color-scheme-demo
  position: relative

  display: flex
  justify-content: center
  // max-width: $icon-size * 18
  margin: 0.5rem auto

  text-align: center
  line-height: $icon-size * 1

  .icon
    position: relative

    flex-grow: 1
    height: 100%

    text-indent: 0

  .ticker
    position: absolute
    bottom: 0
    left: 0

    display: inline-block
    width: 100%
    height: 20%

    z-index: -1

// icon displayed over ticker background
.root.singleline, .root.hide-name
  .color-scheme-demo
    line-height: $icon-size * 1.75
    .ticker
      height: 100%

.c-settings-group-content .color-scheme-demo
  margin-left: -1rem

</style>
