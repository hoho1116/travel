<template>
    <div>
        <city-header/>
        <city-search/>
    </div>
    
    
</template>

<script>
import CityHeader from '../city/components/Header'
import CitySearch from './components/Search'
export default {
    name:'City',
    components: { 
        CityHeader,
        CitySearch
     }
}
</script>

<style lang="stylus" scoped>

</style>
