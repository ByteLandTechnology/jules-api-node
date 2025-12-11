[**jules-api-node**](../README.md)

---

[jules-api-node](../globals.md) / ListSessionsData

# Type Alias: ListSessionsData

> **ListSessionsData** = `object`

## Properties

### body?

> `optional` **body**: `never`

---

### path?

> `optional` **path**: `never`

---

### query?

> `optional` **query**: `object`

#### pageSize?

> `optional` **pageSize**: `number`

Optional. The number of sessions to return. Must be between 1 and 100, inclusive. If
unset, defaults to 30. If set to greater than 100, it will be coerced to 100.

#### pageToken?

> `optional` **pageToken**: `string`

Optional. A page token, received from a previous sessions.list call.

---

### url

> **url**: `"/sessions"`
