---
description: objeto message como parámetro del método sendmessage
---

# message

## message

| Propiedad | Tipo | Descripción |
| :--- | :--- | :--- |
| clientId | numérico | Identificador único del cliente |
| token | texto | Identificador de seguridad para poder acceder al sistema |
| input | objeto | Objeto [**input**](input.md) con el contenido del mensaje |

```text
{ 
    clientId : 1234567890,
    token : "1234567890123456789012345678901234567890",
    input: {
             text: "hola",
             cmd: ""
             } 
}
```



