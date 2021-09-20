<template>
    <header>
        <div class="logo">
            <h1>Boolpress blog</h1>
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">Contatti</a></li>
                <li><a href="">Chi siamo</a></li>
            </ul>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style lang="scss" scoped>
header{
    height: 200px;
    padding: 20px;
    text-align: center;
    .logo{
        padding: 10px;
        background-color: yellow;
        border: 5px solid blue;
        border-radius: 15px;
        ul{
        list-style: none;
        li{
            display: inline-block;
            margin-right: 20px;
        }
    }
    }
}
</style>