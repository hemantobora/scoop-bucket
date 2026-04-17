# Hemanto Bora's Scoop Bucket [![Tests](https://github.com/hemantobora/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/hemantobora/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/hemantobora/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/hemantobora/scoop-bucket/actions/workflows/excavator.yml)

A custom [Scoop](https://scoop.sh) bucket for Windows, containing app manifests maintained by Hemanto Bora.

## How do I install these manifests?

First, add this bucket to Scoop:

```powershell
scoop bucket add hemantobora https://github.com/hemantobora/scoop-bucket
```

Then install any app from this bucket:

```powershell
scoop install hemantobora/<manifest>
```

## How do I contribute new manifests?

1. Fork this repository.
2. Add a new JSON manifest file under the `bucket/` directory.
3. Verify it works by running `scoop install <manifest>` locally.
4. Open a pull request with the title format: `app-name: Add version X.Y.Z`.

For guidance on creating manifests, refer to the [Scoop wiki](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests).
