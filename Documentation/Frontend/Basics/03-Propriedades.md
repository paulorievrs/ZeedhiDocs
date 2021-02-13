
# Propriedades

As propriedades de widgets são algumas definições de comportamento dentro da tela de cada uma delas, uma lista delas seria:

### showOnView


+ Recebe: true/false
+ Ação: Visualiza registro no Swipe
+ Exemplo:
    
    ```json
     "showOnView": true
     ```

<small>Keys: showOnView, swipe</small>


### showOnList

+ Recebe: true/false
+ Ação: Lista no grid
+ Exemplo:
    
    ```json
     "showOnList": true
     ```
<small>Keys: showOnList, grid, lista</small>


### showOnForm

+ Recebe: true/false
+ Ação: Edita/Inclui registro
+ Exemplo:
    
    ```json
     "showOnForm": true
     ```
<small>Keys: showOnForm, incuir, alterar, editar</small>


### readOnly

+ Recebe: true/false
+ Ação: Se é somente visivel ou passível de edição
+ Exemplo:
    
    ```json
     "readOnly": true
     ```
<small>Keys: readOnly, editar, leitura, read</small>


### isVisible

+ Recebe: true/false
+ Ação: Se o campo é visivel ou não
+ Exemplo:
    
    ```json
     "isVisible": true
     ```
<small>Keys: isVisible, visibilidade, campo</small>



### template

+ Recebe: string da localidade de um template
+ Ação: Define o template da field/widget
+ Exemplo:
    
    ```json
     "template": "field/select-multiple.html"
     ```
<small>Keys: template</small>


### validations

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
Você também pode:

```json
"validations": false
```

<small>Keys: validação, validacao, required</small>


### filterProperties

+ Recebe: Objeto com propriedades que serão exibidas só na parte de filtragem
+ Ação: Define propriedades específicas para aba de filtros, pode ser utilizado quaisquer outra propriedade
+ Exemplo:
```json
    "filterProperties": {
        "isVisible": false
    }
```
<small>Keys: filtro, propriedades</small>
