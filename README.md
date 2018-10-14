---
description: Punto de enlace del orquestador para el envío de mensajes
---

# sendmessage

{% api-method method="post" host="https://cactbot.simplemente.online" path="/orquestador/v1/sendmessage" %}
{% api-method-summary %}
sendmessage
{% endapi-method-summary %}

{% api-method-description %}
Punto de entrada del sistema para envío de consultas al orquestador
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-body-parameters %}
{% api-method-parameter name="message" type="object" required=true %}
objeto message a enviar
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
devuelve un objeto response con el resultado de la consulta  
{% endapi-method-response-example-description %}

```javascript
{
    text: "Hola, un placer"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



