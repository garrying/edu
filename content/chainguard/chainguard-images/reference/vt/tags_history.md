---
title: "vt Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the vt Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-06-10 00:50:47
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/vt/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/vt/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/vt/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/vt/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | June 9th     | `sha256:e485c3a58601d78a44e4ab9fd0f18aa9b7e292f9adfcfa7d89915b51b244b739` |
|  `latest`     | June 5th     | `sha256:8cfab5888804799ee0ee9e466335c0386c761ce857df64a2e3b27b1346abcb1d` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                     | Last Changed | Digest                                                                    |
|---------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` `1.0-dev` `1-dev` `1.0.0-dev` | June 8th     | `sha256:44a7f7434d73add342aba87a7062cef40ab6f1d126f9ddbc159f53604bab5dce` |
|  `1.0` `1.0.0` `1` `latest`                 | June 5th     | `sha256:78056d23f3cdb5461cdd55c41980353432d5e9ba5e23a89dd74941ffcb4577fd` |

