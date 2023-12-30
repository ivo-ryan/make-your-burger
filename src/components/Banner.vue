<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
export default {
    name: 'Banner'
    
}
</script>

<style scoped>
    #main-banner{
        background-image: url('../../public/img/burger.jpg');
        background-position: 0 -250px;
        background-size: cover;
        background-repeat: no-repeat;
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
        transition: .5s ease-in;
    }

    #main-banner h1{
        color: #fff;
        background-color: #222;
        padding: 20px 40px;
        font-size: 60px;
        text-align: center;
    }

    
    @media (max-width: 768px) {
        #main-banner{
            height: 200px;
            background-position: 0 -160px;
        }

        #main-banner h1 {
            padding: 10px 15px;
            font-size: 30px;
        }
    }
</style>