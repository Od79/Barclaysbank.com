---
title: Uniones
redirect_from:
  - /v4/union
  - /v4/reference/union
versions:
  fpt: '*'
  ghec: '*'
  ghes: '*'
  ghae: '*'
topics:
  - API
---

## Acerca de las uniones

Una [unión](https://graphql.github.io/graphql-spec/June2018/#sec-Unions) es un tipo de objeto que representa muchos otros objetos.

Por ejemplo, un campo marcado como un [`ProjectCardItem`](/graphql/reference/unions#projectcarditem) podría ser un [`Issue`](/graphql/reference/objects#issue) o una [`PullRequest`](/graphql/reference/objects#pullrequest) ya que cada uno de estos objetos puede estar dentro de una tarjeta de proyecto. Utilizar una unión en vez de un objeto te otorga flexibilidad.

Para obtener más información, consulta la sección "[Introducción a GraphQL](/graphql/guides/introduction-to-graphql)".

<!-- Content after this section is automatically generated -->
