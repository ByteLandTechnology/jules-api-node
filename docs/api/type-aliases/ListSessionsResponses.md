[**jules-api-node**](../README.md)

---

[jules-api-node](../globals.md) / ListSessionsResponses

# Type Alias: ListSessionsResponses

> **ListSessionsResponses** = `object`

## Properties

### 200

> **200**: `object`

Response message for sessions.list.

#### nextPageToken?

> `optional` **nextPageToken**: `string`

A token, which can be sent as pageToken to retrieve the next page. If this
field is omitted, there are no subsequent pages.

#### sessions?

> `optional` **sessions**: [`Session`](Session.md)[]

The sessions from the specified request.
