<template>
    <div class="container">
        <div class="title">
            <h1>DISCOVER OUR ICED</h1>
            <h1>COFFEE CREATIONS</h1>
        </div>

        <div class="grid">
            <div class="grid01">
                <p class="forma"></p>
                <img src="../assets/cafe02.png" alt="">
                <div class="legend">
                    <h3>CLASSIC CHOCOLATE</h3>
                    <p>Experience the enveloping flavor of chocolate iced coffee, a perfect combination of intense coffee and the smooth touch of creamy chocolate.</p>
                </div>
            </div>

            <div class="grid01">
                <p class="forma"></p>
                <img src="../assets/cafe02.png" alt="">
                <div class="legend">
                    <h3>CLASSIC MINT</h3>
                    <p>Experience the enveloping flavor of chocolate iced coffee, a perfect combination of intense coffee and the smooth touch of creamy chocolate.</p>
                </div>
            </div>

            <div class="grid01">
                <p class="forma"></p>
                <img src="../assets/cafe02.png" alt="">
                <div class="legend">
                    <h3>CLASSIC AMOLD MILK</h3>
                    <p>Experience the enveloping flavor of chocolate iced coffee, a perfect combination of intense coffee and the smooth touch of creamy chocolate.</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default{
    name: 'SecondComp'
}
</script>

<style scoped>
.container{
    height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.title{
    text-align: center;
    padding-top: 3vh;
    font-family: var(--font-family);
    font-size: 1.5rem;
    color: var(--primary-color);
}

.grid{
    display: flex;
    flex-direction: row;
    padding: 3vw 0;
}

img{
    width: 35%;
}

.grid01{
    display: flex;
    flex-direction: column;
    align-items: center;
}

.legend{
    margin-top: 4%;
    text-align: center;
    width: 45%;
    color: #005e3b;
    font-family: Barlow-SemiBold, sans-serif;
}

.legend>h3{
    font-size: x-large;
    margin-bottom: 2vh;
}


.forma{
    z-index: -99;
    position: absolute;
    margin-top: 11.1%;
    width: 20vw;
    height: 20vh;
    background-color: #4bff87;
    border-radius: 0px 0px 200px 200px;
}
</style>