<template>
    
    <div id="nav">
        <RouterLink to="/" id="logo-url">
            <img :src="logo" :alt="alt" id="logo">
        </RouterLink>
        <RouterLink to="/">Home</RouterLink> 
        <RouterLink to="/pedidos">Pedidos</RouterLink>
    </div>
    
</template>

<script>
export default {
    //recebendo o props do app.vue 
    name: "NavBar",
    props: ["logo", "alt"]
}
</script>

<style scoped>

#nav {
    background-color: #333;
    border-bottom: 4px solid #FFCE30;
    padding: 15px 50px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

#nav #logo-url {
    margin: auto;
    margin-left: 0;
}

#logo {
    width: 40px;
    height: 40px;
}

#nav a {
    color: #FFCE30;
    text-decoration: none;
    margin: 12px;
    transition: .5s;
}

#nav a:hover {
    color: #FFF;
}

</style>