---
title: 411 Length Required
slug: Web/HTTP/Status/411
translation_of: Web/HTTP/Status/411
---
{{HTTPSidebar}}

Le code de réponse d'erreur HTTP **`411 Length Required`** indique que le serveur refuse d'accepter la requête si celle-ci ne contient pas d'en-tête [`Content-Length`](/fr/docs/Web/HTTP/Headers/Content-Length).

> **Note :** Selon la spécification, lors de l'envoi de données en plusieurs fragments, l'en-tête `Content-Length` est absent et il est nécessaire d'ajouter la longueur du fragment courant au format hexadécimal. Pour plus de détails, se référer à la page sur l'en-tête [`Transfer-Encoding`](/fr/docs/Web/HTTP/Headers/Transfer-Encoding).

## Statut

```
411 Length Required
```

## Spécifications

| Spécification                                                    | Titre                                                         |
| ---------------------------------------------------------------- | ------------------------------------------------------------- |
| [RFC 7231, section 6.5.10: 411 Length Required](https://datatracker.ietf.org/doc/html/rfc7231#section-6.5.10) | Hypertext Transfer Protocol (HTTP/1.1): Semantics and Content |

## Voir aussi

- [`Content-Length`](/fr/docs/Web/HTTP/Headers/Content-Length)
- [`Transfer-Encoding`](/fr/docs/Web/HTTP/Headers/Transfer-Encoding)
