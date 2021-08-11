---
description: API documentation for the Analytics webhook.
---

# Analytics Webhook

{% api-method method="post" host="https://app.doubleloop.app" path="/zapier" %}
{% api-method-summary %}
Create a metric data point
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create a metric data point.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-query-parameters %}
{% api-method-parameter name="api\_token" type="string" required=true %}
API token from DoubleLoop
{% endapi-method-parameter %}

{% api-method-parameter name="name" type="string" required=true %}
Name of the metric
{% endapi-method-parameter %}

{% api-method-parameter name="date" type="string" required=true %}
Date of the metric data point
{% endapi-method-parameter %}

{% api-method-parameter name="value" type="number" required=true %}
Value of the metric data point
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Metric data point successfully created.
{% endapi-method-response-example-description %}

```
{
  "ok": true,
  "metric": {
    "id": 1174,
    "organization_id": 3,
    "name": "Homepage load time (ms)",
    "date": null,
    "value": null,
    "created_at": "2021-04-29T22:16:17Z",
    "updated_at": "2021-04-29T22:16:17Z"
  },
  "metric_data_point": {
    "id": 1232,
    "date": "2021-04-29",
    "value": 0,
    "metric_id": 1174,
    "created_at": "2021-04-29T22:24:34Z",
    "updated_at": "2021-04-29T22:24:34Z"
  }
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



