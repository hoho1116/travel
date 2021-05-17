<template>
    <div>
        <city-header/>
        <city-search/>
        <city-list/>
    </div>
    
    
</template>

<script>
import CityHeader from '../city/components/Header'
import CitySearch from './components/Search'
import CityList from './components/list'


export default {
    name:'City',
    components: { 
        CityHeader,
        CitySearch,
        CityList
     }
}
</script>

<style lang="stylus" scoped>

</style>
