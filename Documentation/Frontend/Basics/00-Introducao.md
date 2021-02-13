# Definições basicas

A parte de frontend do Zeedhi é basicamente criada por um JSON que engloba alguns componetes.

O objeto se inicia com as propriedades:


+ <strong>name:</strong> Essa propriedade define o nome o objeto, que utilizam-se como o mesmo nome que o arquivo

+ <strong>label:</strong> Essa propriedade define o nome da tela no header.
  
+ <strong>showMenu:</strong> Propriedade booleana que define se vai ou não mostrar o menu
  + True mostra
  + False não mostra

+ <strong>showHeader:</strong> Propriedade booleana que define se vai ou não mostrar o header
  + True mostra
  + False não mostra
  
+ <strong>showFooter:</strong> Propriedade booleana que define se vai ou não mostrar o footer
  + True mostra
  + False não mostra

+ <strong>template:</strong> Define o template padrão que geralmente utilizam ***"container/window.html"*** - ***"container/dashboard.html"*** - ***"container/tabbed.html"***

+ <strong>footer:</strong> Define o template padrão do rodapé que geralmente é ***"component/footer.html"***

+ <strong>Widgets</strong> Essa propriedade recebe um array que vai passar as widgets que resumindamente são componentes que vão compor a tela. Vamos ter uma parte sobre elas.


### Id's

Existe um ID para cada componente/widget, não somente na sua tela mas em tudo. Cada um tem um ID específico que é gerado. Não crie ID's manualmente e não altere ID's já existentes sem saber o que está fezendo.

<hr>

Vamos Agora criar uma tela simples que não irá ter nada, mas será um template em branco para iniciar o projeto.

```json
{ 
    "name": "docspessoal",
    "label": "Criando uma docs pessoal",
    "showMenu": true,
    "showHeader": true,
    "showFooter": true,
    "template": "container/window.html",
    "footer": "component/footer.html",
    "widgets": [],
}

```