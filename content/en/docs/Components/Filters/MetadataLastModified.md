---
title: "MetadataLastModified"
weight: 19
date: 2022-07-05
---
{{% pageinfo color="primary" %}}

**Read the [API documentation &raquo;](https://pkg.go.dev/github.com/AdRoll/baker/filter#MetadataLastModified)**
{{% /pageinfo %}}

## Filter *MetadataLastModified*

### Overview
Extract the "last modified" timestamp from the record Metadata and write it to the selected field.

### Configuration

Keys available in the `[filter.config]` section:

|Name|Type|Default|Required|Description|
|----|:--:|:-----:|:------:|-----------|
| DstField| string| ""| true| Name of the field into which write the timestamp to|
