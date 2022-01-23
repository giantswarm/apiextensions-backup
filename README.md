# apiextensions-backup

This repository defines the Giant Swarm Kubernetes APIs in the `backup.giantswarm.io` group including the following:

- `ETCDBackup`

**Note: These APIs were originally defined in `giantswarm/apiextensions` and were moved here to simplify dependency graphs.**

## Code Generation

Code generation is used to generate:

- `DeepCopy` methods for each Go type to satisfy the `runtime.Object` interface (`zz_generated.deepcopy.go`).
- CRDs for each API in YAML format to be applied to a Kubernetes cluster before creating CRs using that API (`config/crd`).

Regenerate these files using `make generate`. Other options can be viewed in `Makefile.custom.mk`.

Additionally, example CRs are generated from code in Go tests using `go test ./... -update`.
