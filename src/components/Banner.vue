<template>
    <div id="main-banner">
        <h1>Make U Burguer</h1>
    </div>
</template>

<script>
export default {
    name: "Banner"
}
</script>

<style scoped>

#main-banner {
    background-image: url("/img/burger.jpg");
    background-position: 0 -250px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}

#main-banner h1 {
    color: #000;
    font-size: 60px;
    background-color: #FFCE30;
    padding: 20px 40px;
    border-top-right-radius: 30px;
}

</style>