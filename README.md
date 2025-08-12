# Synaptics Synap – Examples Prebuilt Packages

This repository hosts prebuilt binary packages used with the Synaptics [Astra SL Series Examples](https://github.com/synaptics-synap/examples/tree/main)

Prebuilt binaries are available via GitHub Pages on the `wip/gh-pages` branch:
- [llamac-pp-python](https://synaptics-synap.github.io/examples-prebuilts/llama-cpp-python/)
- [sqlite](https://synaptics-synap.github.io/examples-prebuilts/outetts/)
- [sqlite](https://synaptics-synap.github.io/examples-prebuilts/sqlite/)

🔗 You can use these directly in your build system or with `pip` if applicable.


## Package Metadata

Each package under `/packages` contains metadata and versioning information.

- `packages/llama-cpp-python/metadata.json`
- `packages/outetts/metadata.json`
- `packages/sqlite/metadata.json`

## Deployment

Prebuilt packages are deployed to `wip/gh-pages` branch. To add a new package:

1. Add the package file to `wip/gh-pages/your-package/`.
2. Update `index.xml` (or `simple/` for pip).
3. Commit and push to `wip/gh-pages`.
 
