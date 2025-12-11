[**jules-api-node**](../README.md)

---

[jules-api-node](../globals.md) / Plan

# Type Alias: Plan

> **Plan** = `object`

A plan is a sequence of steps that the agent will take to complete the task.

## Properties

### createTime?

> `optional` **createTime**: `string`

Output only. Time when the plan was created.
Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9
fractional digits. Offsets other than "Z" are also accepted. Examples:
"2014-10-02T15:01:23Z", "2014-10-02T15:01:23.045123456Z" or "2014-10-02T15:01:23+05:30".

---

### id?

> `optional` **id**: `string`

Output only. ID for this plan; unique within a session.

---

### steps?

> `optional` **steps**: [`PlanStep`](PlanStep.md)[]

Output only. The steps in the plan.
