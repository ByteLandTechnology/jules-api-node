[**jules-api-node**](../README.md)

---

[jules-api-node](../globals.md) / GitPatch

# Type Alias: GitPatch

> **GitPatch** = `object`

A patch in Git format.

## Properties

### baseCommitId?

> `optional` **baseCommitId**: `string`

The base commit id of the patch. This is the id of the commit that the patch should be
applied to.

---

### suggestedCommitMessage?

> `optional` **suggestedCommitMessage**: `string`

A suggested commit message for the patch, if one is generated.

---

### unidiffPatch?

> `optional` **unidiffPatch**: `string`

The patch in unidiff format.
