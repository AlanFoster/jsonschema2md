---
template: reference
foo: bar
---

# Custom Schema

```
https://example.com/schemas/custom
```

This is an extensible schema. It has `definitions`, that can be used in other schemas. Additionally, it allows custom properties.

| Abstract | Extensible | Custom Properties | Defined In |
|----------|------------|-------------------|------------|
| Can be instantiated | Yes | Allowed | [custom.schema.json](custom.schema.json) |

# Custom Properties

| Property | Type | Required |
|----------|------|----------|
| [foo](#foo) | `string` | Optional |
| [bar](#bar) | `string` | Optional |