# Redis storage adapter for grammY

Storage adapter that can be used to
[store your session data](https://grammy.dev/plugins/session.html) in
[Redis](https://redis.io/) when using sessions.

## Installation

Node

```bash
npm install @grammyjs/storage-redis ioredis --save
npm install @types/ioredis -D
```

```ts
import { RedisAdapter } from "@grammyjs/storage-redis";
import IORedis from "ioredis";
```

Deno

```ts
import { RedisAdapter } from "https://deno.land/x/grammy_storages/redis/src/mod.ts";
import { connect } from "https://deno.land/x/redis@v0.27.0/mod.ts";
```

## Usage

You can check
[examples](https://github.com/grammyjs/storages/tree/main/packages/redis/examples)
folder
