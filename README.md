```
export GITHUB_TOKEN='token'
export GITHUB_USER='debianmaster'
export GITHUB_REPO='flux-sample'
```

```
flux bootstrap github \
    --context=staging \
    --owner=${GITHUB_USER} \
    --repository=${GITHUB_REPO} \
    --branch=main \
    --personal \
    --path=clusters/staging
```
