---
title: "lamotrigine - Seizures"
sidebar: mydoc_sidebar
permalink: lamotrigineseizures.html
toc: false 
---

{% include image.html url="images/lamotrigineseizures.png" file="lamotrigineseizures.png" alt="lamotrigineseizures" %}

## Concepts

|------------|------|---------|
| Identifier | Name | Type    |
|------------|------|---------|
| MESH:C047781 | lamotrigine | Drug |
| InterPro:IPR001696 | Voltage gated sodium channel, alpha subunit | GeneFamily |
| GO:0061530 | aspartate secretion, neurotransmission | BiologicalProcess |
| GO:0061535 | glutamate secretion, neurotransmission | BiologicalProcess |
| HP:0020219 | Motor seizure | PhenotypicFeature |
| MESH:D000066829 | Neuroprotection | PhenotypicFeature |
| MESH:D012640 | Seizures | Disease |
|------------|------|---------|

## Relationships

|---------|-----------|---------|
| Subject | Predicate | Object  |
|---------|-----------|---------|
| Lamotrigine | NEGATIVELY REGULATES | Voltage Gated Sodium Channel, Alpha Subunit |
| Voltage Gated Sodium Channel, Alpha Subunit | POSITIVELY REGULATES | Aspartate Secretion, Neurotransmission |
| Voltage Gated Sodium Channel, Alpha Subunit | POSITIVELY REGULATES | Glutamate Secretion, Neurotransmission |
| Aspartate Secretion, Neurotransmission | POSITIVELY CORRELATED WITH | Motor Seizure |
| Glutamate Secretion, Neurotransmission | POSITIVELY CORRELATED WITH | Motor Seizure |
| Glutamate Secretion, Neurotransmission | NEGATIVELY CORRELATED WITH | Neuroprotection |
| Neuroprotection | NEGATIVELY CORRELATED WITH | Seizures |
| Motor Seizure | POSITIVELY CORRELATED WITH | Seizures |
|---------|-----------|---------|

Reference: [https://go.drugbank.com/drugs/DB00555#mechanism-of-action](https://go.drugbank.com/drugs/DB00555#mechanism-of-action){:target="_blank"}