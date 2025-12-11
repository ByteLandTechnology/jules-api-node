[**jules-api-node**](../README.md)

---

[jules-api-node](../globals.md) / ListSourcesResponses

# Type Alias: ListSourcesResponses

> **ListSourcesResponses** = `object`

## Properties

### 200

> **200**: `object`

If successful, the response body contains data with the following structure:

#### nextPageToken?

> `optional` **nextPageToken**: `string`

A token, which can be sent as pageToken to retrieve the next page. If this
field is omitted, there are no subsequent pages.

#### sources?

> `optional` **sources**: [`Source`](Source.md)[]

The sources from the specified request.
