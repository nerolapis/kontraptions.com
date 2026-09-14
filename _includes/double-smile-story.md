{%- comment -%}
Shared text for the two Double Smile variants.
Usage: {% include double-smile-story.md art="/assets/img/double-smile/dark.png" style="on-dark" %}
The artwork links to the page's first link, the shop page.
TODO: the story below is a placeholder written by Claude; replace it with your own.
{%- endcomment -%}
{%- assign shop = page.links | first -%}
Two smileys, standing a little too close, until they are one. Three eyes, one wobbly mouth, and a face that cannot quite decide how it feels about it.

## The design

<figure class="art {{ include.style }}">{% if shop.disabled %}<img src="{{ include.art | relative_url }}" alt="Two overlapping smiley faces merged into one, with three eyes and a wavy mouth">{% else %}<a href="{{ shop.url }}" target="_blank" rel="noopener"><img src="{{ include.art | relative_url }}" alt="Two overlapping smiley faces merged into one, with three eyes and a wavy mouth"></a>{% endif %}</figure>

It reads as one face from across the room and as two from up close, which is roughly how it feels to be in two moods at once.
