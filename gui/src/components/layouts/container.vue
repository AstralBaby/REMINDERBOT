
<template>
    <div id="container">
        <div id="front">
            <div class="insidefront" id=top></div>
            <div class="insidefront" id=middle></div>
            <div class="insidefront" id=bottom></div>
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style>
    #container{
        background-color: rgb(205, 205, 255);
        padding: 50px;
        width: 80%;
        display: flex;
    }
    #front{
        background-color: rgb(163, 160, 202);
        width: 100%;
        padding: 15px;
        border-radius: 15px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-items: center;
    }
    .insidefront{
        background-color: white;
        border-radius: 30px;
        width: 90%;
        height: 18%;
        margin: 30px;
    }
</style>