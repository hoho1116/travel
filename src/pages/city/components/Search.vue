<template>
    <div class="search">
        <input class="searchinput" type="text" placeholder="输入城市名或拼音">
    </div>
</template>

<script>

export default {
    name:"CitySearch"
}
</script>

<style lang="stylus" scoped>
    @import '~styles/varibles.styl';
        .search
          padding 0 .1rem
          height 0.72rem
          background $bgColor
          .searchinput
            box-sizing border-box
            height .62rem
            line-height .62rem
            padding 0 .1rem
            width 100%
            text-align center
            border-radius .06rem
            color #666
</style>
