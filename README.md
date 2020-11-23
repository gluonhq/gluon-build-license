# gluon-build-license

This action configures the license for your Gluon build

Have a look at the [Hello Gluon CI](https://github.com/gluonhq/hello-gluon-ci) for a sample.

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
