# problem statement
copies a file to a directory

# example usage

> note: in examples, VERSION represents a version of the fs.cp-file pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/fs.cp-file#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/fs.cp-file#VERSION
```

## compose

```yaml
op:
  pkg: { ref: github.com/opspec-pkgs/fs.cp-file#VERSION }
  inputs: { file, dir, name }
  outputs: { dir }
```
