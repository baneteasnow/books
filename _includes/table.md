|  A  |     |  B  |  C  |     |  D  |  E  |  F  |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| A-1 |     | B-1 | C-1 |     |  -  |  -  |  -  |
| A=2 |     | B-2 | C-2 |     | D-2 | E-2 | F-2 |
| A-3 |     | B-3 | C-3 |     | D-3 | E-3 | F-3 |
| A-4 |     | B-4 | C-4 |     | D-4 | E-4 | F-4 |

{% for item in site.data.list %}
{%- if site.data.list.item.notes == "A-1" -%}
{{ site.data.list.item.notes == "A-1" | size}}
{%- endif -%}
