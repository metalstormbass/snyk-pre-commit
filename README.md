# snyk_pre_commit

Add this to your pre-commit-config.yaml
```
repos:
-   repo: https://github.com/metalstormbass/snyk-pre-commit
    rev: be796f98d3575e1d855251cdb8308f2a1fd8dacb
    hooks:
    - id: snyk-sca
    - id: snyk-code
    - id: snyk-iac
```
