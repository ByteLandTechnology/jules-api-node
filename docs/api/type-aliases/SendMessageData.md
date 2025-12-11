[**jules-api-node**](../README.md)

---

[jules-api-node](../globals.md) / SendMessageData

# Type Alias: SendMessageData

> **SendMessageData** = `object`

## Properties

### body

> **body**: `object`

The request body contains data with the following structure:

#### prompt

> **prompt**: `string`

Required. The user prompt to send to the session

---

### path

> **path**: `object`

#### session

> **session**: `string`

Required. The resource name of the session to post the message to. Format:
sessions/{session} It takes the form sessions/{session}.

---

### query?

> `optional` **query**: `never`

---

### url

> **url**: `"/sessions/{session}:sendMessage"`
