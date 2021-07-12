<template>
    <div class="pokedex">
        <TopPanel />
        <!-- <LeftPanel class="pokedex--left" />
        <Divider />
        <RightPanel class="pokedex--right" /> -->
    </div>
</template>

<script>
    import TopPanel from './TopPanel/TopPanel.vue';
    /* import LeftPanel from '@/components/LeftPanel/LeftPanel.vue';
    import Divider from '@/components/Divider/Divider.vue';
    import RightPanel from '@/components/RightPanel/RightPanel.vue'; */
export default {
    name: 'Pokedex',
    components:{
        TopPanel,
        //LeftPanel,
        //Divider,
        //RightPanel,
    },
}
</script>

<style lang="scss" scoped>
    .pokedex{
        position: relative;
        display: flex;
        flex-direction: column;
        width: 100%;
        max-width: 960px;
        height: 100%;
    }
</style>