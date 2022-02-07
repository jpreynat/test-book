# Chapter 1

Bla bla bla bla

![](.gitbook/assets/small-duck.svg)

![progress](https://img.shields.io/badge/progress-100%25-green.svg)

```text
{% sw_extends '@Storefront/storefront/base.html.twig' %}

{% block base_body %}

    {# We want to set our own icon here #}
    <h1>Custom icon:</h1>
    {% sw_icon 'done-outline-24px' style {
        'size': 'lg',
        'namespace': 'TestPlugin',
        'pack': 'solid'
    } %}
    {{ parent() }}

{% endblock %}
```
