# Catalogs

This directory contains source catalog roots.

Each child directory under `catalogs/` is a standalone catalog shape:

```text
<catalog>/
  README.md
  index.yaml
  blueprints/
    <name>/blueprint.yaml
```

Rules:

- `index.yaml` is the catalog entrypoint.
- `blueprints/<name>/blueprint.yaml` is authored source content.
- Source blueprints must not contain cluster-stamped `catalog.suse.ai/*` ownership metadata.
- Cluster-side `BlueprintCatalog` and `BlueprintImportRequest` examples live under `api/suse.ai/v1alpha1/samples/`, not here.
- Catalog roots do not contain bundle output or other cluster manifests.
