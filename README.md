[![Build and Test](https://github.com/VIA-BFW/CICITest/actions/workflows/main.yml/badge.svg)](https://github.com/VIA-BFW/CICITest/actions/workflows/main.yml)
# CI / CD with GitHub Actions
This Repo should show CI/CD Piplines with GitHub Actions.

The action build-test-release.yml compiles, tests and releases an .exe file. It only releases the .exe file if a new named tag is published.

```
git tag -a v1.0.8 -m "Release version 1.0.8"
git push origin v1.0.8
```
## Permissions
In order for publishing the .exe file in a release with a GitHub action, this option must be set in the repository settings:
![image](https://github.com/VIA-BFW/CICDTest/assets/168544253/a758c5fb-b65d-4453-bd88-ab27d4d044c1)

(Actions->General)
