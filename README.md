![CI](https://github.com/team-gary/asdf-linkerd/workflows/CI/badge.svg)

Changes in this fork:
- Does **NOT** work on Mac because it uses `sort -V` to sort the versions
- Only filters on `stable` versions
- Fixes the issue with installation where checksum is always invalid

---

# asdf-linkerd
linkerd plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

## Install

```
asdf plugin-add linkerd https://github.com/farzadmf/asdf-linkerd.git
```

## Use

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install and manage versions.

## When using `go get`

After using `go get` to install a package you need to run `asdf reshim linkerd` to get any new shims.

## License
MIT License
