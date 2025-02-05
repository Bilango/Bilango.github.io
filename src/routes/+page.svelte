<div class="total">
    <div class="user">
        <span align="center">Titulo pag</span>
        <div class="sep">
            <input placeholder="Nome" id="name" type="text">
            <input placeholder="Senha" id="pass" type="text">
        </div>
        <button>Confirmar</button>
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
        width:min-content;
        background-color: rgb(29, 38, 46);
        border: rgb(28, 31, 49) 1px solid;
        border: none;
        border-radius: 15px;
    }
    input:hover{background-color: rgb(50, 58, 65)}

     button{
        background-color: darkblue;
        margin: 15px;
        width: 100px;
        height: 30px;
     }

     button:hover{background-color: rgb(0, 0, 185);}

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