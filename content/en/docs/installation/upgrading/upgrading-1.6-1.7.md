---
title: "Upgrading from v1.6 to v1.7"
linkTitle: "v1.6 to v1.7"
weight: 750
type: "docs"
---

⚠ Following their deprecation in version 1.5, the cert-manager API versions v1alpha2, v1alpha3, and v1beta1 have been removed.
You must ensure that all cert-manager custom resources are stored in etcd at version v1
and that all cert-manager `CustomResourceDefinition`s have only v1 as the stored version
**before** upgrading.
Please read [Migrating Deprecated API Resources] for full instructions.

[Migrating Deprecated API Resources]: ../remove-deprecated-apis/

## Now Follow the Regular Upgrade Process

From here on you can follow the [regular upgrade process](../).
