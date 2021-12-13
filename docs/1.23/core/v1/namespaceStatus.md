---
permalink: /1.23/core/v1/namespaceStatus/
---

# core.v1.namespaceStatus

"NamespaceStatus is information about the current status of a Namespace."

## Index

* [`fn withConditions(conditions)`](#fn-withconditions)
* [`fn withConditionsMixin(conditions)`](#fn-withconditionsmixin)
* [`fn withPhase(phase)`](#fn-withphase)

## Fields

### fn withConditions

```ts
withConditions(conditions)
```

"Represents the latest available observations of a namespace's current state."

### fn withConditionsMixin

```ts
withConditionsMixin(conditions)
```

"Represents the latest available observations of a namespace's current state."

**Note:** This function appends passed data to existing values

### fn withPhase

```ts
withPhase(phase)
```

"Phase is the current lifecycle phase of the namespace. More info: https://kubernetes.io/docs/tasks/administer-cluster/namespaces/\n\nPossible enum values:\n - `\"Active\"` means the namespace is available for use in the system\n - `\"Terminating\"` means the namespace is undergoing graceful termination"