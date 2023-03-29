# yaml2jsonnet

Sometimes you needo craft some jsonnet but you may have some existing example in YAML you may want to use as a starting point.

Jsonnet provides this feature by default and its so simple I'll repeat it here in full in the readme:

```bash
jsonnet -e "std.parseYaml(importstr '$1')" | jsonnetfmt -
```

I packaged this up in a github repo because my colleagues frequently ask how to convert some YAML into Jsonnet so I figured this may need to become more easily discoverable somehow.