# :giraffe: Giraugh Vector

Utilities for working with vectors in typescript.

## Installation
```bash
yarn add @giraugh/vector
```

## Usage
```ts
import { Vector } from '@giraugh/vector'

const position = new Vector(100, 100)
  .add(Vector.random())
  .mul(3)
  .dot(Vector.ONE)
```

## Contributing

All PRs and issues are welcome :)

## Copyright

You are welcome to use this software commercially or non-commercially for any purpose with or without attribution as per the attached MIT license.
