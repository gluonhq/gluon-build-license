# gluon-build-license

This action configures the license for your Gluon build

# Usage

* Add this before your Maven build step

```yaml
steps:
- name: Gluon Build License
    uses: gluonhq/gluon-build-license@v1
    with:
      gluon-license: ${{ secrets.GLUON_LICENSE }} 
      target: 'ios'
```

* Configure GLUON_LICENSE in your repo secrets


# License

The project is licensed under GPL 3. See LICENSE file for the full license.

