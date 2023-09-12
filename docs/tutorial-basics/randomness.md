---
sidebar_position: 4
---

# Randomness

Regarding random number generation: We do not have a preference for what random number generation technique is used to determine traits and other characteristics from the seed, as long as it is deterministic and reproducible. JavaScript’s math.random() function does not provide this guarantee, as different engines utilize different implementations of the function. Any deterministic PRNG implemented in JavaScript should be sufficient. If you have used sfc32 for ArtBlocks projects before, and that will work for this project too. Other good candidate algorithms are mulberry and gjrand. Please let us know if you need help implementing any of these.