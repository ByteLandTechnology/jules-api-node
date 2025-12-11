[**jules-api-node**](../README.md)

---

[jules-api-node](../globals.md) / Session

# Type Alias: Session

> **Session** = `object`

A continuous unit of work within a specific context, similar to a chat session. A session is
initiated with a prompt and a source.

## Properties

### automationMode?

> `optional` **automationMode**: `"AUTOMATION_MODE_UNSPECIFIED"` \| `"AUTO_CREATE_PR"`

Optional. Input only. The automation mode of the session. If not set, the default
automation mode will be used.

---

### createTime?

> `optional` **createTime**: `string`

Output only. The time the session was created.
Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9
fractional digits. Offsets other than "Z" are also accepted. Examples:
"2014-10-02T15:01:23Z", "2014-10-02T15:01:23.045123456Z" or "2014-10-02T15:01:23+05:30".

---

### id?

> `optional` **id**: `string`

Output only. The id of the session. This is the same as the "{session}" part of the
resource name (e.g., "sessions/{session}").

---

### name?

> `optional` **name**: `string`

Output only. Identifier. The full resource name (e.g., "sessions/{session}").

---

### outputs?

> `optional` **outputs**: [`SessionOutput`](SessionOutput.md)[]

Output only. The outputs of the session, if any.

---

### prompt

> **prompt**: `string`

Required. The prompt to start the session with.

---

### requirePlanApproval?

> `optional` **requirePlanApproval**: `boolean`

Optional. Input only. If true, plans the agent generates will require explicit plan
approval before the agent starts working. If not set, plans will be auto-approved.

---

### sourceContext

> **sourceContext**: [`SourceContext`](SourceContext.md)

Required. The source to use in this session, with additional context.

---

### state?

> `optional` **state**: `"STATE_UNSPECIFIED,"` \| `"QUEUED,"` \| `"PLANNING,"` \| `"AWAITING_PLAN_APPROVAL,"` \| `"AWAITING_USER_FEEDBACK,"` \| `"IN_PROGRESS,"` \| `"PAUSED,"` \| `"FAILED,"` \| `"COMPLETED,"`

Output only. The state of the session.

---

### title?

> `optional` **title**: `string`

Optional. If not provided, the system will generate one.

---

### updateTime?

> `optional` **updateTime**: `string`

Output only. The time the session was last updated.
Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9
fractional digits. Offsets other than "Z" are also accepted. Examples:
"2014-10-02T15:01:23Z", "2014-10-02T15:01:23.045123456Z" or "2014-10-02T15:01:23+05:30".

---

### url?

> `optional` **url**: `string`

Output only. The URL of the session to view the session in the Jules web app.
