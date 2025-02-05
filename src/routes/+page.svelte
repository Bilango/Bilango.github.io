<div class="total">
    <div class="user">
        <span align="center">Titulo pag</span>
        <div class="sep">
            <input placeholder="Nome" id="name" type="text">
            <input placeholder="Senha" id="pass" type="text">
        </div>
        <button align="center">Confirmar</button>
    </div>
</div>

<style>
    
    div.user{
        background-color: rgb(92, 92, 92);
        height: 160px;
        border: black solid 2px;
        width: 250px;
        padding: 30px;
        border-radius: 15px;
        justify-content: center;
    }

    input{
        font-size: 40px;
        background-color: rgb(50, 58, 65);
        border: rgb(28, 31, 49) 1px solid;
        border-radius: 15px;
    }
    input:hover{background-color: rgb(72, 88, 102);}
    

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