
<p align="center">

  <h3 align="center">menu notification javascript</h3>

  <p align="center">
    Simples e totalmente editavel
    <br>
  </p>
</p>
<br>

## Requisitos
- Necessario ter jquery carregado

## Quick start
1. importe a lib com a versão;
```
<link rel="stylesheet" type="text/css" href="css/noti-menuList_style.css">
<link rel="stylesheet" type="text/css" href="css/animate.css">
<script src="noty.menu.min.js"></script>
```
2. Html do componente
```

<div id="containerGeralNotify" draggable="true">
  <div id="containerIconeBalao">
    <div id="balaoNotifi" class="balaoNotifi">
    </div>
    <div id="noty-menuList_numeroMsg" >
    </div>
  </div>
  <div id="containerLista" style="display:none;">
  </div>
</div>

```
3. é preciso inicializar o plugin com ```menuNoty()``` que é necessario passar o json de opcoes utilize este para auxilio ```{
                        listMessages:
                        {
                          {"texto":"teste de mensagem","tipo":"error","lido":"S"}
                        },notify:{animateHideCss:"animated fadeOutLeft",
      animateShowCss:"animated fadeInLeft"}} ```
4. a variavel listMessages do json é onde vc inicializa todas as mensagens que quer carregar passe um array de objetos com estas variaveis preenchidas ```{"texto":"teste de mensagem","tipo":"error","lido":"S"}```

## Estilizando 

altere o estilo de todo o componente como desejar utilizando a folha de css com o nome  de ```noti-menuList_style``` por padrao as mensagens tem 5 status mas para criar os seus é so passar no tipo da mensagem e criar um estilo css onde quiser que o componente se encarrega de preencher o estilo e de realizar os eventos.

- classes padrao :
  ```
    .success
    .information
    .error
    .warning
    .alert
  ```
