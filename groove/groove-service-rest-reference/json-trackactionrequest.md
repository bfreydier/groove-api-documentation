---
title: TrackActionRequest JSON object | Groove Services
description:  Learn about TrackActionRequest JSON object in Groove Music API.
keywords: groove music, groove api, groove trackactionrequest json
author: sakley
ms.assetid: 299cdadf-3bae-414e-bda4-61005eaccbaf
---

# TrackActionRequest (JSON)  
The input element for every track action request: add and delete.

## TrackActionRequest
The TrackActionRequest object has the following specification.

| **Member** | **Type**       | **Description**                                                                                                                                                                                                                                                       |
|------------|----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| TrackIds   | List of string | List of track IDs to add to the user's collection. These IDs can be found through [/1/content/{id}/lookup](uri-content-lookup.md) or [/1/content/{namespace}/search?q={query}](uri-search-content.md), for example. |

## Sample JSON syntax
```json
{
  "TrackIds": [
    "music.873FB507-0100-11DB-89CA-0019B92A3933",
    "music.A83EB907-0100-11DB-89CA-0019B92A3933"
  ]
}
```

#### Parent
[Groove Service REST Reference](overview.md)
