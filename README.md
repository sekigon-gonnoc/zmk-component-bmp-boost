# ZMK Module for BMP Boost

## west.yaml

```yaml
manifest:
  remotes:
    - name: zmkfirmware
      url-base: https://github.com/zmkfirmware
    - name: sekigon-gonnoc
      url-base: https://github.com/sekigon-gonnoc
  projects:
    - name: zmk-component-bmp-boost
      remote: sekigon-gonnoc
```

## build.yaml

```yaml
include:
  - board: bmp_boost
    shield: tester_pro_micro
```