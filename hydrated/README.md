# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/chukmunnlee/volatile-app.git
# cd into the cloned directory
git checkout a3932ce592fbbad2ba07e91720e4200f450bd85c
kustomize edit set namespace -- medium
kustomize build ./overlays/dev
```
