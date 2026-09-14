{%- comment -%}
Shared text for the two Reservoir Ducks variants.
Usage: {% include reservoir-ducks-story.md art="/assets/img/reservoir-ducks/dark.png" style="on-dark" %}
The artwork links to the page's first link, the shop page.
TODO: the story below is a placeholder written by Claude; replace it with your own.
{%- endcomment -%}
{%- assign shop = page.links | first -%}
Three ducks in suits and skinny red ties, walking towards you in slow motion. You know the scene. You may not have pictured it with ducks.

## The design

<figure class="art {{ include.style }}">{% if shop.disabled %}<img src="{{ include.art | relative_url }}" alt="Three ducks in suits and red ties walking side by side">{% else %}<a href="{{ shop.url }}" target="_blank" rel="noopener"><img src="{{ include.art | relative_url }}" alt="Three ducks in suits and red ties walking side by side"></a>{% endif %}</figure>

Black suits, white shirts, red ties, and three very serious ducks. One looks left, one looks at you, one looks right, because somebody has to watch the exits.
