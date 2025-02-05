<div class="total">
    <div class="user">
        <span align="center">Titulo pag</span>
        <div class="sep">
            <div class="input"><input placeholder="Nome" id="name" type="text"></div>
            <div class="input"><input placeholder="Senha" id="pass" type="text"></div>
        </div>
        <button align="center">Confirmar</button>
    </div>
</div>

<style>
    
    div.user{
        background-color: rgb(192, 192, 192);
        height: 160px;
        border: black solid 3px;
        width: 250px;
        padding: 30px;
        border-radius: 15px;
        justify-content: center;
    }

    div.input{
        background-color: rgb(50, 58, 65);
        border-radius: 15px;
        padding: 0px;
        margin: 5px;
        justify-content: center;
    }
    input{
        background-color: rgb(50, 58, 65);
        border: none;
    }
    div.total{
        font-family: sans-serif;
        padding: 0px;
        justify-content: center;
        align-items: center;
        display: flex;
        width: 100%;
        height: 1000px;
        overflow: hidden;
    }
    div.sep{
        margin: 10px 0px 10px 0px;
        padding: 0px;
        border-top: solid black 1px;
    }

    span{
        font-weight: 600;
        font-size: 40px;
        font-family: monospace;
    }

</style>