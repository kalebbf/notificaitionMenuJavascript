
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