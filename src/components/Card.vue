<template>
    <div class="container">
        <div class="card">
            <SearchBar></SearchBar>

        </div>
    </div>
    
</template>

<style scoped>
    .container{
        display: flex;
        justify-content: center;
    }

    .card{
        width: 200px;
        height: 200px;
        border-radius: 15px;
        margin-top: 100px;
        background-color: blueviolet;
    }

    .container{
        align-items: center ;
        background-color: black;
        width: 500px;
        height: 500px;
    }

</style>

<script>
// import SearchBar from './components/SearchBar.vue';

    export default {
        setup() {
            return{

            }
        }
    }
</script>