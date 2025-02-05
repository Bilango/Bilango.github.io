<head>
    <title>Página de verificação..</title>
</head>
<div class="total">
    <div class="caixa">
        <div class="divs">
            <p id="t">Usuário</p>
        </div>
        <input type="nome" placeholder="Nome:" id="nome">
        <input type="senha" placeholder="Senha:" id="senha">
        <button>Comfirmar</button>
    </div>
</div>


<style>
    input{
        background-color: rgb(41, 51, 66);
        font-size: 20px;
        padding: 10px 5px 0px 5px;
        border-radius: 5px;
        border-bottom-left-radius: 0px;
        border:none;
        display: grid;
        color:white;
        margin-top:5px;
    }
    input:hover{
        color:white;
        background-color: rgb(63, 77, 97);
        border-bottom: rgb(216, 0, 0) solid 2px;
    }

    button{
        background-color: rgb(60, 139, 214);
        border: solid 2px rgb(91, 198, 212);
        border-radius: 15px;
        color:white;
        display: grid;
        padding: 3px;
        margin:10px;
        padding: 8px 8px 8px 8px;
    }
    

    div.caixa{
        background-color: rgb(29, 29, 31);
        border-radius: 15px;      
        box-shadow: 3px 3px 5px;
        padding: 25px;
        width: 320px;
    }

    #t{
        border-bottom: solid 1px darkgray;
        font-size:30px;
        font-weight:800;
        font-family:sans-serif;
        color:white;
        justify-content: center;
    }
    body{
        justify-content: center;
        align-content: center;
    }
</style>