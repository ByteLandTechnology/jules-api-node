[**jules-api-node**](../README.md)

---

[jules-api-node](../globals.md) / ListSourcesData

# Type Alias: ListSourcesData

> **ListSourcesData** = `object`

## Properties

### body?

> `optional` **body**: `never`

---

### path?

> `optional` **path**: `never`

---

### query?

> `optional` **query**: `object`

#### filter?

> `optional` **filter**: `string`

Optional. The filter expression for listing sources, based on AIP-160. If not set, all
sources will be returned. Currently only supports filtering by name, which can be used
to filter by a single source or multiple sources separated by OR.

#### pageSize?

> `optional` **pageSize**: `number`

Optional. The number of sources to return. Must be between 1 and 100, inclusive. If
unset, defaults to 30. If set to greater than 100, it will be coerced to 100.

#### pageToken?

> `optional` **pageToken**: `string`

Optional. A page token, received from a previous sources.list call.

---

### url

> **url**: `"/sources"`
