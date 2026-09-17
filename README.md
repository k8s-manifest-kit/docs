# k8s-manifest-kit Documentation

This directory is the documentation repository for the k8s-manifest-kit
modules. The implementation lives in the sibling module repositories; this
directory is intentionally not a Go module and is not installed with `go get`.

## Module documentation

- [`engine`](../engine)
- [`pkg`](../pkg)
- [`renderer-helm`](../renderer-helm)
- [`renderer-kustomize`](../renderer-kustomize)
- [`renderer-mem`](../renderer-mem)
- [`renderer-olm-bundle`](../renderer-olm-bundle)
- [`renderer-yaml`](../renderer-yaml)
- [`renderer-gotemplate`](../renderer-gotemplate)
- [`postrenderer-cert`](../postrenderer-cert)
- [`examples`](../examples)

Each module keeps its design and development guides beside its source. Start
with the module README and `AGENTS.md`, then use the documents under `docs/`
for detailed behavior and maintenance notes.

When changing public behavior, update the affected module documentation and
examples in the same change. Validate links and remove references to APIs
that no longer exist.

## License

Apache License 2.0. See [LICENSE](LICENSE).
