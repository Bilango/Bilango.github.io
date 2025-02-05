<head>
    <title>Página de verificação..</title>
</head>
<div class="caixa">
    <p>Comfirmação de entrada</p>
    <input type="text" placeholder="Nome" id="nome">
    <input type="text" placeholder="Senha" id="senha">
    <button><span id="t">Comfirmar</span></button>
</div>


<style>
    input{
        background-color: rgb(41, 51, 66);
        font-size: 20px;
        padding: 10px 5px 0px 5px;
        border-top-left-radius: 4px;
        border:none;
        display: grid;
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
        margin:10px
    }

    div.caixa{
        background-color: rgb(29, 29, 31);
        border-radius: 15px;      
        box-shadow: 3px 3px 5px;
        padding: 25px;
    }
    #t{
        font-size:30px;
        margin: 2px 3px 2px 3px;
        font-weight:800;
        font-family:sans-serif;
        color:white;
    }
</style>