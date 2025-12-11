[**jules-api-node**](../README.md)

---

[jules-api-node](../globals.md) / ListActivitiesResponses

# Type Alias: ListActivitiesResponses

> **ListActivitiesResponses** = `object`

## Properties

### 200

> **200**: `object`

If successful, the response body contains data with the following structure:

#### activities?

> `optional` **activities**: [`Activity`](Activity.md)[]

The activities from the specified session

#### nextPageToken?

> `optional` **nextPageToken**: `string`

A token, which can be sent as pageToken to retrieve the next page. If this
field is omitted, there are no subsequent pages.
