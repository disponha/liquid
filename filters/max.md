---
title: max
description: Liquid filter that limits a number to a maximum value
---

Limits a number to a maximum value.

<p class="code-label">Input</p>
{% raw %}
```liquid
{{ 4 | max: 5 }}
```
{% endraw %}

<p class="code-label">Output</p>
{% raw %}
```
4
```
{% endraw %}

<p class="code-label">Input</p>
{% raw %}
```liquid
{{ 4 | max: 3 }}
```
{% endraw %}

<p class="code-label">Output</p>
{% raw %}
```
3
```
{% endraw %}
