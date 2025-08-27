{% css %}
.articles-list {
--width-column-min: calc(var(--width-max) / 4);
--width-column-max: 100%;
& article {
width: 100%;
border-inline-start: var(--deco-thickness) solid var(--color-border);
padding-inline-start: var(--deco-thickness);
}
}
{% endcss %}
