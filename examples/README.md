# Examples Catalog

Small example catalog for learning and smoke-testing the intake flow.

This catalog deliberately stays small and approachable. It uses the same shape
as the real catalog so users can learn one catalog format and one import flow.

Catalog structure:

- `index.yaml`: curated table of contents
- `blueprints/<name>/blueprint.yaml`: authored source blueprints

This directory is source content only. Cluster-side `BlueprintCatalog` and
`BlueprintImportRequest` examples belong in `api/suse.ai/v1alpha1/samples/`.
