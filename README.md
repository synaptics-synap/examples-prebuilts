# Synaptics Synap – Examples [Prebuilt Packages](https://synaptics-synap.github.io/examples-prebuilts/)

This repository hosts prebuilt binary packages used with the Synaptics [Astra SL Series Examples](https://github.com/synaptics-synap/examples/tree/main)

These are based on Python 3.10 version.

Prebuilt binaries are available via GitHub Pages on the `wip/gh-pages` branch [here](https://synaptics-synap.github.io/examples-prebuilts/)

##  Usage

You can use these prebuilt packages directly on your **Astra Machina** device based on the file type:

### 📦 Python Wheels (`.whl`)
Install using `pip`:
```bash
pip install <package-name>.whl
```

### 📦 Debian Packages (.deb)
Install using `dpkg`:
```bash
dpkg -i <package-name>.deb
```
 
## Deployment

Prebuilt packages are deployed to `wip/gh-pages` branch. To add a new package:

1. Add the package file to `wip/gh-pages/your-package/`.
2. Update `index.xml` .
3. Commit and push to `wip/gh-pages`.
 
