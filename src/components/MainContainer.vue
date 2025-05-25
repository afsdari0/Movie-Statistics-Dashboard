<template>
    <div class="bodyMainContainer">
        <div class="mainContainerStatistics">

        </div>
        <div class="mainContainerMovies">
            <div class="mainContainerCards">
                <CardDialog />
            </div>
        </div>
    </div>
</template>

<script>
    import CardDialog from './CardDialog.vue';
export default {
    name: "MainContainer",
    components: {
        CardDialog
    }
}
</script>

<style scoped>
.bodyMainContainer {
    min-height: 100vh;
    width: 100vw;
    max-width: 1300px;
    background: rebeccapurple;   
    display: flex; 
    align-items: center;
    flex-direction: column;
}

.mainContainerStatistics {
    height: 40vh;
    min-height: 200px;
    width: 100%;
    background: teal;
}

.mainContainerMovies{
    height: 60vh;
    min-height: 200px;
    width: 100%;
    background: thistle;
    display: flex;
    align-items: center;
    justify-content: center;
}

.mainContainerCards{
    height: 95%;
    width: 95%;
    background: firebrick;
}
</style>