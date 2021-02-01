
<link rel="stylesheet" type="text/css" media="all" href="../../../Assets/css/style.css" />

# Propriedades

<span>As propriedades de widgets são algumas definições de comportamento dentro da tela de cada uma delas, uma lista delas seria:</span>

<div class="propriedade-box">

### showOnView


+ Recebe: true/false
+ Ação: Visualiza registro no Swipe
+ Exemplo:
    
    ```json
     "showOnView": true
     ```

<small>Keys: showOnView, swipe</small>

</div>

<div class="propriedade-box">

showOnList

+ Recebe: true/false
+ Ação: Lista no grid
+ Exemplo:
    
    ```json
     "showOnList": true
     ```
<small>Keys: showOnList, grid, lista</small>

</div>

<div class="propriedade-box">

showOnForm

+ Recebe: true/false
+ Ação: Edita/Inclui registro
+ Exemplo:
    
    ```json
     "showOnForm": true
     ```
<small>Keys: showOnForm, incuir, alterar, editar</small>

</div>

<div class="propriedade-box">

readOnly

+ Recebe: true/false
+ Ação: Se é somente visivel ou passível de edição
+ Exemplo:
    
    ```json
     "readOnly": true
     ```
<small>Keys: readOnly, editar, leitura, read</small>

</div>

<div class="propriedade-box">

isVisible

+ Recebe: true/false
+ Ação: Se o campo é visivel ou não
+ Exemplo:
    
    ```json
     "isVisible": true
     ```
<small>Keys: isVisible, visibilidade, campo</small>

</div>


<div class="propriedade-box">

template

+ Recebe: string da localidade de um template
+ Ação: Define o template da field/widget
+ Exemplo:
    
    ```json
     "template": "field/select-multiple.html"
     ```
<small>Keys: template</small>

</div>

<div class="propriedade-box">

validations

+ Recebe: Objeto com definições de validações
+ Ação: Diz quais validações devem ser feitas pelo campo
+ Tipos de validação:
    + Required
        + Recebe: true/false
+ Exemplo:
```json
    "validations": {
        "required": true
    },
```
<small>Keys: validação, validacao, required</small>

</div>

<div class="propriedade-box">

filterProperties

+ Recebe: Objeto com propriedades que serão exibidas só na parte de filtragem
+ Ação: Define propriedades específicas para aba de filtros, pode ser utilizado quaisquer outra propriedade
+ Exemplo:
```json
    "filterProperties": {
        "isVisible": false
    }
```
<small>Keys: filtro, propriedades</small>

</div>