<template>
    <main>
        <div class="left-col">
            <h1>Connecting to Nature</h1>
            <h2>Have a love for all things that are outdoors?</h2>
            <div class="btn-container">
                <button class="btn" href="">Join Now</button>
                <button class="btn" href="">Read Blog</button>
            </div>
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

<style scoped>
main {
    margin-top: 60px;
    height: 60vh;
    display: grid;
    grid-template-columns: 1fr 1fr;
    font-family: 'Montserrat', sans-serif;
}

h1 {
    font-size: 64px;
    width: 400px;
    color: #40916C;
    font-weight: 700;
    background: -webkit-linear-gradient(#40916C, #58B727);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    font-family: 'Montserrat', sans-serif;
}

h2 {
    font-size: 30px;
    width: 400px;
    font-weight: 400;
}

.left-col {
    /* padding: 40px 0 40px 100px; */
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
}

.btn-container {
    width: 440px;
    display: flex;
    justify-content: space-between;
    /* margin-top: 20px; */
}

.right-col {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.right-col img {
    /* margin-top: 50px; */
    height: 28rem;
}

.btn {
    /* margin-right: 2.5rem; */
    /* margin-top: 1rem; */
    background: linear-gradient(180deg, #58B727, #40916C);
    color: #fff;
    width: 200px;
    height: 70px;
    border: none;
    border-radius: 5px;
    font-size: 30px;
}
</style>