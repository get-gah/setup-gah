# setup-gah

This is simple GitHub Action that setups [gah](https://github.com/marverix/gah) - an GitHub Releases app installer, that DOES NOT REQUIRE SUDO!

## Usage

```yaml
- name: Setup gah
  uses: marverix/setup-gah@v1
  with:
    version: latest # optional, default is latest

- name: Install helm
  run: gah install helm
```

## Inputs

* `version`: The version of gah to install. Default is `latest`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
