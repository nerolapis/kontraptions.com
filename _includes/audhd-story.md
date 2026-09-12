{%- comment -%}
Shared text for the two AuDHD variants.
Usage: {% include audhd-story.md art="/assets/img/audhd-dark.svg" style="on-dark" %}
  art    the artwork to show under "The design"
  style  on-dark or on-light, the background the artwork is meant for
The artwork links to the page's first link, the shop page.
{%- endcomment -%}
{%- assign shop = page.links | first -%}
A few months ago my wife was diagnosed with AuDHD. I wanted to celebrate that with a t-shirt, and I was surprised to find that nobody on the whole internet had made this design. Or at least nobody I could find. So I made one.

A few months later I was diagnosed too. We never had matching t-shirts. I guess now we do.

## The design

<figure class="art {{ include.style }}"><a href="{{ shop.url }}" target="_blank" rel="noopener"><img src="{{ include.art | relative_url }}" alt="The AuDHD design"></a></figure>

Au is gold on the periodic table, element 79. Put it in front of DHD and you get AuDHD, the name for having both autism and ADHD. The gold standard of neurodivergence, if you like.
