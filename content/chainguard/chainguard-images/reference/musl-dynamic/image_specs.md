---
title: "musl-dynamic Image Variants"
type: "article"
description: "Detailed specs for musl-dynamic Chainguard Image Variants"
date: 2023-03-07T11:07:52+02:00
lastmod: 2023-03-07T11:07:52+02:00
draft: false
images: []
menu:
  docs:
    parent: "musl-dynamic"
weight: 550
toc: true
---

This page shows detailed information about all available variants of the Chainguard **musl-dynamic** Image.

## Variants Compared
The **musl-dynamic** Chainguard Image currently has one public variant: 

- `latest`

The table has detailed information about each of these variants.

|              | latest        |
|--------------|---------------|
| Default User | `root`        |
| Entrypoint   | not specified |
| CMD          | not specified |
| Workdir      | not specified |
| Has apk?     | no            |
| Has a shell? | no            |

## Image Dependencies
The table shows package distribution across all variants.

|                          | latest |
|--------------------------|--------|
| `alpine-baselayout-data` | X      |
| `alpine-release`         | X      |
| `ca-certificates-bundle` | X      |
| `musl`                   | X      |