---
translationKey: articles
order: 8
lang: fr
createdAt: 2026-10-02T10:02:00.000Z
ldType: WebPage
name: Articles
eleventyNavigation:
  add: Nav
status: published
---

# La parole de l'Autre École

Cette page rassemble les articles, réflexions et témoignages rédigés par les différents acteurs de notre communauté éducative: animateurs, parents, enfants et partenaires. Chaque contribution illustre une facette de notre projet pédagogique et de notre vie coopérative.

## Nos derniers articles

{% sectionCollection  %}
{% sectionHeader  %}
## Nos derniers articles
{% endsectionHeader %}
{% collection collection="articles", filters=[{"by":"first","value":3}], sortCriterias=[{"by":"date","direction":"desc"}], type="switcher", class="articles-list", itemPartial="card-article" %}{% endcollection %}

{% endsectionCollection %}

Retrouvez la liste complète des articles dans notre [archive](/articles-archive/).

## Contribuer à la réflexion collective

La pédagogie Freinet encourage l'expression libre et la coopération. Dans cet esprit, nous accueillons les contributions de tous les membres de notre communauté:

- **Témoignages de pratiques** partagés par les animateurs
- **Récits d'expériences** vécues par les enfants
- **Réflexions pédagogiques** des parents et partenaires
- **Comptes-rendus** des projets et événements de l'école

Si vous êtes membre de notre communauté et souhaitez proposer un article, n'hésitez pas à contacter l'école.

## Archives par thématiques

Bientôt disponible : accès aux articles classés par thématiques (pédagogie Freinet, projets d'école, vie de classe, témoignages, événements...).

{% if collections.articles.length == 0 %}

<div class="notice">
  <p>Aucun article n'est publié pour le moment. Revenez prochainement !</p>
</div>
{% endif %}

{% partial "styles-articles-list.md" %}
