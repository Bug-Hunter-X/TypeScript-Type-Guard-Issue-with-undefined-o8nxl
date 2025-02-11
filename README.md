# TypeScript Type Guard Issue with undefined

This repository demonstrates a subtle issue with TypeScript's type guards when dealing with potentially undefined values.  The `greet` function is designed to handle null values gracefully, but it fails when passed `undefined`.  This is because TypeScript's type guards only strictly check for null, not undefined.

The solution provides a more robust approach that explicitly handles both null and undefined using optional chaining or nullish coalescing.