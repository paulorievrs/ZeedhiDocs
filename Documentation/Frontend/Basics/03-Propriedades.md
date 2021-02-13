
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


### dataSource

+ Recebe: Objeto com propriedades específicas para o dataSource
+ Ação: Define de onde virá o dataSource ou se ele será fixo
+ Em name: path para o dataSource ou seu nome se ele for fixo
+ lazyLoad: Em true, ele carregará somente quando clicar na field, em false assim que entrar na widget
+ rest: em true vai ser buscado do banco de dados, em false irá ser um dataSource fixo.
+ data: passe um array com os dados caso o dataSource seja fixo
+ Exemplo:
```json
 "dataSource": {
    "name": "cadSup#/fornecedor_visualizacao",
    "lazyLoad": false,
    "rest": true
 },
```

### label

+ Recebe: string
+ Ação: define o nome que mostrará ao usuário no campo.
+ Exemplo:
```json
 "label": "nome do campo para user",
```

### name

+ Recebe: string
+ Ação: define o nome do campo que poderá ser adquirido no backend se enviar como row e também será esse o nome da currentRow
+ Exemplo:
```json
 "name": "nome do campo",
```

### maxlength

+ Recebe: integer
+ Ação: define o tamanho de caracteres que um campo poder ter
+ Exemplo:
```json
 "maxlength": 20,
```