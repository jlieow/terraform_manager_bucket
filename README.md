# About

This repo contains a terraformx manifest for [Scoop](https://scoop.sh).

## Adding this bucket to Scoop

To add the bucket, run `scoop bucket add <name> https://github.com/iSoBored/my-bucket`

## Installing terraformx

To install terraformx, run `scoop install terraformx`

## Uninstalling terraformx

To uninstall terraformx, run `scoop uninstall terraformx`

## Removing this bucket from Scoop

To remove the bucket, run `scoop bucket rm <name>`

## Update hash for new manifests

Each bucket contains a manifest in the form of a json file. To create a new hash for your manifests, run `curl <url> | shasum -a 256` where url is the url in the manifest.
