# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/chukmunnlee/volatile-app.git
# cd into the cloned directory
git checkout 489a20d65dae766e378bc1af91a5e0ec1191a247
kustomize edit set namespace -- medium
kustomize build ./overlays/dev
```
