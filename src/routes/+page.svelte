<head>
    <title>Página de verificação..</title>
</head>
<div class="caixa">
    <p>Comfirmação de entrada</p>
    <input type="text" placeholder="Nome" id="nome">
    <input type="text" placeholder="Senha" id="senha">
    <button><p class="t">Comfirmar</p></button>
</div>


<style>
    input{
        background-color: rgb(41, 51, 66);
        font-size: 20px;
        padding: 10px 5px 0px 5px;
        border:none;
        border-top-left-radius: 4px;
        display: grid;
        margin-top:5px;
    }
    input:hover{
        color:white;
        background-color: rgb(63, 77, 97);
        border-bottom: rgb(216, 0, 0) solid 2px;
    }

    button{
        background-color: rgb(77, 169, 255);
        border: solid 2px rgb(176, 246, 255);
        border-radius: 15px;
        color:white;
        display: grid;
        padding: 1px 3px 1px 3px;
        margin:10px
    }

    div.caixa{
        background-color: rgb(53, 53, 56);
        border-radius: 15px;
        box-shadow: 3px 3px 5px;
        padding: 10px;
    }
    span.t{
        font-size:30px;
        margin: 2px 3px 2px 3px;
        font-weight:800;
        font-family:sans-serif;
        color:white;
    }
</style>