# Scala 3 ScalaDoc Sidebar Ordering Issue

Scala 3 ScalaDoc puts top-level packages in reverse order in the sidebar.
You can see this by building this repository:

```sh
./mill foo.docJar
open out/foo/docJar.dest/docs/index.html
```

