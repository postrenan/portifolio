<template>
    <section class="section" id="about">
        <div class="line"></div>
        <div class="icons">
            <p><i class="fa-solid fa-desktop"></i> Desenvolvimento Web</p>
            <p><i class="fa-solid fa-mobile-screen-button"></i> Desenvolvimento Mobile</p>
            <p><i class="fa-solid fa-house-laptop"></i> Hospedagem de aplicações</p>
        </div>
        <div class="history">
            <h3 class="title">Sobre mim</h3>
            <p class="text">
                Comecei a minha jornada no desenvolvimento após sair do exército e entrar na faculdade no ano de 2020, de lá para cá estudei linguagens de baixo e alto nível, além de metodologias e design. Dentro da área de desenvolvimento, sempre tive mais facilidade com linguagens web e desenvolvimento de UI. O resultado do estudo se transformou em:
            </p>
            <div class="metrics">
                <div class="metric">
                    <p class="value">25<span> +</span></p>
                    <p>Projetos feitos</p>
                </div>
                <div class="metric">
                    <p class="value">452<span> h</span></p>
                    <p>Horas desenvolvendo</p>
                </div>
                <div class="metric">
                    <p class="value">3<span> +</span></p>
                    <p>Anos de experiência</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.section {
    color: var(--primary-text);
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin: 100px 75px 100px 75px;
    gap: 50px;
    padding: 0 20px;
}

.line{
    background-color: var(--third-text);
    width: 4px;
}

.icons, .history {
    max-width: 50%;
}

.icons {
    display: flex;
    justify-content: space-around;
    flex-direction: column;  
    font-size: 25px;
    gap: 15px;
}

i{
    font-size: 40px;
}

.history {
    max-width: 60%;
}

.title {
    font-size: 35px;
    margin-bottom: 45px;
}

.text {
    font-size: 20px;
    overflow-wrap: break-word;
    margin-bottom: 40px;
}

.metrics {
    display: flex;
    justify-content: space-between;
    gap: 30px;
    font-size: 20px;
}

.metric {
    text-align: center;
}

.value {
    font-size: 35px;
    font-weight: bold;
}

span {
    color: var(--primary-btn);
    font-weight: bold;
}

/* Responsive Design */
@media (max-width: 1024px) {
    .section {
        flex-direction: column;
        align-items: center;
    }

    .icons, .history {
        max-width: 100%;
        text-align: center;
    }

    .title {
        font-size: 30px;
    }

    .text {
        font-size: 18px;
        margin: 15px 0;
    }

    .metrics {
        flex-direction: column;
        align-items: center;
        gap: 20px;
    }

    .metric {
        font-size: 18px;
    }

    .value {
        font-size: 30px;
    }
}

@media (max-width: 768px) {
    .section {
        margin: 50px 15px;
        gap: 30px;
    }

    .icons {
        font-size: 22px;
    }

    .text {
        font-size: 16px;
        margin: 15px 0;
    }

    .metrics {
        font-size: 16px;
        gap: 20px;
    }

    .value {
        font-size: 28px;
    }

    span {
        font-size: 18px;
    }
}

@media (max-width: 480px) {
    .section {
        margin: 40px 10px;
        gap: 20px;
    }

    .icons {
        font-size: 20px;
    }

    i{
    font-size: 20px;
    }

    .title {
        font-size: 28px;
    }

    .text {
        font-size: 15px;
        margin: 10px 0;
    }

    .metrics {
        flex-direction: column;
        gap: 15px;
        font-size: 14px;
    }

    .value {
        font-size: 25px;
    }

    span {
        font-size: 16px;
    }
}
</style>
