## Motivation

Such a simple pattern to implement that I'd rather use my own library when I need this :)

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
