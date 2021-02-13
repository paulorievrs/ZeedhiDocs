# Eventos
As widgets contem eventos que podem ser realizados. Uma lista deles é:
###### Utilize CTRL+F para buscar os eventos.

```js
'WidgetBeforeInlineEditMoveRow',
'WidgetBeforeMoveRow',
'WidgetAfterMoveRow',
'WidgetBeforeNewRow',
'WidgetNewRow',
'WidgetOnEnter',
'WidgetOnEnterOnce',
'WidgetOnEnterTab',
'WidgetOnSync',
'WidgetBeforeSelectRow',
'WidgetAfterSelectRow',
'WidgetBeforeUnselectRow',
'WidgetAfterUnselectRow',
'WidgetOnCancel',
'WidgetOnSave',
'WidgetBeforeSelectAll',
'WidgetAfterSelectAll',
'WidgetBeforeUnselectAll',
'WidgetAfterUnselectAll',
'WidgetOnInitDataSource',
'WidgetAfterLoadDataSource',
'WidgetAfterLoadDataSourceError',
'WidgetPopUpOnCancel',
'WidgetOnActivate',
'WidgetOnDeactivate',
'WidgetOnDateClick',
'WidgetOnMonthClick',
'WidgetOnYearClick',
'WidgetOnDashboardClick',
'WidgetOnDashboardConfigClick',
'WidgetOnSaveInlineEdit',
'WidgetOnCancelInlineEdit',
'WidgetOnSaveRelations',
'WidgetOnOpenDetail',
'WidgetOnCloseSwipe',
'WidgetOnNewColor',
'WidgetOnChangeMonth',
'WidgetOnChangeYear',
'WidgetOnChangeDecade',
'WidgetOnTimelineIconClick',
'ContainerOnBack',
'ContainerBeforeClose',
'ContainerAfterClose',
'ContainerBeforeinit',
'ContainerAfterinit',
'ContainerAfterOpenreport',
'WizardOnDecision',
'WizardAfterOpenStage',
'WizardBeforePreviousStage',
'WizardAfterPreviousStage',
'WizardBeforeNextStage',
'WizardAfterNextStage',
'WizardOnFinish',
'WizardOnCancel',
'FieldOnChange',
'FieldOnInput',
'FieldOnCancel',
'FieldOnAdd',
'FieldOnConfirm',
'FieldOnClick',
'FieldOnBlur',
'FieldOnKeypress',
'FieldOnKeyup',
'FieldOnKeydown',
'FieldAfterMoveRow',
'FieldBeforeMoveRow',
'FieldOnFocus',
'FieldBeforeSelectOpen',
'FieldAfterSelectOpen',
'FieldAfterSelectFile',
'FieldAfterDeselectFile',
'FieldInlineEdit',
'FieldOnNewColor',
'ActionEvent',
'ElementOnClick',
'ElementOnTouchstart',
'NotificationEvent',
'onUpdate',
'RepositoryOnRetry',
'EventOnContainerOpen',
'EventOnRequestMetaDataStart',
'EventOnRequestStart',
'EventOnRequestEnd',
'EventOnRequestRetry',
'EventOnRequestSuccess',
'EventOnRequestError',
'EventOnRequestIdle',
'KanbanBeforeMoveItem',
'KanbanAfterMoveItem',
'KanbanOnTaskClick',
'MenuOnClick',
'ProductOnClick',
'FilterAfterApply',
'FilterBeforeApply'
```

Aos poucos serão preenchidos definições.

<hr>


### WidgetOnEnter

Ao carregar a widget irá disparar esse evento, realizando o script JavaScript dele.

<hr>

### WidgetOnEnterOnce

Ao carregar a widget somente uma vez irá disparar esse evento, realizando o script JavaScript dele.

<hr>

### FilterAfterApply

Ao aplicar o filtro e buscar os dados na datasource executa esse evento (antes de mostrar, é justo na hora que volta do datasource)

<hr>

### FilterBeforeApply

Ao clicar em aplicar o filtro, ele realiza esse evento antes de buscar os dados no datasource

<hr>

### FieldOnChange

Ao alterar o estado da filed, seja usando um template de select e selecionando um dado, ele realiza esse evento.

<hr>

### FieldBeforeSelectOpen

Antes de abrir o select, executa o evento

<hr>

### FieldAfterSelectOpen

Após de abrir o select, executa o evento

<hr>

### WidgetPopUpOnCancel

Após cancelar no popup executa o evento

<hr>