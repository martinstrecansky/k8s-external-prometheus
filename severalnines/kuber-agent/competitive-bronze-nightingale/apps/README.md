# GitOps Root Bootstrap

This directory is managed by the Severalnines Kuber Agent operator for `severalnines-system/apps-root`.

Before Argo can reconcile resources from this root, merge the accompanying PR to accept the bootstrap contents.

## Context

- Repository path: `severalnines/kuber-agent/competitive-bronze-nightingale/apps`
- Provider: `argo`
- Target namespace: `severalnines-system`

After merging, Kuber Agent operator will populate this directory with GitOps-managed artifacts.
Do not remove this README unless you intend to manage the directory manually.
