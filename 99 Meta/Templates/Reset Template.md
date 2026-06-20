---
type: reset
title:
reset_number:
status:
start_date:
end_date:
reset_type:
severity:
trigger:
affected_systems: []
affected_alters: []
affected_locations: []
tags:
  - reset
aliases: []
---

> [!infobox|n-th]
> # {{title}}
>
> #### Reset Information
>
> | Property | Value |
> |-----------|--------|
> | Reset Number | |
> | Type | |
> | Status | |
> | Severity | |
> | Trigger | |
>
> #### Timeline
>
> | Property | Value |
> |-----------|--------|
> | Start Date | |
> | End Date | |
> | Duration | |
> | Recovery Status | |
>
> #### Scope
>
> | Property | Value |
> |-----------|--------|
> | Alters Affected | |
> | Systems Affected | |
> | Locations Affected | |
> | Major Changes | |
>
> #### Current Status
>
> - Recovery Progress:
> - Stability:
> - Notes:

# Overview

> [!note|clean no-i]
> Summary of the reset, its effects, and its significance in system history.

---

# Reset Information

## Basic Details

| Property | Value |
|-----------|--------|
| Title | |
| Reset Number | |
| Reset Type | |
| Status | |
| Severity | |
| Trigger | |

## Summary

Describe the reset and what happened overall.

---

# Pre-Reset State

## System Status Before Reset

Describe the state of the system before the reset occurred.

## Known Conditions

- 
- 
- 

## Active Systems

| System | Status |
|----------|--------|
| | |
| | |

## Notable Features

- 
- 
- 

---

# Trigger & Causes

## Immediate Trigger

Describe the event or circumstance that initiated the reset.

## Contributing Factors

- 
- 
- 

## Warning Signs

- 
- 
- 

---

# Reset Process

## Initial Phase

Describe what happened when the reset began.

## Major Changes

| Change | Description |
|---------|-------------|
| | |
| | |

## Observed Effects

- 
- 
- 

## Duration Notes

Document how long the reset lasted and any phases it went through.

---

# Structural Changes

## Alter Changes

### New Alters

| Alter | Notes |
|---------|-------|
| | |
| | |

### Missing Alters

| Alter | Notes |
|---------|-------|
| | |
| | |

### Changed Alters

| Alter | Change |
|---------|--------|
| | |
| | |

---

## System Changes

### New Systems

| System | Notes |
|----------|-------|
| | |
| | |

### Removed Systems

| System | Notes |
|----------|-------|
| | |
| | |

### Reorganized Systems

| System | Description |
|----------|------------|
| | |
| | |

---

## Location Changes

### New Locations

| Location | Notes |
|-----------|-------|
| | |
| | |

### Removed Locations

| Location | Notes |
|-----------|-------|
| | |
| | |

### Modified Locations

| Location | Change |
|-----------|--------|
| | |
| | |

---

# Memory & Knowledge Changes

## Information Lost

- 
- 
- 

## Information Retained

- 
- 
- 

## Information Gained

- 
- 
- 

## Memory Notes

Describe any changes in memory access, barriers, or awareness.

---

# Impact Assessment

## Immediate Impact

Describe the short-term effects.

## Long-Term Impact

Describe lasting consequences.

## Relationship Changes

- 
- 
- 

## Functional Changes

- 
- 
- 

---

# Recovery

## Recovery Process

Describe how the system adapted after the reset.

## Stabilization Efforts

- 
- 
- 

## Current Understanding

Document what is currently known about the reset.

## Remaining Questions

- 
- 
- 

---

# Timeline

## Chronology

| Date | Event |
|--------|--------|
| | |
| | |
| | |

---

# Historical Comparison

## Differences From Previous Reset

Describe similarities and differences.

## Patterns Observed

- 
- 
- 

## Lessons Learned

- 
- 
- 

---

# Related Content

## Related Resets

```dataview
TABLE reset_number AS "Reset", start_date AS "Date"
FROM "Resets"
WHERE file.name != this.file.name
SORT reset_number DESC
```

## Affected Alters

```dataview
LIST
FROM "Characters"
WHERE contains(file.outlinks, this.file.link)
```

## Affected Systems

```dataview
LIST
FROM "Systems"
WHERE contains(file.outlinks, this.file.link)
```

## Affected Locations

```dataview
LIST
FROM "Locations"
WHERE contains(file.outlinks, this.file.link)
```

## Related Events

```dataview
LIST
FROM "Events"
WHERE contains(file.outlinks, this.file.link)
```

## Related Notes

```dataview
LIST
FROM outgoing([[]])
```

---

# Archive

## Documentation Sources

- [[Source Note]]
- [[System Log]]
- [[Meeting Notes]]

## Reliability Notes

Document uncertainty, conflicting reports, or incomplete information.

---

# Notes

Additional observations, discoveries, theories, or miscellaneous information.