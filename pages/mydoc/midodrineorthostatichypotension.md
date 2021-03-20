---
title: "Midodrine - Orthostatic hypotension"
sidebar: mydoc_sidebar
permalink: midodrineorthostatichypotension.html
toc: false 
---

{% include image.html url="images/midodrineorthostatichypotension.png" file="midodrineorthostatichypotension.png" alt="midodrineorthostatichypotension" %}

## Concepts

|------------|------|---------|
| Identifier | Name | Type    |
|------------|------|---------|
| MESH:D008879 | Midodrine | Drug |
| CHEBI:73248 | Deglymidodrine | ChemicalSubstance |
| UniProt:P35348 | Alpha-1A adrenergic receptor | Protein |
| UniProt:P35368 | Alpha-1B adrenergic receptor | Protein |
| GO:0006939 | Smooth muscle contraction | BiologicalProcess |
| GO:0008217 | Blood pressure | BiologicalProcess |
| MESH:D007024 | Orthostatic hypotension | Disease |
|------------|------|---------|

## Relationships

|---------|-----------|---------|
| Subject | Predicate | Object  |
|---------|-----------|---------|
| Midodrine | PRODUCES | Deglymidodrine |
| Deglymidodrine | INCREASES ACTIVITY OF | Alpha-1A Adrenergic Receptor |
| Deglymidodrine | INCREASES ACTIVITY OF | Alpha-1B Adrenergic Receptor |
| Alpha-1A Adrenergic Receptor | POSITIVELY REGULATES | Smooth Muscle Contraction |
| Alpha-1B Adrenergic Receptor | POSITIVELY REGULATES | Smooth Muscle Contraction |
| Smooth Muscle Contraction | POSITIVELY REGULATES | Blood Pressure |
| Blood Pressure | NEGATIVELY CORRELATED WITH | Orthostatic Hypotension |
|---------|-----------|---------|

Comment: Midodrine is a prodrug, i.e., the therapeutic effect of orally administered midodrine is due to the major metabolite desglymidodrine

Reference: [https://go.drugbank.com/drugs/DB00211#mechanism-of-action](https://go.drugbank.com/drugs/DB00211#mechanism-of-action){:target="_blank"}