[**jules-api-node**](../README.md)

---

[jules-api-node](../globals.md) / Activity

# Type Alias: Activity

> **Activity** = \{ `agentMessaged?`: [`AgentMessaged`](AgentMessaged.md); \} \| \{ `userMessaged?`: [`UserMessaged`](UserMessaged.md); \} \| \{ `planGenerated?`: [`PlanGenerated`](PlanGenerated.md); \} \| \{ `planApproved?`: [`PlanApproved`](PlanApproved.md); \} \| \{ `progressUpdated?`: [`ProgressUpdated`](ProgressUpdated.md); \} \| \{ `sessionCompleted?`: [`SessionCompleted`](SessionCompleted.md); \} \| \{ `sessionFailed?`: [`SessionFailed`](SessionFailed.md); \} & `object`

## Type Declaration

### artifacts?

> `optional` **artifacts**: [`Artifact`](Artifact.md)[]

Output only. The artifacts produced by this activity.

### createTime?

> `optional` **createTime**: `string`

Output only. The time at which this activity was created.
Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or
9 fractional digits. Offsets other than "Z" are also accepted. Examples:
"2014-10-02T15:01:23Z", "2014-10-02T15:01:23.045123456Z" or
"2014-10-02T15:01:23+05:30".

### description?

> `optional` **description**: `string`

Output only. A description of this activity.

### id?

> `optional` **id**: `string`

Output only. The id of the activity. This is the same as the "{activity}" part of
the resource name (e.g., "sessions/{session}/activities/{activity}").

### name?

> `optional` **name**: `string`

Identifier. The full resource name (e.g.,
"sessions/{session}/activities/{activity}").

### originator?

> `optional` **originator**: `string`

The entity that this activity originated from (e.g. "user", "agent", "system").
