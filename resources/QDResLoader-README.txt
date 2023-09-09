This directory is created and handled by QDResLoader. You can delete this README
once any of the following things exist.

This directory itself is loaded as a datapack *and* resourcepack, so any pack.mcmeta
will be considered (using a default provided by QSL if not present) and any data in
"data", as well as resources in "assets" on the client, will be loaded.

You may also create a "packs" directory, and put directories, zips, or jars in there
that will all be loaded as packs. For organization purposes, you may also create a
"datapacks" or "resourcepacks" directory -- packs in those directories will only be
loaded as one type instead of both.

The resources in the main directory cannot be disabled by users, but will be visible
in the "Resource Packs" and "Data Packs" menu, and can be reordered. Packs in all
three pack directories can be disabled as the user pleases, but are all enabled by
default.

Jars are recognized as packs so you can take "datapack-as-mod" JARs and drop them
here instead of in mods, if that's something you would like to do.
