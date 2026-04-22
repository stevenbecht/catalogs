# SUSE AI Catalog

Curated source catalog for SUSE AI Factory blueprints.

This catalog is intended to become the primary real catalog shape used by the
platform. Today it lives in this monorepo under `catalogs/suse-ai-catalog/`.
Later it can move to its own repository without changing the internal layout.

Catalog structure:

- `index.yaml`: curated table of contents for the catalog
- `blueprints/<name>/blueprint.yaml`: authored source blueprints

The platform should treat this catalog as external source content. Cluster-side
intake and import resources belong in the main repo's API samples, not here.
