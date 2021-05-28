<template>
    <div class="jbt">
        <h2>The Progressive JavaScript Framework</h2>
        <button class="start">Get Started</button>
        <button class="hub">github</button>
    </div>
</template>

<style scoped lang="css">
    .jbt {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        height: calc(100vh - 150px);
        padding: 50px;
        border-radius: 15px;
        background-image: url(https://wallpapercave.com/wp/wp7134546.jpg);
        background-size: cover;
        background-position: center;
        text-align: left;
    }
    .jbt button {
        margin: 20px 10px;
        padding: 10px 40px;
        border-radius: 30px;
        font-size: 15px;
        text-transform: uppercase;
        cursor: pointer;
    }

    .jbt .start {
        background-color: white;
        border: 1px solid #42b983;
        color: #42b983;
    }

    .jbt .hub {
        background-color: lightgray;
        border: 1px solid grey;
        color: grey;
    }
</style>