## Motivation

The Pub/Sub pattern is needed every now and then and this library is a no dependency, tiny and typesafe solution.

## Get started

Install

```bash
npm install --save lightcast
# or
yarn add lightcast
```

Use

```typescript
import { createPubSub } from 'lightcast'

// create
const pubSub = createPubSub<string>()

// subscribe anywhere in your app
pubSub.subscribe(console.log)
pubSub.subscribe(console.log)

// dispatch
pubSub.dispatch('hello world')
```
