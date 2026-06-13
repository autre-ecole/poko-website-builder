---
translationKey: media-test
lang: fr
createdAt: 2026-06-13T15:54:00.000Z
uuid: e2e474c8502d
localizationKey: 9b76779e5302
status: noindex
name: media-test
---
# Médias

## Classe rouge

::: div { .medias .flow .prose}

### W3School

<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

### Not working

<figure>
  <figcaption class="h4">Nuit</figcaption>
  <audio controls src="/assets/files/nuit.mp3"></audio>
</figure>

#### Audio without figure

<audio controls src="/assets/files/nuit.mp3"></audio>

### Tests

<audio controls>
  <source src="/assets/files/nuit.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

:::

{% css %}

.medias figure {
margin-inline: 0;
}

{% endcss %}
