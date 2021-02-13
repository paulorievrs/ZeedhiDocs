
# Propriedades

As propriedades de widgets são algumas definições de comportamento dentro da tela de cada uma delas, uma lista delas seria:
###### Utilize CTRL+F para buscar palavras chaves ou as propriedades em si.

### showOnView


+ Recebe: true/false
+ Ação: Visualiza registro no Swipe
+ Exemplo:
    
    ```json
     "showOnView": true
     ```

###### Keys: showOnView, swipe


### showOnList

+ Recebe: true/false
+ Ação: Lista no grid
+ Exemplo:
    
    ```json
     "showOnList": true
     ```
###### Keys: showOnList, grid, lista


### showOnForm

+ Recebe: true/false
+ Ação: Edita/Inclui registro
+ Exemplo:
    
    ```json
     "showOnForm": true
     ```
###### Keys: showOnForm, incuir, alterar, editar


### readOnly

+ Recebe: true/false
+ Ação: Se é somente visivel ou passível de edição
+ Exemplo:
    
    ```json
     "readOnly": true
     ```
###### Keys: readOnly, editar, leitura, read


### isVisible

+ Recebe: true/false
+ Ação: Se o campo é visivel ou não
+ Exemplo:
    
    ```json
     "isVisible": true
     ```
###### Keys: isVisible, visibilidade, campo



### template

+ Recebe: string da localidade de um template
+ Ação: Define o template da field/widget
+ Exemplo:
    
    ```json
     "template": "field/select-multiple.html"
     ```
###### Keys: template


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

###### Keys: validação, validacao, required


### filterProperties

+ Recebe: Objeto com propriedades que serão exibidas só na parte de filtragem
+ Ação: Define propriedades específicas para aba de filtros, pode ser utilizado quaisquer outra propriedade
+ Exemplo:
```json
    "filterProperties": {
        "isVisible": false
    }
```
###### Keys: filtro, propriedades


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
    "name": "modulo#/arquivo",
    "lazyLoad": false,
    "rest": true
 },
```
###### Keys: dataSource, banco de dados, dados

### label

+ Recebe: string
+ Ação: define o nome que mostrará ao usuário no campo.
+ Exemplo:
```json
 "label": "nome do campo para user",
```
###### Keys: label, user, usuário

### name

+ Recebe: string
+ Ação: define o nome do campo que poderá ser adquirido no backend se enviar como row e também será esse o nome da currentRow
+ Exemplo:
```json
 "name": "nome do campo",
```
###### Keys: name, nome, campo

### maxlength

+ Recebe: integer
+ Ação: define o tamanho de caracteres que um campo poder ter
+ Exemplo:
```json
 "maxlength": 20,
```
###### Keys: field, tamanho da field

### class
+ Recebe: integer
+ Ação: define o tamanho do campo em seu espaço, parece com bootstrap, um espaço tem um máximo de tamanho 12.
+ Exemplo:
```json
 "class": 12,
```
###### Keys: bootstrap, size, field, tamanho, campo