<template>
    <div>
        <hr>
        <h1 class="main-text m-5">Perspectives on today's marriages</h1>
        <FlowerItem />
        <!-- <h5 class="written-by">written by</h5> -->
        <h2 class="writer m-5">CLETUS ELIAKIM MATOMA &copy;</h2>
        


    </div>
</template>

<script>
  import FlowerItem from './FlowerItem.vue';

  export default {
        name:'ForeText',
        components: {
            FlowerItem,
        }
    }
</script>

<style  scoped>
.main-text{
    font-family: Great Vibes;
    font-size: 80px;
}
.writer {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 20px;
}

</style>