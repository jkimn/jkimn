
@@ -38,7 +38,7 @@ And then use this library (change `(the latest version)` to the latest version!)
```

# Contributing
Contributions are welcome ! :D
Contributions are welcome! :D

Most contributions will require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to,
and actually do, grant us the rights to use your contribution. For details, visit https://cla.microsoft.com.
@@ -128,8 +128,8 @@ the reason why is inside this exception map.
## Displaying usage info
There are two forms of "usage strings" provided by this library, both require a target node.

`getAllUsage(node, source, restricted)`  will return a list of all possible commands (executable end-points) under the target node and their human readable path. If `restricted`, it will ignore commands that `source` does not have access to. This will look like [`foo`, `foo <bar>`]
`getAllUsage(node, source, restricted)`  will return a list of all possible commands (executable end-points) under the target node and their human readable path. If `restricted`, it will ignore commands that `source` does not have access to. This will look like [`foo`, `foo <bar>`].

`getSmartUsage(node, source)` will return a map of the child nodes to their "smart usage" human readable path. This tries to squash future-nodes together and show optional & typed information, and can look like `foo (<bar>)`
`getSmartUsage(node, source)` will return a map of the child nodes to their "smart usage" human readable path. This tries to squash future-nodes together and show optional & typed information, and can look like `foo (<bar>)`.

[![GitHub forks](https://img.shields.io/github/forks/Mojang/brigadier.svg?style=social&label=Fork)](https://github.com/Mojang/brigadier/fork) [![GitHub stars](https://img.shields.io/github/stars/Mojang/brigadier.svg?style=social&label=Stars)](https://github.com/Mojang/brigadier/stargazers)
