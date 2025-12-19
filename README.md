# Scoop Bucket

[![Tests](https://github.com/Gildedter/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Gildedter/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/Gildedter/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Gildedter/scoop-bucket/actions/workflows/excavator.yml)

My personal [Scoop](https://scoop.sh) Bucket.

## Manifests

This bucket includes the following manifests:

| Shim Name        | Manifest File                                                                                   | Source Repository                                        |
|---------------------|-------------------------------------------------------------------------------------------------|----------------------------------------------------------|
| `vacuumtube`        | [vacuumtube.json](https://github.com/Gildedter/scoop-bucket/blob/master/bucket/vacuumtube.json) | [VacuumTube](https://github.com/shy1132/VacuumTube)      |

## How to add this bucket?

```pwsh
scoop bucket add Gildedter_scoop-bucket https://github.com/Gildedter/scoop-bucket
```

## How to install a manifest?

```pwsh
scoop install Gildedter_scoop/<manifestname>
```
