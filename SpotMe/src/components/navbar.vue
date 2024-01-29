<script setup>

</script>

<template>
    <header class="header" >
       <div class="nav-box">
            <ul class="nav-list">
                <li class="nav-option"><a href="index.html">home</a></li>
                <li><a href="index.hml"><img class="logo" src="../../public/logo.png" alt="Logotipo"></a></li>
                <li class="nav-option"><a href="">Entrar</a></li>
            </ul>
       </div>
    </header>
</template>

<style>
* {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 24px;
    color: black;
}

.header {
    background: rgb(252,252,252);
    background: linear-gradient(0deg, rgba(252,252,252,1) 0%, rgba(34,193,195,1) 100%); 
    height: 30%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.nav-box {
    width: 500px;
}

.logo {
    width: 200px;
    height: 200px;
}

.nav-list {
    display: flex;
    justify-content: space-between;
    padding: 0;
    align-items: center;
}

ul.nav-list li{
    list-style-type: none;
    display: inline-block;
}

ul li a {
    text-decoration: none;
}

.nav-option {
    border: 1px solid black;
    padding: 20px;
    border-radius: 20px;
}
</style>