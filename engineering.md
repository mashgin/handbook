# Engineering

## Version control

* `master` branch -- this is the "sacred" branch that should always be completely functional in production mode. Master should be a *merge-only* branch.
* `dev` branch -- current development branch. Added features should be created seperately and merged into `dev`. Bug & hot fixes can be commited directly. 
* **Feature** or **experimental** branches

**Master branch** should be tagged with release versions: `<version/name>-<YYYYMMDD>`
```sh
$ git tag demo-20150805
```

