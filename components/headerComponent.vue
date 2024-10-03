<template>
    <navbar class="navbar">
        <h2 class="title">Renan Bick</h2>
        <div class="btns">
            <button class="btn">Home </button>
            <button class="btn">Sobre</button>
            <button class="btn">Projetos</button>
            <button class="btn">Contato</button>
        </div>
    </navbar>
    <section class="presentation">
        <div class="texts">
            <h3 class="title_1">Olá<span class="attention">!</span></h3>
            <h3 class="title_2"><span class="attention">__________</span> Sou o Renan</h3>
            <h3 class="title_3">Desenvolvedor de Software</h3>
            <div>
                <button class="btn_1">Possui um ideia?</button>
                <button class="btn_2">Meu curriculo</button>
            </div>
        </div>
        <img class="img" src="/assets/css/img.jpg">
    </section>
    <section class="langs">
            <p >HTML5</p>
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

.navbar .btn{
    border: none;
    margin: 10px;
}

.navbar .btn:hover{
    color: var(--third-text)
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

</style>