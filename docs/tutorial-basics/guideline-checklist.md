---
sidebar_position: 5
---

# Guideline Checklist

The following checklist of requests helps align artists with Tonic's processes in order to make a drop as seamless as possible, we understand that in some cases it isn't possible to meet certain requests, please feel free to discuss these scenarios with Tonic representatives.

- Import/load third-party libraries in a way that is appropriate to your project (e.g. via `<script>` tags in the case of client-side Javascript).
- Consolidate your code into as few files as viable, preferably a single file when possible (e.g. one HTML file with inlined JS in the case of a browser-friendly generator)
- Ability to pass a seed to the generator with relative ease (e.g. a URL parameter such as `seed` in the case of a browser-friendly generator), results should be deterministic based off the seed, so that users can regenerate their own images
- Ability to pass a 