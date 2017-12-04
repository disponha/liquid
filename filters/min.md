---
title: min
description: Liquid filter that limits a number to a minimum value
---

Limits a number to a minimum value.

<p class="code-label">Input</p>
{% raw %}
```liquid
{{ 4 | min: 5 }}
```
{% endraw %}

<p class="code-label">Output</p>
{% raw %}
```
5
```
{% endraw %}

<p class="code-label">Input</p>
{% raw %}
```liquid
{{ 4 | min: 3 }}
```
{% endraw %}

<p class="code-label">Output</p>
{% raw %}
```
4
```
{% endraw %}
