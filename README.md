# Snippets VS Code - ADVPL
Compartilhe de trechos de usuários definidos em ADVPL para usuários do VS Code.

Trechos disponíveis:
* Aviso
* Cabeçalho de Fonte
* Cabeçalho de Rotina
* Conout
* DbSeek
* DbUseArea
* DbUseArea com While
* BeginSql
* EnvNotif - Envio de notificações
* FwMsExcel - Relatório em Excel
* addField (model MVC)
* cFil (Padrão de variavel com xFilial)
* For
* User Function
* FwmBrowse
* GetArea
* Help
* AddGrid (model MVC)
* JSON Serialize
* JSON Deserialize
* MenuDef
* MPFormModel (model MVC)
* MsgYesNo
* Processa
* RestArea
* Struct (MVC)
* Query (Variável de definição)
* While

### cFil

### Conout
Resultado:
```
Conout('ROTINA - DATA| MENSAGEM')
```

Variáveis disponiveis:
  * ROTINA: Definição da rotina que identifica o conout
  * DATA: Data no momento da execução
  * MENSAGEM: Mensagem definida pelo usuário



### For
Resultado:
```
For [VAR] := 1 to Len([ARRAY])
  [CURSOR]
Next [VAR]
```

Variáveis disponiveis:
  * VAR: Variável definida pelo usuário que servirá de índice do array a ser varrido.
  * ARRAY: Array que será lido pelo For
  * CURSOR: Posição do cursor ao final do snnipet

### While
Resultado:
```
While ([ALIAS])->(! Eof())
  [CURSOR]
  
  ([ALIA])->(Skip())
End
```

Variáveis disponiveis:
  * ALIAS: Alias definido pelo usuário
  * CURSOR: Posição do cursor ao final do snnipet
