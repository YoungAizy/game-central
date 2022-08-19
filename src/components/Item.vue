<template>
    <div>
        <img src="../assets/pong.png" alt="" />
        <h2 id="name">{{gameName}}</h2>
        <button>play</button>
    </div>
</template>

<script>
export default {
    name: 'Item',
    props: [
        'imgSrc',
        'gameName'
    ]
}
</script>

<style scoped>
div{
    width: 400px;
    display: flex;
    flex-direction: column;
    background: white;
    border-radius: 8px;
    padding: 8px;
}

img{
    width: 100%;
}

button{
    flex: 1;
    background-color: aquamarine;
    border: none;
    border-radius: 16px;
    color: white;
    font-size: larger;
}
</style>