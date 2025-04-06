# XXH3 Implementation Notes

This file contains implementation notes for the XXH3 hash function.

- The implementation uses runtime detection of CPU features like AVX2 and NEON
- Different code paths are used for different input sizes
- The code is optimized for performance with unsafe intrinsics
