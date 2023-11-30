---
sidebar_position: 3
---

# Parameters

Ideally, it should be possible for Tonic to feed parameters to the generator code with relative ease. In the case of a browser-based approach, please use URL parameters to enable the feeding of parameters to the generator code.

### `seed`

It should be possible to pass a `seed` to the generator with relative ease (e.g. a `seed` URL parameter), results should be deterministic based off the seed, so that users can regenerate their own images from their tokens.

### `width` and `height`

It should be possible to pass `width` and `height` pixel count values to the generator with relative ease (e.g. `width` and `height` URL parameters), it's alright if these values have to be the same or follow a certain aspect ratio, if the aspect ratio is 1:1, it's alright for this to be combined into a single `size` value (measured in pixels).

### `other traits`

If there's any other traits that may be helpful in shaping the curation set, it should be possible to pass dictate specific trait values with relative ease (e.g. through URL parameters)
