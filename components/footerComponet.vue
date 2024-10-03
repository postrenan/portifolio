<template>
      <head>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    </head>
    <div class="all">
        <section class="contact">
            <div class="left">
                <h2><span class="attention">___________</span> Contato</h2>
                <p class="text">Possui um projeto?<br>Vamos tirar ele do papel!</p>
                <Button class="btn">Enviar</Button>
            </div>
            <div class="right">
                <form>
                    <label for="name">Nome:</label>
                    <input type="text" id="name" name="name"><br><br>
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email"><br><br>
                    <input type="submit" value="Enviar">
                </form>
            </div>
        </section>
        <footer class="footer">
            <h2>Renan Bick</h2>
            <p>@{{time}}. All Rights Reserved</p>
            <div>
                <button ><i class="fa fa-github"></i></button>
                <button></button>
                <button></button>
            </div>
        </footer>
    </div>
   
</template>

<style scoped>
.all{
    display: flex;
    flex-direction: column;
    max-height: 100vh;
}

.attention{
    color: var(--third-text);
}

.contact{
    color: var(--primary-text);
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
}

.left{
    display: flex;
    flex-direction: column;
}

.text{
    color:var(--primary-text);
    font-size: 35px;
}

.btn{
    color:var(--primary-text);
    padding: 15px;
    color: var(--primary-text);
    border: solid 2px var(--primary-btn);
    background-color: var(--primary-btn);
    font-size: 20px;
}

.text, .btn{
    margin: 10px 0 0 35px;
    
}

.footer{
    color: var(--primary-text);
    display: flex;
    align-items: center;
    flex-direction: column;
    color:var(--primary-text);
    font-size: 35px;
}
</style>

<script setup>

var time = 2024;



</script>