[**jules-api-node**](../README.md)

---

[jules-api-node](../globals.md) / ListActivitiesData

# Type Alias: ListActivitiesData

> **ListActivitiesData** = `object`

## Properties

### body?

> `optional` **body**: `never`

---

### path

> **path**: `object`

#### session

> **session**: `string`

Required. The parent session, which owns this collection of activities. Format:
sessions/{session} It takes the form sessions/{session}.

---

### query?

> `optional` **query**: `object`

#### pageSize?

> `optional` **pageSize**: `number`

Optional. The number of activities to return. Must be between 1 and 100, inclusive. If
unset, defaults to 50. If set to greater than 100, it will be coerced to 100.

#### pageToken?

> `optional` **pageToken**: `string`

Optional. A page token, received from a previous activities.list call.

---

### url

> **url**: `"/sessions/{session}/activities"`
