
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
3. é preciso inicializar o componente com ```menuNoty()```