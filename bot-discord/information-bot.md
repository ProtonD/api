# Information Bot

{% api-method method="get" host="https://api.oldmodz95.me" path="/v1/bot/" %}
{% api-method-summary %}
Information BOT
{% endapi-method-summary %}

{% api-method-description %}
Have the information of a single bot
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="name" type="string" required=true %}
NAME bot.
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
BOT successfully retrieved.
{% endapi-method-response-example-description %}

```
{
"name":"ProtonDev",
"valid":"Valid",
"status":"No Banned",
"web":"https:\/\/discord.oldmodz95.me\/bot\/protondev\/"
}
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}
Invalid name or error
{% endapi-method-response-example-description %}

```
{"error":"Bot invalid or not found"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

## Forma Link

```text
https://api.oldmodz95.me/v1/bot/protondev
```

protondev = name bot

![](../.gitbook/assets/infos.png)

