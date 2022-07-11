---
id: node-git-server.httpduplex.cork
hide_title: true
custom_edit_url: null
title: HttpDuplex.cork() method
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) > [node-git-server](./node-git-server.md) > [HttpDuplex](./node-git-server.httpduplex.md) > [cork](./node-git-server.httpduplex.cork.md)

## HttpDuplex.cork() method

Buffers written data in memory. This data will be flushed when either the uncork or end methods are called.

<b>Signature:</b>

```typescript
cork(): this;
```

<b>Returns:</b>

this

## Example

request.cork(); request.write('buffer data '); request.write('before sending '); request.uncork();