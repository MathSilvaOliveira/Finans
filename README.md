# Finans - Finanças Pessoais

## Descrição
Bem-vindo ao Finans, a sua ferramenta online para simplificar e organizar sua vida financeira. Este projeto foi desenvolvido como parte do meu aprendizado no curso de desenvolvimento web, focando na prática de habilidades de responsividade.

## Tecnologias Utilizadas

+ HTML5
+ CSS3
+ Bootstrap 4.1.3
+ Font Awesome

## Responsividade
Para garantir que o site seja responsivo e ofereça uma experiência otimizada em dispositivos de diferentes tamanhos, usamos as seguintes práticas:
+ Meta Tags:

  No index.html, incluímos a meta tag viewport para garantir o ajuste correto da escala em dispositivos móveis.\
` <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">`

+ Grid System do Bootstrap:
Usamos o sistema de grid do Bootstrap para criar layouts responsivos. As classes .container, .row, e .col-md-* ajudam a ajustar o conteúdo conforme o tamanho da tela.
```
<div class="container">
    <div class="row">
         <div class="col-md-6"> ... </div>
         <div class="col-md-6"> ... </div>
    </div>
</div>
````

+ Classes de Visibilidade:
Utilizamos classes como d-none d-md-block para controlar a visibilidade de elementos em diferentes tamanhos de tela.
```
<div class="col-md-6 d-none d-md-block">
    <img src="img/capa-mulher.png">
</div>
````

+ Imagens Responsivas:
As imagens utilizam a classe img-fluid para se ajustarem ao tamanho do contêiner.\
`<img src="img/saiba.png" class="img-fluid">`

+ Botões e Formulários:
Os botões e formulários são ajustados para tamanhos de tela variados usando classes de utilidade do Bootstrap, como btn, btn-primary, input-group-lg, entre outras.
````
<div class="input-group input-group-lg">
    <input type="text" placeholder="Seu e-mail" class="form-control">
    <div class="input-group-append">
        <button type="button" class="btn btn-primary">Cadastrar-se</button>
    </div>
</div>
````
