# OHOS fork

- Package: `easy_refresh` 4.0.0
- Upstream: https://github.com/xuelongqy/flutter_easy_refresh
- Purpose: Adds `TargetPlatform.ohos` cases to platform switches so the package compiles with the OpenHarmony Flutter fork.
- Changes: only `TargetPlatform.ohos` handling; no API/behavior changes for other platforms.

Usage in an OHOS Flutter build:

```yaml
dependency_overrides:
  easy_refresh:
    git:
      url: https://github.com/deretame/easy_refresh_ohos.git
      ref: ohos-4.0.0
```
