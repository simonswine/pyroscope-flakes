# Nix flakes for pyroscope

For pyroscope we support a wide range of language ecosystems, this tries to make it more straight forward to build them

## Usage

* Ensure you have nix installed
* Ensure you have https://github.com/nix-community/nix-direnv 

# grafana/pyroscope

# grafana/pyroscope-java

```
$ cd pyroscope-java
$ echo "use flake github:simonswine/pyroscope-flakes?dir=pyroscope-java" >> .envrc
$ direnv allow
```

