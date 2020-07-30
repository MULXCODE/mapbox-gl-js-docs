---
title: Fit to the bounds of a LineString
description: >-
  Get the bounds of a LineString by passing its first coordinates to
  [`LngLatBounds`](/mapbox-gl-js/api/#lnglatbounds)
  and chaining [`extend`](/mapbox-gl-js/api/#lnglatbounds#extend)
  to include the last coordinates.
tags:
  - user-interaction
thumbnail: zoomto-linestring
contentType: example
language:
- JavaScript
prependJs:
- "import Example from '../../components/example';"
- "import html from './zoomto-linestring.html';"
---

{{ <Example html={html} {...this.props} /> }}
