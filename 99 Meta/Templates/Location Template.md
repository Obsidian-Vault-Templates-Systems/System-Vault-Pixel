---
type: location
name:
category:
parent_location:
region:
system:
status:
accessibility:
created:
tags:
  - location
aliases: []
banner: "[[Default Banner.png]]"
---

> [!infobox|n-th]
> 
> # {{title}}
> 
> ![[Default Item Ice Cream.png]]
> 
> #### Location Info
> 
> |Property|Value|
> |---|---|
> |Category||
> |Region||
> |Parent Location||
> |System||
> |Status||
> 
> #### Overview
> 
> |Property|Value|
> |---|---|
> |Accessibility||
> |Population||
> |Activity||
> |Safety||
> 
> #### Quick Facts
> 
> |Property|Value|
> |---|---|
> |Climate||
> |Terrain||
> |Governing Group||
> |Established||
> 
> #### Current Status
> 
> - Occupied By:
>     
> - Last Visited:
>     
> - Notes:
>     

# Overview

> [!note|clean no-i]  
> Brief summary of the location and its significance.

---

# Classification

## Basic Information

|Property|Value|
|---|---|
|Name||
|Category||
|Region||
|Parent Location||
|Associated System||
|Status||
|Accessibility||

## Description

Describe the location as a whole.

---

# Geography

## Environment

|Property|Value|
|---|---|
|Climate||
|Terrain||
|Elevation||
|Size||
|Weather Patterns||

## Physical Description

Describe what the location looks like.

## Notable Features

|Feature|Description|
|---|---|
|||
|||

---

# Layout

## Areas

|Area|Purpose|
|---|---|
|||
|||

## Buildings

|Building|Function|
|---|---|
|||
|||

## Landmarks

|Landmark|Significance|
|---|---|
|||
|||

## Hidden Areas

|Area|Notes|
|---|---|
|||
|||

---

# Population

## Residents

```dataview
TABLE role AS "Role", status AS "Status"
FROM "Characters"
WHERE contains(residence, this.file.name)
SORT file.name ASC
```

## Regular Visitors

|Alter|Notes|
|---|---|
|||
|||

## Organizations

|Organization|Purpose|
|---|---|
|||
|||

---

# Function

## Purpose

Why does this location exist?

## Common Activities

## Important Uses

|Use|Description|
|---|---|
|||
|||

---

# Connections

## Connected Locations

|Location|Relationship|
|---|---|
|||
|||

## Transportation

|Method|Destination|
|---|---|
|||
|||

## Portals / Gateways

|Gateway|Destination|
|---|---|
|||
|||

---

# Ownership & Governance

## Owner

## Leadership

|Position|Holder|
|---|---|
|||
|||

## Rules

---

# History

## Origin

Describe how the location came to exist.

## Timeline

|Date|Event|
|---|---|
|||
|||

## Major Events

### Event

Description

### Event

Description

---

# Resources

## Important Objects

|Object|Significance|
|---|---|
|||
|||

## Resources

|Resource|Notes|
|---|---|
|||
|||

---

# Lore

## Stories

## Myths

## Rumors

## Unexplained Phenomena

---

# Safety

## Hazards

## Security

## Restrictions

---

# Related Content

## Related Locations

```dataview
LIST
WHERE parent_location = this.file.name
```

## Associated Systems

```dataview
LIST
FROM "Systems"
WHERE contains(file.outlinks, this.file.link)
```

## Residents

```dataview
LIST
FROM "Characters"
WHERE contains(residence, this.file.name)
```

## Related Notes

```dataview
LIST
FROM outgoing([[]])
```

---

# Notes

Additional observations, discoveries, changes, or miscellaneous information.