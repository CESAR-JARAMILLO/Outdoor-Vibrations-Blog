<template>
    <main>
        <div class="left-col">
            <h1>Connecting to Nature</h1>
            <h2>Have a love for all things that are outdoors?</h2>
            <button class="btn" href="">Join Now</button>
            <button class="btn" href="">Read Blog</button>
        </div>
        <div class="right-col">
            <img src="../assets/camping.png" alt="">
        </div>
    </main>
</template>

<script>
export default {
    name: 'Landing'
}
</script>

<style>
main {
    display: grid;
    grid-template-columns: 1fr 1fr;
}

h1 {
    font-size: 64px;
    width: 350px;
    color: #40916C;
    font-weight: 700;
    background: -webkit-linear-gradient(#40916C, #58B727);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

h2 {
    font-size: 36px;
    width: 400px;
}

.left-col {
    padding: 40px 0 40px 100px;
}

.right-col {
    text-align: center;
}

.right-col img {
    margin-top: 50px;
    height: 26rem;
}

.btn {
    margin-right: 2.5rem;
    margin-top: 1rem;
    background: linear-gradient(180deg, #58B727, #40916C);
    color: #fff;
    width: 200px;
    height: 70px;
    border: none;
    border-radius: 5px;
    font-size: 30px;
}
</style>