<template>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <navbar class="navbar" id="home">
        <h2 class="title">Renan Bick</h2>
        <div class="btns">
            <button class="btn"><a href='#home'>Home</a></button>
            <button class="btn"><a href='#projects'>Projetos</a></button>
            <button class="btn"><a href="#about">Sobre</a></button>
            <button class="btn"><a href='#contact'>Contato</a></button>
        </div>
    </navbar>
    <section class="presentation">
        <div class="texts">
            <h3 class="title_1">Olá<span class="attention">!</span></h3>
            <h3 class="title_2"><span class="attention">__________</span> Sou o Renan</h3>
            <h3 class="title_3">Desenvolvedor de Software</h3>
            <div>
                <button class="btn_1"><a class="a" href="#contact">Possui um ideia?</a></button>
                <a class="btn_2" href="https://drive.google.com/file/d/1hhPDq25KtqgScEWb3krwgsMBcThUYNFF/view?usp=sharing" target="_blank">Meu curriculo</a>
            </div>
        </div>
        <p>{{ repos }}</p>
    </section>
    <section class="langs">
            <p>HTML5</p>
            <p>CSS</p>
            <p>Javascript</p>
            <p>Node.js</p>
            <p>Vue.js</p>
            <p>Git</p>
            <p>GitHub</p>
            <p>Laravel</p>
            <p>Postgres</p>
    </section>
</template>

<script>

</script>

<style scoped>
.title, .title_1, .title_2, .title_3{
    color:var(--primary-text);
    font-size: 35px;
}

.btn{
    color:var(--primary-text);
    font-size: 20px;
}

.attention{
    color: var(--third-text)
}

.navbar{
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: 25px 150px 50px 150px;
}

a{
    text-decoration: none;
    color:inherit;
}

.a{
    background-color: var(--primary-btn);

}

.navbar .btn{
    border: none;
    margin: 10px;
    background-color: inherit;
}

.navbar .btn:hover{
    color: var(--third-text);
    cursor: pointer;

}

.presentation{
    display: flex;
    justify-content: space-between;
}

.texts{
    margin: 75px 0 0 0;
    width: 60vw;
}

.img{
    display: flex;
    max-height: 50vh;
    margin: 75px 15px 15px 35px ;
    width: 40vw;
}

.title_1, .title_3{
    margin: 15px 0 15px 150px;
}

.title_2{
    font-weight: 100;
}

.btn_1 , .btn_2{
    padding: 15px;
    color: var(--primary-text);
    border: solid 2px var(--primary-btn);
    font-size: 20px;
}

.btn_1{
    margin: 85px 15px 85px 150px;
}

.btn_1 , .btn_2:hover{
  background-color: var(--primary-btn);
  cursor: pointer;
}

.langs{
    display: flex;
    flex-direction: row;
    justify-content: center;
    background-color: var(--second-bg);
    padding: 25px 0 25px 0 ;
}

p{
    font-size: 35px;
    margin: 15px;
    background-color: var(--second-bg);
    color: var(--second-text);
}

@media (max-width: 768px) {
    .navbar {
        flex-direction: column;
        margin: 25px 20px;
    }

    .presentation {
        flex-direction: column;
        align-items: center;
    }

    .texts {
        width: 90vw;
        margin: 20px 0;
    }

    .img {
        width: 90vw;
        margin: 20px 0;
    }

    .title, .title_1, .title_2, .title_3 {
        font-size: 28px;
    }

    .btn {
        font-size: 18px;
    }

    .btn_1, .btn_2 {
        margin: 20px 10px;
        padding: 10px;
        font-size: 18px;
    }

    .langs {
        flex-direction: column;
        align-items: center;
    }

    p {
        font-size: 28px;
        margin: 10px;
    }
}
</style>