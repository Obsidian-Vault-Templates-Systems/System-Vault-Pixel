---
type: condition
name:
classification:
status:
severity:
diagnosis_status:
diagnosed_by:
diagnosis_date:
onset_date:
primary_systems: []
affected_alters: []
tags:
  - condition
aliases: []
---

> [!infobox|n-th]
> # {{title}}
>
> #### Condition Information
>
> | Property | Value |
> |-----------|--------|
> | Classification | |
> | Status | |
> | Severity | |
> | Diagnosis Status | |
> | Onset Date | |
>
> #### Clinical Information
>
> | Property | Value |
> |-----------|--------|
> | Diagnosed By | |
> | Diagnosis Date | |
> | Primary System | |
> | Affected Alters | |
>
> #### Current Status
>
> - Stability:
> - Last Reviewed:
> - Notes:

# Overview

> [!note|clean no-i]
> Brief summary of the condition, disability, disorder, illness, syndrome, or other health-related concern.

---

# Condition Information

## Basic Details

| Property | Value |
|-----------|--------|
| Name | |
| Classification | |
| Status | |
| Severity | |
| Diagnosis Status | |
| Onset Date | |
| Diagnosis Date | |

## Description

Describe the condition and its overall impact.

---

# Diagnosis

## Diagnostic Information

| Property | Value |
|-----------|--------|
| Diagnosed By | |
| Facility | |
| Diagnostic Criteria Used | |
| Assessment Type | |

## Diagnostic History

| Date | Event |
|--------|--------|
| | |
| | |

## Notes

Document relevant diagnostic information.

---

# Symptoms

## Primary Symptoms

| Symptom | Severity | Frequency |
|----------|----------|-----------|
| | | |
| | | |

## Secondary Symptoms

| Symptom | Severity | Frequency |
|----------|----------|-----------|
| | | |
| | | |

## Episodic Symptoms

| Symptom | Trigger | Notes |
|----------|---------|-------|
| | | |
| | | |

---

# Impact

## Daily Living

### Activities Affected

- 
- 
- 

### Limitations

- 
- 
- 

### Accommodations

- 
- 
- 

## Functional Impact

| Area | Impact |
|--------|--------|
| School | |
| Work | |
| Social | |
| Physical | |
| Cognitive | |
| Emotional | |

---

# System Impact

## Affected Alters

| Alter | Impact | Notes |
|---------|--------|-------|
| | | |
| | | |

## System-Wide Effects

Describe how the condition affects the system as a whole.

## Variation Between Alters

Document differences in symptoms, severity, awareness, or impact.

---

# Management

## Current Treatments

| Treatment | Purpose | Notes |
|------------|---------|-------|
| | | |
| | | |

## Medications

| Medication | Purpose | Notes |
|------------|---------|-------|
| | | |
| | | |

## Coping Strategies

- 
- 
- 

## Accommodations

- 
- 
- 

---

# Triggers & Exacerbating Factors

## Known Triggers

- 
- 
- 

## Worsening Factors

- 
- 
- 

## Protective Factors

- 
- 
- 

---

# History

## Onset

Describe when symptoms first appeared.

## Timeline

| Date | Event |
|--------|--------|
| | |
| | |

## Major Changes

### Initial Symptoms

### Diagnosis

### Significant Developments

### Current Status

---

# Monitoring

## Severity Tracking

| Date | Severity | Notes |
|--------|----------|-------|
| | | |
| | | |

## Goals

- [ ]
- [ ]
- [ ]

## Follow-Up Needs

- [ ]
- [ ]
- [ ]

---

# Resources

## Educational Resources

- 
- 
- 

## Support Resources

- 
- 
- 

## Personal Notes

Document useful information, observations, or discoveries.

---

# Related Content

## Related Medications

```dataview
TABLE status AS "Status", dosage AS "Dosage"
FROM "Medical/Medications"
WHERE contains(file.outlinks, this.file.link)
```

## Related Providers

```dataview
LIST
FROM "People"
WHERE contains(file.outlinks, this.file.link)
```

## Related Appointments

```dataview
LIST
FROM "Medical/Appointments"
WHERE contains(file.outlinks, this.file.link)
```

## Related Notes

```dataview
LIST
FROM outgoing([[]])
```

## Affected Alters

```dataview
LIST
FROM "Characters"
WHERE contains(file.outlinks, this.file.link)
```

---

# Notes

Additional observations, questions, updates, research, accommodations, or miscellaneous information.